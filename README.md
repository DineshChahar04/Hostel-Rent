# Hostel / Flat Expense Calculator

Welcome to my **Hostel / Flat Expense Calculator**
This is a simple **Python program** that calculates how much money each person has to pay for the total hostel or flat expenses.
In this program, you enter:
* Hostel / Flat rent
* Food expenses
* Total electricity units used
* Electricity charge per unit
* Number of people living in the room / flat
The program calculates the **total electricity bill** and then divides the total expenses equally among all the people.

This project is made for beginners who are learning Python and want to practice:
* Variables
* `input()`
* `print()`
* `int()`
* Arithmetic operators
* Addition
* Multiplication
* Division
* Basic calculations
* Basic Python logic

----------------------------------------------------------------------------------------------------

## How the Program Works
The program starts by asking for the hostel or flat rent.
```python
rent = int(input("Enter your hostel/flat rent = "))
```
For example:
```text
Enter your hostel/flat rent = 5000
```
Then the program asks for the amount spent on food.
```python
food = int(input("Enter the amount of food ordered = "))
```
For example:
```text
Enter the amount of food ordered = 3000
```
After that, the program asks for the total electricity units used.
```python
electricity_spend = int(input("Enter the total of electricity spend = "))
```
Then it asks for the electricity charge per unit.
```python
charge_per_unit = int(input("Enter the charge per unit = "))
```
Finally, it asks for the number of people living in the room or flat.
```python
persons = int(input("Enter the number of persons living in room/flat = "))
```
The program then calculates how much each person needs to pay.
-----------------------------------------------------------------------------------------------

# How the Calculation Works
The program first calculates the total electricity bill.
```python
total_bill = electricity_spend * charge_per_unit
```
For example:
```text
Electricity units = 200
Charge per unit = 8
```
The calculation will be:
```text
200 × 8 = 1600
```
So:
```text
Total electricity bill = 1600
```

# Calculating the Total Expense
The program adds:
* Food expense
* Hostel / Flat rent
* Electricity bill
The calculation is:
```python
food + rent + total_bill
```
For example:
```text
Food = 3000
Rent = 5000
Electricity = 1600
```
The total expense will be:
```text
3000 + 5000 + 1600 = 9600
```

# Dividing the Expense
After calculating the total expense, the program divides it among all the people.
```python
output = (food + rent + total_bill) // persons
```
For example, if:
```text
Total expense = 9600
Persons = 4
```
Then:
```text
9600 ÷ 4 = 2400
```
So each person will pay:
```text
Each person will pay = 2400
```

# Example
Suppose there are **4 people** living in a flat.
You enter:
```text
Enter your hostel/flat rent = 5000
Enter the amount of food ordered = 3000
Enter the total of electricity spend = 200
Enter the charge per unit = 8
Enter the number of persons living in room/flat = 4
```
The electricity bill will be:
```text
200 × 8 = 1600
```
Total expense:
```text
5000 + 3000 + 1600 = 9600
```
Each person's share:
```text
9600 ÷ 4 = 2400
```
Output:
```text
Each person will pay =  2400
```
------------------------------------------------------------------------------------

# Python Concepts Used

## 1. Variables
The program uses variables such as:
```python
rent = 5000
food = 3000
electricity_spend = 200
charge_per_unit = 8
persons = 4
```
Variables are used to store information.
For example:
```python
rent = 5000
```
stores the rent amount.

## 2. input()
`input()` is used to take information from the user.
Example:
```python
food = input("Enter the amount of food ordered = ")
```
The user can enter:
```text
3000
```
The program receives this value as input.

## 3. int()
`input()` normally gives us a string.
For example:
```python
food = input("Enter the amount of food ordered = ")
```
If the user enters:
```text
3000
```
Python initially treats it as:
```text
"3000"
```
To perform calculations, we convert it into an integer:
```python
food = int(input("Enter the amount of food ordered = "))
```
Now Python can use it for mathematical calculations.
---

## 4. Addition
The program uses `+` to add the expenses.
```python
food + rent + total_bill
```
For example:
```text
3000 + 5000 + 1600
```
Result:
```text
9600
```

## 5. Multiplication
The program uses `*` to calculate the electricity bill.
```python
total_bill = electricity_spend * charge_per_unit
```
For example:
```text
200 × 8 = 1600
```
So:
```text
total_bill = 1600
```

## 6. Floor Division `//`
The program uses:
```python
//
```
to divide the total expense among the people.
Example:
```python
output = 9600 // 4
```
Result:
```text
2400
```
`//` gives the **whole-number result** of the division.
For example:
```text
10 // 3 = 3
```
while:
```text
10 / 3 = 3.333...
```
-----------------------------------------------------------------------------------

# Complete Calculation Flow
The program can be understood like this:
```text
              START
                |
          Enter Flat Rent
                |
          Enter Food Cost
                |
       Enter Electricity Units
                |
     Enter Charge Per Unit
                |
       Enter Number of People
                |
                ↓
     Electricity Bill Calculation
                |
     Units × Charge Per Unit
                |
                ↓
       Add All Total Expenses
                |
      Rent + Food + Electricity
                |
                ↓
       Divide by Number of People
                |
                ↓
       Each Person's Payment
                |
               END
```

# Project Structure

The project is very simple:

```text
Hostel-Expense-Calculator/
│
├── expense_calculator.py
│
└── README.md
```

### `expense_calculator.py`
Contains the complete Python program for calculating each person's expenses.

### `README.md`
Contains information about the project, calculation process, installation, and Python concepts.

-----------------------------------------------------------------------------------------------------------------

#  Technologies Used
* **Python**
* **VS Code / Jupyter Notebook** (recommended)
* **GitHub**
No external Python libraries are required.

# Features
* Hostel / Flat rent calculation
* Food expense calculation
* Electricity bill calculation
* Electricity charge per unit
* Multiple-person expense sharing
* Simple and easy calculations
* Beginner-friendly Python project
* Uses basic arithmetic operators

# Future Improvements
I can improve this project in the future by adding:
* Decimal values for expenses
* Separate food expenses for each person
* Different electricity rates
* Water bill
* Internet bill
* Maintenance charges
* Gas bill
* Multiple rooms
* Monthly expense history
* Total monthly expense report
* GUI interface
* Save expense records
* Automatic monthly calculations

# What I Learned
While making this project, I practiced how to:
```text
Take user input
      ↓
Convert input into integers
      ↓
Store values in variables
      ↓
Multiply electricity units and charge
      ↓
Calculate the electricity bill
      ↓
Add all expenses
      ↓
Divide the total expense among people
      ↓
Display the final result
```
This project helped me understand how basic Python programming can be used to solve **real-life calculation problems**.
---------------------------------------------------------------------------------------------------------------------------------

# Author
**Dinesh Chahar**
Beginner Python Developer!!
Currently learning:
* Python
* C#
* DSA
* OOP

## If You Like This Project
If you found this project useful, you can:------>>> Star the repository 

### Thanks for Using My Program!
**Calculate your expenses easily! **
**Learn Python by building projects! **
