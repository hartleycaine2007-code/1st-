## Coquette Calculator 

The Coquette Calculator is a stylish and user-friendly console-based calculator that supports continuous calculations, history tracking, and input validation. This project serves as a demonstration of Java fundamentals, loops, condition handling, OOP integration, and clean UI design.

## Features

1. Menu-Driven Interface
- Start Calculator
- View Previous Calculations
- Exit the Program

2. Continuous Calculation Mode
- Enter a starting number
- Perform operations infinitely (+, −, ×, ÷)
- Type "=" to checkpoint results
- Type "stop" to return to the main menu
- Prevents invalid inputs and division by zero

3. Calculation History (Array Implementation)
- Stores completed equations
- Displays all saved operations

4. Error Handling
- Catches non-numeric input
- Rejects invalid operators
- Handles division by zero safely


## How to Compile and Run?

Requirements:
- Java JDK 8 or higher
- terminal or command prompt

1.	Compile the Program
- Make sure the .java files are in the same folder.
- javac CoquetteCalculator.java CalculatorHistory.java


2. Run the Program
- java CoquetteCalculator
## Group Member Contributions

- Kassandra Pamienta – Basics LeadUser input, menu creation, loops, error handling.
- Krystiana Ricaro – Array & History LeadDesigned and implemented history storage using arrays.
- Hartley Caine Rubia – Integration LeadContinuous calculation logic, linking components, main functionality.
## Challenges Faced & Solutions

1. Input Mismatch Errors
- Problem: The group entered letters when numbers were expected, causing program crashes.
- Solution: Used scanner.hasNextDouble() loops to validate numeric input before accepting.

2. Array Bounds Issues (History Storage)
- Problem: Running out of space when storing too many equations.
- Solution: Upgraded to a dynamic array approach (or manually handled array index checking) inside CalculatorHistory.

3. Division by Zero
- Problem: Inputting zero in division caused runtime errors.
- Solution: Added a check:
if (nextNumber != 0) { ... } else { warn user }


4. Resetting Equation History After "="
- Problem: The string builder kept stacking previous operations.
- Solution: Reset equation string after saving:
equationString.setLength(0);
equationString.append(currentTotal);


Thank you for checking out our Coquette Calculator!
We hope you enjoy the smooth, cute, and functional computing experience. ♡
## Screenshots

![image](https://github.com/hartleycaine2007-code/1st-/blob/1884ea942506fd870f16021984a8870049a2314d/Screenshot%20(191).png)
