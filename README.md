# Basic-Operations-Calculator-using-Python
Simple calculator to add, subtract, multiply, divide and double multiply
# Created by Syeda Damiya Kafait

""Operations should be like 
1
+
2""

print ("Enter first value:")
num1 = int(input(""))
print ("Enter operator (+,-,*,/,**):")
operator = input("")
print ("Enter second value:")
num2 = int(input(""))

if operator == "+":
    print(num1 + num2)
elif operator == "-":
    print(num1 - num2)
elif operator == "*":
    print(num1 * num2)
elif operator == "/":
    print(num1 / num2)
elif operator == "**":
    print(num1 ** num2)
else:
    print("Invalid operator")
