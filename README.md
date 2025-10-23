🧑‍💻 Author

Name: Juliet Mulenga
GitHub: @julietmulenga

Institution: Mulungushi University
Course: ICT251 – Web Technologies
Date: 23rd October 2025



🧮 ICS-Quadratic-Grader-Mulenga-Juliet
📘 Project Description

This project is a single-file web application developed for the ICT251 – Web Technologies course at Mulungushi University.
It is built using HTML and JavaScript and performs two main functions:

Solves quadratic equations of the form ax² + bx + c = 0.

Converts a numeric score (0–100) into a letter grade based on a specified grading scale.

The application runs fully offline — simply open the file index.html in any modern web browser.

⚙️ Features
🔹 Quadratic Equation Solver

Inputs for coefficients a, b, and c.

Input validation (ensures a ≠ 0 and all fields are numbers).

Displays:

Discriminant (D = b² − 4ac)

Nature of roots (real, repeated, or complex)

Root values, rounded neatly.

Includes a Reset button to clear inputs.

🔹 Grading System

Accepts a numeric score between 0 and 100.

Validates input range.

Displays the letter grade and a short message (e.g.,

Score 82 → Grade A)

Grading Scale:

Score Range	Grade
85–100	A+
75–84	A
65–74	B+
60–64	B
55–59	C+
50–54	C
0–49	D



💻 How to Run

Copy or download this repository:

https://github.com/julietmulenga/ICS-Quadratic-Grader-Mulenga-Juliet.git


download and open the index.html file directly on your phone or web browser.

Use the two sections on the page to:

Solve a quadratic equation.

Convert a score into a letter grade.

No installation or internet connection is required.

🧪 Test Cases
Quadratic Solver
a	 b	c 	Expected Output
1	-3	2 	D = 1 → Two distinct real roots (x₁=2, x₂=1)
1	 2	1 	D = 0 → One real repeated root (x = -1)
1  1 	2	  D < 0 → Two complex roots


Grading System

Score	Expected Grade:

100	A+
85	A+
75	A
65	B+
60	B
55	C+
50	C
49	D
0	D
