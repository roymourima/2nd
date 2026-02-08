# Check if a number is odd or even

number = int(input("Enter a number: "))
if (number % 2) == 0:
    print(number," is a Even number.")
else:
    print(number,"is a Odd number.")



# Sum of Integers from 1 to 50 Using a Loop

total = 0
for number in range(1, 51):
    total += number
print("The sum of integers from 1 to 50 is:", total)
