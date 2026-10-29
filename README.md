# CA1.3 Basic Arithmetic Calculator
This submission contains a simple web calculator built with HTML, CSS and JavaScript.
It supports four basic arithmetic operations: addition, subtraction, multiplication and division, and includes input validation as required.

## Development Steps
1. **Build the HTML page structure**
I created the page skeleton, including a heading, two input boxes for numeric input, four operation buttons (Add, Subtract, Multiply, Divide), and a display area for calculation results.

2. **Add CSS styling**
CSS rules are applied to layout the calculator as a centered card, matching the sample design. It defines background colour, button style, text spacing and result panel style.

3. **Implement JavaScript logic and validation**
- Read the values entered by users from the two input fields.
- Validate inputs: check whether inputs are valid numeric values. Non-numeric input will trigger an error message.
- Extra validation for division: prevent division by zero and show a corresponding error.
- Run the selected calculation and show the output on the page.

4. **Testing**
I opened the HTML file in a web browser to test: normal calculations, invalid text input, and division by zero. All validation rules work correctly.

## How to run this calculator
1. Download the `index.html` file.
2. Double-click it to open in any web browser such as Chrome or Edge.
3. Enter two numbers and click one of the four operation buttons to get the result.
