# SimpleCalculatorCOD4682
## Java Calculator Documentation

### Overview
The Java Calculator is a simple console-based application designed to perform basic arithmetic operations. It provides users with a menu-driven interface for selecting operations such as addition, subtraction, multiplication, division, and exponentiation. Additionally, the program offers the option to quit, allowing users to exit the calculator when desired.

### Features
- Addition: Allows users to add two numbers.
- Subtraction: Enables users to subtract one number from another.
- Multiplication: Allows users to multiply two numbers.
- Division: Enables users to divide one number by another.
- Exponentiation: Allows users to calculate the exponentiation of a base to a given exponent.
- Quit: Provides users with the option to exit the calculator.

### Installation
To use the Java Calculator, follow these steps:
1. Ensure you have Java installed on your system.
2. Download the `Calculator.java` file from the repository.
3. Open a terminal or command prompt and navigate to the directory containing `Calculator.java`.
4. Compile the program using the following command:
   ```
   javac Calculator.java
   ```
5. Run the compiled program with the following command:
   ```
   java Calculator
   ```

### Usage
Upon running the Java Calculator program, users will be presented with a menu displaying various arithmetic operations. Users can choose an operation by entering the corresponding number. The program will then prompt users to enter the required numbers for the selected operation. After performing the calculation, the result will be displayed on the console. Users can continue performing calculations or choose the option to quit.

### Code Explanation
The `Calculator` class serves as the main entry point for the program. Within the `main` method, a while loop is used to repeatedly display the calculator menu and handle user input until the user chooses to quit. Based on the user's choice, the program invokes specific methods (`add`, `subtract`, `multiply`, `divide`, `exponentiate`) to perform the corresponding arithmetic operation. These methods take input numbers as parameters and return the result of the operation.

### Conclusion
The Java Calculator provides users with a convenient tool for performing basic arithmetic calculations. Its simple yet functional design makes it suitable for a wide range of users, from students studying mathematics to professionals requiring quick calculations. With its intuitive menu-driven interface and error handling capabilities, the Java Calculator offers a seamless user experience for performing arithmetic operations.
