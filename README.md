# Course-Management-System-End-Sem-Project.

Purely CLI Based C++ (OOP) Project. 
Can be transformed into a GUI Based Project using SFML or QT. (will learn in the future :p)

The Course Management System allows students to enroll in courses, instructors to manage courses, and administrators to track academic records efficiently. 

System Functionality: 
The system allows the administrator to manage student and instructor information efficiently. - Students
can enroll in multiple courses, and their course lists and grades are tracked. - Instructors can be assigned to
teach courses and view the students enrolled. - Courses manage the list of enrolled students and the
assigned instructor. - Reports can be generated for students and courses to show grades, enrollment, and
instructor information.

Base Class: Person
The base class Person represents common attributes such as name and age for both students and
instructors. It defines common behaviors that derived classes will implement.

Derived Classes: Student and Instructor
Student and Instructor are derived from Person . - Student maintains information about
enrolled courses and grades. - Instructor maintains information about the courses they teach. - Both
classes implement specific behaviors for displaying their details, demonstrating polymorphism.

Class: Course
The Course class represents academic courses. It contains details such as course name and code, and
manages relationships with students and instructors. - Association: Courses are linked with an instructor. -
Composition: Courses manage enrolled students. - Aggregation: Students and instructors maintain lists of
courses.

