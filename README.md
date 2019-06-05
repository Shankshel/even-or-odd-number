# even-or-odd-number
task text:
Create a variable - a large number. Check whether it is even and display the result (Создать переменную — большое число. Проверить является ли оно четным и вывести результат на экран)

# array creation
greeting = [

	"Здравствуйте! Введите, пожалуйста число: ",
	"Хотите узнать четность числа? Введите его: ",
	"Четность чисел - интересная штука... И мы можем ее проверить! Введите свое число и мы узнаем, является ли оно четным или нет: "

]

# output a random number from the array

print greeting.sample

# user interaction (enter numeric value)

num = gets.to_i

# we conclude that the number is even based on the condition of the remainder of division by two

if num % 2 == 0
	puts "Число #{num} - четное"
else
	puts "Число #{num} - нечетное"
end
