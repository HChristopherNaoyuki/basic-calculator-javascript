# Calculator Web App

This is a simple and stylish web-based calculator built with HTML, CSS, and JavaScript. It supports basic arithmetic operations (addition, subtraction, multiplication, division) and allows users to toggle between light and dark modes for a more personalized user experience.

## Features

- **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
- **Toggle Theme**: Switch between light and dark mode for a customized appearance.
- **Responsive Layout**: The layout adapts to different screen sizes, providing an optimal experience on both desktop and mobile devices.
- **Error Handling**: Displays an error message if an invalid expression is entered.
- **Clear Button**: Reset the calculator to its initial state.

## Technologies Used

- **HTML**: Markup for the structure of the calculator.
- **CSS**: Styling for layout, buttons, light/dark mode themes, and transitions.
- **JavaScript**: Logic for handling button clicks, performing calculations, and managing the theme toggle.

## Installation

You can run this calculator app locally by following these steps:

1. **Clone or Download the Repository**:
   - Clone the repository using Git:
     ```bash
     git clone https://github.com/HChristopherNaoyuki/basic-calculator-web.git
     ```
   - Or, download the ZIP file and extract it.

2. **Open in Browser**:
   - Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Safari).

## Usage

1. **Perform Calculations**:
   - Click the numeric and operator buttons to form an expression.
   - Press the "=" button to calculate the result.
   - Use the "AC" button to clear the current expression.

2. **Toggle Theme**:
   - Click the "Switch to Light Mode" button to toggle between light and dark themes.

## Code Explanation

- **HTML**: The structure contains a `div` for the calculator, a display section for showing the current input and result, and buttons for each digit and operator.
  
- **CSS**: The styles provide a modern look, including:
  - Flexbox for centering and organizing the layout.
  - Grid for the calculator buttons.
  - Transitions for smooth theme changes and button interactions.

- **JavaScript**: 
  - The `toggleThemeBtn` toggles between dark and light themes when clicked.
  - Each button has an event listener that updates the display or performs a calculation when clicked.
  - The `eval()` function is used for calculating the result when the "=" button is pressed. Basic error handling ensures the app doesn’t crash on invalid input.

## Contributions

Feel free to fork this repository and make your own improvements! Pull requests are welcome.
