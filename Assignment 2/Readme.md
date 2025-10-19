# -----------------------------------------
# 🧮 Assignment 2 – Python Basics
# Submitted by: Hussain Ahmed Rabbani
# -----------------------------------------

# ---------- Task 1 ----------
# Program to check whether a number is even or odd

n = int(input("Enter a Number = "))

if (n % 2) == 0:
    print(f"{n} is an even number")
else:
    print(f"{n} is an odd number")

print("\n-------------------------------------\n")

# ---------- Task 2 ----------
# Program to calculate the sum of integers from 1 to 50

sum = 0

for i in range(1, 51):
    sum = sum + i

print("The sum of numbers from 1 to 50 is:", sum)
