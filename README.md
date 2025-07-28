# 📓 Advanced Python Calculator in Jupyter Notebook

This interactive calculator built in a Jupyter Notebook lets users perform both **basic** and **advanced mathematical operations**, using Python's object-oriented features and the `math` module. It includes built-in error handling and is fully extensible.

## 🌟 Features

- ✅ Basic operations: `+`, `-`, `*`, `/`
- 📐 Advanced operations: Exponentiation (`^`), Square Root (`sqrt`), Logarithm (`log`)
- 💥 Robust error handling: invalid inputs, unsupported operations, division by zero
- 🔄 Extensible: add your own operations with `add_operation()`

## 🧰 Requirements

- Python 3.x
- Jupyter Notebook
- `math` module (standard library)

## 🚀 How to Use

1. Open `calculator.ipynb` in Jupyter.
2. Run all cells in order.
3. Input an operation and numeric values when prompted.
4. Enter `exit` to quit.

Example:
Choose a mathematical operation: (+, -, *, /, ^, sqrt, log)  
Enter first number: 16  
Enter second number: 4  
Result: 4.0

## 📂 File Structure

calculator.ipynb   # Jupyter Notebook with calculator code  
README.md          # Project documentation

## 📌 Highlights

- Written with Python classes and methods  
- Supports both unary and binary operations  
- User-friendly and interactive  
- Easy to expand functionality

## 🧠 Examples

cal.add_operation('%', lambda x, y: x % y)  
result = cal.calculate(10, '%', 3)  # Output: 1

