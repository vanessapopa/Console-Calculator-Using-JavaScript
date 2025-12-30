# Console Calculator Using JavaScript

A console-based calculator application built with JavaScript featuring basic arithmetic operations and mathematical functions.

## Note

This project was completed as part of freeCodeCamp's Full Stack Developer curriculum, under the JavaScript Certification course. Javascript -> Functions -> Build a Calculator.

## Technologies

- JavaScript (ES6+)
- Node.js (for runtime)

## Features

- **Basic Arithmetic Operations**
  - Addition (`calculateSum`)
  - Subtraction (`calculateDifference`)
  - Multiplication (`calculateProduct`)
  - Division (`calculateQuotient`) with zero-division error handling

- **Advanced Mathematical Functions**
  - Square calculation (`calculateSquare`)
  - Square root calculation (`calculateSquareRoot`)

- Console-based output for all calculations
- Built-in test cases demonstrating each function

## Installation & Usage

1. Clone the repository
   ```bash
   git clone https://github.com/vanessapopa/Console-Calculator-Using-JavaScript.git
   ```

2. Navigate to the project directory
   ```bash
   cd Console-Calculator-Using-JavaScript
   ```

3. Run the calculator
   ```bash
   node script.js
   ```

## Example Output

```javascript
// Addition
calculateSum(2, 5)        // Output: 7
calculateSum(10, 10)      // Output: 20

// Subtraction
calculateDifference(22, 5) // Output: 17

// Multiplication
calculateProduct(13, 5)    // Output: 65

// Division
calculateQuotient(7, 11)   // Output: 0.636...
calculateQuotient(3, 0)    // Output: "Error: Division by zero"

// Square
calculateSquare(9)         // Output: 81

// Square Root
calculateSquareRoot(16)    // Output: 4
```

## Credits

Course by freeCodeCamp.

## Preview
<img width="632" height="203" alt="Screenshot 2025-12-30 at 1 11 48 PM" src="https://github.com/user-attachments/assets/82022e37-5651-430a-b9e9-42d71aa796c7" />

