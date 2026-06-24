num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))


addition_result = num1 + num2
print("Addition:", addition_result)

subtraction_result = num1 - num2
print("Subtraction:", subtraction_result)

multiplication_result = num1 * num2
print("Multiplication:", multiplication_result)

if num2 != 0:
    division_result = num1 / num2
    print("Division:", division_result)
else:
    print("Error: Division by zero is not allowed.")
