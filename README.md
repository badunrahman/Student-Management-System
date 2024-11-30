# Student-Management-System
Overview
The Student Management System is a Java application with a graphical user interface (GUI) built using JavaFX. 
It allows users to manage student records, including adding, deleting, searching, displaying, saving, and loading student data.
Additionally, it provides functionality to sort students by Name, ID, or GPA.

Features

Add new students with unique IDs.
Delete existing students by ID.
Search for students by ID.
Display all students in a table.
Save student data to a text file.
Load student data from a text file.
Sort students by Name, ID, or GPA.


Setup Instructions
Prerequisites
Java Development Kit (JDK) 8 or higher
JavaFX SDK (if using JDK 11 or higher)


Steps
1. Download the Source Code
Clone the repository or download the source code files into a directory on your system.

2. Set Up JavaFX (For JDK 11 or Higher)
Extract the JavaFX SDK to a location on your system.
Note the path to the lib folder within the JavaFX SDK.
  - **IntelliJ IDEA:**
    - Go to `File > Project Structure > Libraries`.
    - Click `+` to add the JavaFX SDK `lib` folder.
  - **Eclipse:**
    - Right-click on the project > `Build Path > Configure Build Path`.
    - Under `Libraries`, add the JavaFX SDK `lib` folder.
  - **NetBeans:**
    - Right-click on the project > `Properties > Libraries`.
    - Add the JavaFX SDK `lib` folder.

- **Set VM Options (For Running):**
  - Add the following VM options when running the application:
--module-path "/Users/badunrahman/Documents/javafx-sdk-23.0.1/lib" --add-modules javafx.controls,javafx.fxml,javafx.web
  - Replace `/Users/badunrahman/Documents/javafx-sdk-23.0.1/lib` with the actual path to your JavaFX SDK `lib` directory.


3. Compile the Source Files
Open a terminal or command prompt and navigate to the directory containing the source files.

4. Run the Application


Usage Guidelines


1. Launching the Application
After running the application, the main window will appear with input fields and buttons.

Adding a Student

**Enter the student's Name, ID, and GPA.
Click Add Student.
Ensure all fields are filled correctly.
A success message will confirm the addition.**


Deleting a Student

****Click Delete Student.
Enter the ID of the student to delete.
Confirm the deletion.**


Searching for a Student

**Click Search by ID.
**Enter the ID of the student to search for.
The student's details will be displayed.**


Displaying All Students**

**Click Display All Students.
The table will show all students currently in the system.**


Sorting Students

**Use the Sort by Name, Sort by ID, or Sort by GPA buttons to sort the students.
The table will update accordingly.**

Saving Data to a File

**Click Save to File.
Enter a file name (e.g., students.txt).
The data will be saved, and a confirmation message will appear.**

Loading Data from a File

**Click Load from File.
Enter the file name containing the student data.
The data will be loaded, and the table will update.**

Exiting the Application

**Click Exit to close the application.**


Notes
Data Persistence: Ensure you save data before exiting if you want to retain the student records.
Unique IDs: Each student must have a unique ID. Duplicate IDs are not allowed.
GPA Range: GPA must be a numeric value between 0.0 and 5.0.

Troubleshooting
JavaFX Errors: Ensure the JavaFX SDK is correctly set up and the module paths are properly configured.
Input Errors: If you encounter input validation errors, double-check that all fields are filled with valid data.
File Operations: When loading or saving data, ensure the file paths and names are correct.


Contact Information
For any issues or questions, please contact:

Author: Badun Rahman
Email: badun.12121@gamil.com
