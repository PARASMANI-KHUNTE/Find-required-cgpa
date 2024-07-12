# Find-required-cgpa

# CGPA Calculator

A simple web application to calculate the required CGPA for the remaining semesters to achieve an overall target CGPA. This application uses vanilla JavaScript for the logic and Tailwind CSS for styling.

## Features

- Input CGPA for the first three semesters.
- Calculate the required CGPA for the remaining three semesters to achieve target overall CGPAs of 7, 8, 9, and 10.
- Display a message if achieving the target CGPA is not possible.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Tailwind CSS](https://tailwindcss.com/)

## How to Use

1. Clone the repository or download the HTML file.
2. Open the `index.html` file in a web browser.
3. Enter the CGPA for the first three semesters.
4. Click the "Calculate" button to see the required CGPA for the remaining semesters.

## Installation

No installation is required. Simply open the `index.html` file in your web browser.

## Code Overview

### HTML

The HTML file contains a form to input the CGPA for the first three semesters and a button to calculate the required CGPA for the remaining semesters. It also includes a section to display the results.

### JavaScript

The JavaScript function `calculateCGPA` retrieves the input values, calculates the required CGPA for the remaining semesters, and updates the result section with the required CGPA or a message indicating that the target CGPA is not possible.

### Tailwind CSS

Tailwind CSS is used to style the form and result section, making the application more visually appealing.

## Example

To achieve an overall CGPA of 8.0:

- If your CGPA for the first three semesters are 6.5, 7.0, and 7.5, respectively, the application will calculate the required CGPA for the remaining three semesters.
- The result will show the required CGPA for each target (7, 8, 9, 10) or indicate if the target is not possible.



## License

This project is open source and available under the [MIT License](LICENSE).


