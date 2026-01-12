# ✖️ Multiplication Table Generator 🧮

A simple Python program that **generates a multiplication table** for any number entered by the user. Perfect for beginners learning Python and loops! 🐍✨

## Features ⭐

- 🔢 Generates a multiplication table from 1 to 12  
- 🖥️ Simple user input interface  
- 🐍 Easy-to-understand Python code  

## Requirements 🛠️

- Python 3.x  

## How to Run ▶️

1. Clone or download this repository  
2. Open the Python file (`multiplication_table.py`) in your IDE or editor  
3. Run the script:

```bash
python multiplication_table.py
```
4. Enter any number when prompted, and the program will display its multiplication table from 1 to 12.

### Code Overview 📝
```bash
num = int (input ("Enter a number: "))
print ()
print ("==========================================")
print ()
for i in range (1, 13):
    print ("             ", num, "x", i, "=", num * i)
print ()
print ("==========================================")
print ()
```

### How it Works 🔍

1. 🔢 The program asks the user to enter a number.
2. 🔄 A for loop runs from 1 to 12.
3. ✖️ In each iteration, the program calculates the product of the number and the current loop index.
4. 📊 The result is printed in a neat, readable format.

### Example Output 📸
[![Multiplication Table](https://github.com/owaiskazmi/Multiplication-Table/blob/main/Screenshots/table.png)](https://github.com/owaiskazmi/Multiplication-Table/blob/main/Screenshots/table.png)
