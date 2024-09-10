JavaScript Calculator with Responsive HTML & CSS

This project is a calculator built using HTML, CSS and JavaScript. It features basic arithmetic operations and a clean, responsive design. The calculator is fully functional with buttons for digits (0-9), operations (addition, subtraction, multiplication, and division), and extra features like clear (C) and an equal (=) button to evaluate the result. 

Key Features:
- Responsive calculator UI: The layout adjusts well across different screen sizes.
- Functional buttons for basic arithmetic operations (`+`, `-`, `*`, `/`).
- Clear button (C) to reset the screen and start fresh.
- JavaScript's `eval()` function is used to compute expressions and display results.
- Error handling for invalid expressions, displaying "Error" when the input can't be evaluated.

Technologies Used:
- HTML5: Structure of the calculator.
- CSS3: Styling the calculator, including grid layout for buttons, hover effects, and responsive design.
- JavaScript: Logic to handle input, evaluate expressions, and manage button interactions.

How It Works:
- The calculator takes input via on-screen buttons, and users can build arithmetic expressions in real-time.
- The input is displayed on a text screen using the `addToScreen()` function.
- Clicking the equal button calls the `calculate()` function, which uses `eval()` to compute the result and display it.
- Invalid inputs trigger an error message on the display.
