# Python Programming Tasks

This repository contains two basic Python programming tasks demonstrating fundamental concepts like conditional statements and loops.

## Tasks Overview

### Task 1: Check if a Number is Even or Odd
A simple program that determines whether a user-input number is even or odd.

### Task 2: Sum of Integers from 1 to 50 Using a Loop
A program that calculates the sum of all integers from 1 to 50 using a for loop.

---

## Task 1: Check if a Number is Even or Odd

### Description
This program takes an integer input from the user and checks whether it is even or odd using the modulus operator.

### How It Works
- The program uses the modulus operator (`%`) to check divisibility by 2
- If `number % 2 == 0`, the number is even
- Otherwise, the number is odd

### Usage
```bash
python "Task_1_Check if a Number is Even or Odd.py"

number = int(input("Enter a number: "))

if number % 2 == 0:
    print(f"{number} is an even number.")
else:
    print(f"{number} is an odd number.")
```

### Example Output
```
Enter a number: 7
7 is an odd number.
```

```
Enter a number: 12
12 is an even number.
```

### Code Explanation
- `input()` - Gets user input as a string
- `int()` - Converts the string to an integer
- `%` - Modulus operator that returns the remainder of division
- `f-string` - Formatted string for clean output

---

## Task 2: Sum of Integers from 1 to 50 Using a Loop

### Description
This program calculates the sum of all integers from 1 to 50 using a for loop and displays the result.

### How It Works
- Initializes a variable `total` to 0
- Uses a `for` loop with `range(1, 51)` to iterate through numbers 1 to 50
- Adds each number to the running total
- Prints the final sum

### Usage
```bash
python "Task_2_Sum of Integers from 1 to 50 Using a Loop.py"

total = 0

for num in range(1,51):
    total += num

print(f"The sum of numbers from 1 to 50 is: {total}")

```

### Example Output
```
The sum of numbers from 1 to 50 is: 1275
```

### Code Explanation
- `range(1, 51)` - Generates numbers from 1 to 50 (51 is exclusive)
- `+=` - Compound assignment operator (equivalent to `total = total + num`)
- The mathematical formula for this sum is: n(n+1)/2 = 50(51)/2 = 1275

---

## Author
Baldutt Upadhyay