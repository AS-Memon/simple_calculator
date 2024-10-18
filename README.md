# simple_calculator
print("Select the operation you want:")
print("1 for Multiplication")
print("2 for Subtraction")
print("3 for Division")
print("4 for Addition")
operation = int(input("Enter the number according to your operation: "))
if operation == [1/2/3/4]:
        
    number_count = int(input("How many numbers do you want to calculate? "))


    result = float(input("Enter the first number: "))


    for i in range(1, number_count):
        num = float(input(f"Enter number {i + 1}: "))

        if operation == 1:
            result *= num
        elif operation == 2:
            result -= num
        elif operation == 3:
            result /= num
        elif operation == 4:
            result += num
        else:
            print("You entered an invalid operation number.")
            break
    if operation in [1, 2, 3, 4]:
        print(f"The result of the operation is: {result}")
print("you entered wrong number")
