# 1. Student Grade generator

This Java script code prompts the use to input the student marks. If the Student mark corresponds to the grade based on the grading scale, the output will be displayed.

## Grading Scale

1. A(79 to 100)
2. B(60 to 79)
3. C(59 to 59)
4. D(40 to 49)
5. E(0 to 39)

## How it works
1. Open the vscode terminal 
2. Run the script using the command: node challenge1.js
3. Enter the student marks between 0 and 100
4. The script should display according to corresponding grade.

# 2. Speed Detector calculator 
This script calculates the demerit points for a driver's speed and rhe speed limit.

## How it works
The program defines a function calculatePoints that takes speed as input.

It then checks if the speed is less than or equal to the speed limit which is for now 70 and if so, it prints "Ok" indicating that there ere points.

If not so, the script calculates the excess speed by subtracting the speed limit from the entered speed.

it then calculates demerit points by rounding down (using Math.floor) the excess speed divided by 5.

It then checks if the demerit points exceed 12 and if it does exceed, it prints "License suspended".

Otherwise, it prints the number of demerit points received.

## 3. Net salary Calculator
this script calculates the individual's net salary in Kenya.

The code : calculates gross salary by adding basic salary and benefits.
it then calculates desuction based on PAye, NHIF and NSSF rates
it goes on to calculate the net salary by subtracting deductions from gross salary

the results is displayed on the console.

## Display/output
The prompt should display 
1. gross salary
2. PAYE deduction 
3. NHIF deduction
4. NSSF decuction
5. total deductions
6. Net salary