

length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print("Area of Rectangle =", area)


# Program to calculate Simple Interest

p = float(input("Enter Principal amount: "))
r = float(input("Enter Rate of Interest: "))
t = float(input("Enter Time in years: "))

si = (p * r * t) / 100

print("Simple Interest =", si)

# Convert temperature from Celsius to Fahrenheit

c = float(input("Enter temperature in Celsius: "))

f = (c * 9/5) + 32

print("Temperature in Fahrenheit =", f)

# Program to calculate average of 3 numbers

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))

avg = (a + b + c) / 3

print("Average =", avg)

# Program to find square and cube of a number

num = float(input("Enter a number: "))

square = num ** 2
cube = num ** 3

print("Square =", square)
print("Cube =", cube)

# Swap two numbers without using a third variable

a = float(input("Enter first number (a): "))
b = float(input("Enter second number (b): "))

a, b = b, a

print("After swapping:")
print("a =", a)
print("b =", b)

# Student Report Program

# Taking student details
name = input("Enter student name: ")
roll = input("Enter roll number: ")

# Taking marks for 5 subjects
print("\nEnter marks out of 100:")
m1 = float(input("Subject 1: "))
m2 = float(input("Subject 2: "))
m3 = float(input("Subject 3: "))
m4 = float(input("Subject 4: "))
m5 = float(input("Subject 5: "))

# Calculating total and percentage
total = m1 + m2 + m3 + m4 + m5
percentage = (total / 500) * 100

# Displaying the report
print("\n----- STUDENT REPORT -----")
print("Name:", name)
print("Roll Number:", roll)
print("Total Marks:", total)
print("Percentage:", round(percentage, 2), "%")
```

---

If you want, I can also **combine all programs into one menu‑driven application** for your assignment.
