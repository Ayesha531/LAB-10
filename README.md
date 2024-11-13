Name of the members:
Amna Mukarram (CT-105)
Ayesha Zahid (CT-104)
Tehzeeb ghazi (CT-107)

Calculator Program Documentation
Overview
This document outlines the steps taken to recreate a basic calculator program in C, using functions for addition, subtraction, multiplication, and division.
Steps Taken:
1. Defined Function Prototypes: Declared function prototypes for add, subtract, multiply, and divide at the top of the program.
2. Main Function: Created the main function, which prompts the user to input an operator and two integers.
3. Input Validation: Implemented input validation to ensure the user enters a valid operator and integers.
4. Switch Statement: Used a switch statement to determine which operation to perform based on the user's input.
5. Function Calls: Called the corresponding function (add, subtract, multiply, or divide) based on the operator.
6. Error Handling: Implemented error handling for division by zero.
7. Function Definitions: Defined the add, subtract, multiply, and divide functions.

GitHub Commands Used:
To recreate this project on GitHub, follow these steps:
Step 1: Create a new repository
bash
git init calculator
cd calculator

Step 2: Create a new file for the calculator program
bash
touch calculator.c

Step 3: Add the calculator program code to the file
bash
nano calculator.c
Paste the code into the file and save.

Step 4: Add the file to the Git repository
bash
git add calculator.c

Step 5: Commit the changes
bash
git commit -m "Initial commit of calculator program"

Step 6: Create a new repository on GitHub
Create a new repository on GitHub and link it to your local repository.

Step 7: Push the changes to GitHub
bash
git remote add origin (link unavailable)
git push -u origin master
Replace your-username with your actual GitHub username.
