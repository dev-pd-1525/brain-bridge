Brain Bridge: Command-Line Educational Help System
Project Overview
Brain Bridge is a simplified, command-line Educational Help System designed to manage student records, course grades, and perform basic class statistics. The project applies core concepts covered in the subject (e.g., modular design, data structures, file handling) within a practical scenario. It utilizes different login views for teachers and students to control data access.


Features
This project incorporates the required three major functional modules:

User Authentication and Management: Implements distinct login mechanisms for Teachers and Students. Teachers can perform CRUD operations on student records.



Data Processing and Grade Management: Allows for data input of student grades and handles the processing of this data.

Reporting and Analytics: Provides features like calculating class averages, checking enrollment, and generating project team combinations.

Technologies and Tools Used
The following technologies and tools were utilized in the development of this project:

Programming Language: Python [Customize this]

Data Storage: CSV / JSON File System [Customize this]


Version Control: Git & GitHub 

Architectural Pattern: [e.g., Simple Modular Design, MVC if applicable - Customize this]

Steps to Install and Run the Project
This section provides a clear, logical workflow for interacting with the system.


Clone the Repository:

Bash

git clone https://github.com/dev-pd-1525/brain-bridge.git
cd brain-bridge
Set up the Environment (if required):

Bash

# If using Python and virtual environments is required
pip install -r requirements.txt
Execute the Main Application File:

Bash

python main.py
Initial Login Credentials (Example):

Teacher: admin / password123

Student: S101 / pass

Instructions for Testing
The system implements validation and error handling. Testing should focus on verifying functional requirements and robustness:


Functional Verification:

Log in as a Teacher and successfully add a new student record and update an existing student's grade.

Generate a Class Average Report and confirm the results are accurate.

Access Control Testing:

Log in as a Student and attempt to access any Teacher-only function (e.g., deleting a record). The system must restrict access and provide an appropriate error message.

Error Handling Testing:

Attempt to input invalid data (e.g., letters where numbers are expected for a grade). The system should gracefully handle the error and prompt for re-entry.
