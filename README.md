# checking-numbers---odd-or-even28-100
num = int(input("Enter any number: "))
flag = num % 2

if flag == 0:
    print(num, "is an even number")
elif flag == 1:
    print(num, "is an odd number")
else:
    print("Error, Invalid input")
