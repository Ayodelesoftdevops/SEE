# 🎉 Fun Calculator 🎉

Welcome to the **Fun Calculator** — a simple and playful Python program that lets you add, subtract, multiply, and divide two numbers like a boss! 😎

## Features

- Works with decimal numbers (floats) — fancy, right? ✨
- Performs basic arithmetic operations:
  - Addition ➕
  - Subtraction ➖
  - Multiplication ✖️
  - Division ➗
- Prints the results in a clear, fun format with emojis! 🥳

## How to Use

1. Clone this repo or download the script.
2. Run the Python script:

```bash
python fun_calculator.py
Enter the first number when prompted.

Enter the second number.

See the results of all four operations instantly!

Code Overview
python
Copy
Edit
# Step 1: Ask the user to input the first number (supports decimals!)
num1 = float(input("Enter the first number: "))

# Step 2: Ask the user to input the second number
num2 = float(input("Enter the second number: "))

# Step 3: Calculate the sum, difference, product, and quotient
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2  # Be careful not to divide by zero!

# Step 4: Print the results in a fun and friendly way
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")          # ➕
print(f"Difference: {difference_result}")  # ➖
print(f"Product: {product_result}")        # ✖️
print(f"Quotient: {quotient_result}")      # ➗
Notes
Make sure you don’t divide by zero — this script assumes you’re responsible! 😅

Feel free to modify and add more features like input validation or custom operations.

Made with ❤️ and Python magic by [Ayodelesoftdevops]
