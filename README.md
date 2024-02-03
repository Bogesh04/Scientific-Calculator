# Calculator Java Swing Application

This Java program is a simple calculator application implemented using the Swing GUI toolkit. The calculator provides basic arithmetic operations such as addition, subtraction, multiplication, and division. It also includes buttons for decimal input, clearing the display, and deleting the last entered character.

## How to Run:

1. **Compile and Run:**
   - Compile the program using `javac`:
     ```bash
     javac Calculator.java
     ```
   - Run the compiled program:
     ```bash
     java Calculator
     ```

2. **Calculator Interface:**
   - The calculator window will appear, featuring a display at the top and buttons for numbers and operations below.

3. **Basic Operations:**
   - Click on number buttons (0-9) to enter numbers.
   - Use the operation buttons (+, -, *, /) for arithmetic operations.
   - Press the "=" button to calculate the result.
   - Click on the "CE" button to clear the last entry.
   - Use the "CLR" button to clear the entire display.

4. **Decimal Input:**
   - The "." button allows the input of decimal numbers.

5. **Exiting the Application:**
   - Close the calculator window to exit the application.

## Application Logic:

- The calculator handles basic arithmetic operations (+, -, *, /).
- The "=" button triggers the calculation of the result based on the current operator.
- The "CE" button clears the last entered character, and the "CLR" button clears the entire display.
- Decimal input is facilitated by the "." button.
- The calculator follows the order of operations.

## Notes:

- This calculator application is a basic example and does not handle more advanced features like parentheses or scientific functions.
- The GUI is implemented using Java Swing components (JFrame, JButton, JTextField, etc.).
- The code structure separates the GUI initialization and event handling logic.

## Developer:

- This calculator application was developed by an anonymous contributor.
