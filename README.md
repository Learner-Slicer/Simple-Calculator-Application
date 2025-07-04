Simple Calculator Application

Overview:
This project is part of an internship assignment at Prodigy InfoTech. The focus of this task was to develop a simple calculator using HTML, CSS, and JavaScript, and to apply manual testing techniques by writing structured test cases.
The calculator performs basic arithmetic operations such as addition, subtraction, multiplication, and division. I also validated different input types including invalid scenarios, edge cases, and decimal-based operations.

Features:
- Performs basic arithmetic operations (addition, subtraction, multiplication, division)
- Handles decimal values and negative numbers
- Validates simple chained operations such as 2 + 3 * 4
- Displays basic errors (e.g., division by zero)
- Manual test cases written and reviewed
- Built using clean HTML, CSS, and JavaScript

Usage:
1. Clone or download this repository
2. Open `index.html` in a browser
3. Use the calculator interface to test functionality

Project Structure:
Simple-Calculator-Application
├── index.html → Main UI structure
├── style.css → Styling for the calculator
├── script.js → Functionality and logic
└── README.md → Manual testing documentation

Test Case Coverage:
This project includes manually written test cases covering the following:
- Addition of two positive numbers
- Subtraction that results in a negative value
- Multiplication using decimal inputs
- Division using integers
- Chained operations with different operator combinations
- Division by zero
- Input of letters or symbols
- Resetting values using the CE (Clear Entry) function

Each test case includes the following fields:
- Test Case ID
- Description
- Preconditions
- Test Steps
- Expected Result
These were written and reviewed using a browser-based interface during execution.

Testing:
All tests were performed manually in a modern web browser (Chrome and Firefox). Special cases such as dividing by zero or attempting to enter invalid characters were reviewed for expected handling. The calculator performed accurately in all documented cases, with proper layout and input handling.

Author:
Rathun Rajeevan  
BCA Student – Jain (Deemed-to-be) University  
Software Testing Intern – Prodigy InfoTech

Acknowledgements:
This task is part of the Prodigy InfoTech Software Testing Internship. Thanks to the Prodigy InfoTech team for outlining this exercise and supporting the learning process.

Reference:
The calculator interface was tested using inspiration from:  
https://dunizb.github.io/sCalc/
