# Course Management System

A simple, console-based course management system built in Java. It provides separate interfaces for students and teachers to manage course enrollments, assignments, and grades through a menu-driven workflow.

---

## Features

This project includes a variety of features for both students and teachers:

* **Dual Role System**: Separate login and registration for **Students** and **Teachers**.
* **Student Dashboard**:
    * View all available courses.
    * Enroll in (add) a new course.
    * Unenroll from (drop) a course.
    * View marks for all enrolled courses.
* **Teacher Dashboard**:
    * Add new courses to the system.
    * Remove courses.
    * Assign grades to students for specific courses.
* **Data Persistence**: A "Save Details" option to save the current state of students, teachers, and courses to files.
* **UI Customization**: A "System Theme" option to change the console's background color for a personalized experience.

---

## Technologies Used

* **Java**: The entire application is built using core Java, without any external frameworks.

---

## How to Compile and Run

To run this project on your local machine, follow these steps:

1.  **Navigate to the Source Directory**
    Open your terminal or command prompt and navigate to the directory containing the project's source code (where `Main.java` is located).
    ```sh
    cd  \Course-Management-System-Java-main\CourseManagementSystem\out\production\CourseManagementSystem
    ```

2.  **Compile the Code**
    Use the Java compiler (`javac`) to compile the source files.
    ```sh
    javac Main.java
    ```

3.  **Run the Application**
    Execute the compiled code using the `java` command.
    ```sh
    java Main
    ```

---

## Project Walkthrough & Screenshots

Here is a visual walkthrough of the application's core functionality.

### 1. Registration and Login
Users can register as either a student or a teacher, each with a unique ID. They can then use these credentials to log in.

![Screenshot 1](./Screenshot/Screenshot%202025-09-25%20215333.png)

### 2. Teacher: Adding a New Course
Once logged in, a teacher can add a new course to the system, specifying details like course name, ID, credit hours, and capacity.

![Screenshot 2](./Screenshot/Screenshot%202025-09-25%20215744.png)

### 3. Student: Enrolling in a Course
A logged-in student can view all available courses and enroll in the one they choose.

![Screenshot 3](./Screenshot/Screenshot%202025-09-25%20220132.png)

### 4. Teacher: Assigning a Grade
The teacher can then assign a grade to any student enrolled in their course.

![Screenshot 4](./Screenshot/Screenshot%202025-09-25%20220232.png)

### 5. Student: Viewing Marks
The student can log back in and check their marks for the courses they are enrolled in.

![Screenshot 5](./Screenshot/Screenshot%202025-09-25%20220314.png)

### 6. Additional Features
The application also includes features for data persistence and UI customization.

![Screenshot 6](./Screenshot/Screenshot%202025-09-25%20220426.png)