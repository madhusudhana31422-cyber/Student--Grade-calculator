# Student Grade Calculator

A beginner-friendly Python project to calculate student grades.

## Description
This program accepts marks for three subjects, calculates the total and average, and assigns a grade based on the average using conditional statements.

## Features
- Takes input for 3 subjects
- Calculates total marks
- Calculates average marks
- Displays grade using if-else conditions

## Technologies Used
- Python

## Purpose
This project was created to practice basic Python concepts like input/output, arithmetic operations, and conditional logic.

## Author
Madhusudhana R

##CODE

Maths=int(input("Enter the obtained Maths exam Marks:"))
Science=int(input("Enter the obtained Science exam Marks:"))
Social=int(input("Enter the obtained Social exam Marks:"))

Total=Maths+Science+Social
print(f"Total Marks:{Total}")

Average=Total//3
print(f"Average Marks:{Average}")

if Average>=90:
    print("Grade A allocated to Marks")
elif Average>=75:
    print("Grade B allocated to Marks")
elif Average>=50:
    print("Grade C allocated to Marks")
else:
     print("Fail.")
     
## Sample Output
Enter marks for subject 1: 80  
Enter marks for subject 2: 75  
Enter marks for subject 3: 85  

Total: 240  
Average: 80  
Grade: A
