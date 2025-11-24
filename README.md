# brain-bridge
Brain Bridge is a simplified command-line Educational Help System designed to manage student records, course grades, and perform basic class statistics. It uses different login views for Teachers and Students to control data access and provides features like calculating class averages, checking enrollment, and generating project team combinations.
# BRAIN BRIDGE: Educational Help System v0.1.1
## Project Overview
BRAIN BRIDGE is a command-line application designed to simulate a simple academic records system. It allows teachers to manage student scores, calculate class averages and standard deviations, and allows students to view their grades. The project demonstrates core Python OOP, set operations, and external library integration (NumPy, itertools).

## Features 
* Role-Based Access: Separate login flows for Teachers (credential-based) and Students (ID-based).
* Grade Management: Teachers can enter/update student scores and credit hours, and the system performs automated letter grade conversion.
* Class Analytics: Calculates class average and standard deviation (using NumPy) for specified courses.
* Set Analysis: Analyzes mock enrollment data (Math vs. CS) using set difference and union operations.
* Project Grouping: Generates possible 3-person project groups using `itertools.combinations`.
* Individual Student View: Students can view their recorded scores, credits, and calculated GPA (placeholder).

## Technologies/Tools Used 
* Language: Python 3.x
* Libraries: `numpy` (for standard deviation), `itertools` (for combinations)
* Architecture: Command Line Interface (CLI) and In-Memory Data Storage (Python Dictionaries)

##  Steps to Install & Run the Project 
1.  Prerequisites: Ensure you have Python 3.x installed.
2.  Install Dependencies: This project requires NumPy. Run the following command:
    ```bash
    pip install numpy
    ```
3.  Run the System: Execute the main Python file:
    ```bash
    python main.py 
    ```
4.  Start: When prompted with `-->[ON/OFF]`, type `ON`.

##  Instructions for Testing

### Teacher Credentials (Login: 1)
* Username: `prof_vishal` / Password: `grade123`
* Username: `dr_kavita` / Password: `math_pass`

### Student IDs (Login: 2)
* `25BCE10599` (PRATEEK DAS)
* `25BCE0001` (Ram Kumar)
