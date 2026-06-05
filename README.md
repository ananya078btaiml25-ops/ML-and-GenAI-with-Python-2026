ASSIGNMENT 2
1. Sum of first 10 natural numbers
total = 0
for i in range(1, 11):
    total += i

print("Sum of first 10 natural numbers:", total)
#2. Factorial of a number
num = int(input("Enter a number: "))
fact = 1

for i in range(1, num + 1):
    fact *= i

print("Factorial of", num, "is", fact)

#3. Print Fibonacci Series
n = int(input("Enter how many Fibonacci numbers to print: "))

a, b = 0, 1
print("Fibonacci Series:")

for _ in range(n):
    print(a, end=" ")
    a, b = b, a + b

#4. Find largest among 3 numbers
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))

if a >= b and a >= c:
    largest = a
elif b >= a and b >= c:
    largest = b
else:
    largest = c

print("Largest number is:", largest)

#5. Student Result System
name = input("Enter student name: ")
roll = input("Enter roll number: ")

subjects = int(input("Enter number of subjects: "))
total = 0

for i in range(1, subjects + 1):
    marks = float(input(f"Enter marks for subject {i}: "))
    total += marks

percentage = (total / (subjects * 100)) * 100

print("\n--- Student Result ---")
print("Name:", name)
print("Roll Number:", roll)
print("Total Marks:", total)
print("Percentage:", round(percentage, 2), "%")

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 50:
    grade = "D"
else:
    grade = "F"

print("Grade:", grade)

ASSIGNMENT 1

#1. Area of Rectangle

length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print("Area of Rectangle =", area)

# 2. Program to calculate Simple Interest

p = float(input("Enter Principal amount: "))
r = float(input("Enter Rate of Interest: "))
t = float(input("Enter Time in years: "))

si = (p * r * t) / 100

print("Simple Interest =", si)

# 3. Convert temperature from Celsius to Fahrenheit

c = float(input("Enter temperature in Celsius: "))

f = (c * 9/5) + 32

print("Temperature in Fahrenheit =", f)

# 4. Program to calculate average of 3 numbers

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))

avg = (a + b + c) / 3

print("Average =", avg)

# 5. Program to find square and cube of a number

num = float(input("Enter a number: "))

square = num ** 2
cube = num ** 3

print("Square =", square)
print("Cube =", cube)

# 6. Swap two numbers without using a third variable

a = float(input("Enter first number (a): "))
b = float(input("Enter second number (b): "))

a, b = b, a

print("After swapping:")
print("a =", a)
print("b =", b)

# 7. Student Report Program

name = input("Enter student name: ")
roll = input("Enter roll number: ")

print("\nEnter marks out of 100:")
m1 = float(input("Subject 1: "))
m2 = float(input("Subject 2: "))
m3 = float(input("Subject 3: "))
m4 = float(input("Subject 4: "))
m5 = float(input("Subject 5: "))

total = m1 + m2 + m3 + m4 + m5
percentage = (total / 500) * 100

print("\n----- STUDENT REPORT -----")
print("Name:", name)
print("Roll Number:", roll)
print("Total Marks:", total)
print("Percentage:", round(percentage, 2), "%")

