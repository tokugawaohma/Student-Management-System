Instructions on how to compile and run the application.
If you do not have Java installed on your device, you will not be able to
Compile the program.
If you want to use the application properly, install Java Compiler with version at least
20.0.1+9-29 at least, and configure Sqlite to open the database correctly.
1 Download and extract the .RAR file with the project. The directory contains single files with
all classes and the database file. In order to properly run the program compile
it through a downloaded Java Compiler such as IntelliJ. After compilation, the application will be launched.
Functionality offered by the student management system:
- Adding a student to the database based on ID, first name, age and grade using the
Add Student button
- Removing a student using the Remove Student button
- Updating the student's data using the Update Student button
- Displaying the full list of students using Display All Students
- Calculate the average of students' grades using Calculate Average
The application supports exceptions and notifies the user of errors when entering data
data.

Technologies used in application development
- Programming Language:
- Java - The language used to create the application, based on the object-oriented paradigm,
providing portability and scalability of the application.
- IDE Environment:
- IntelliJ IDEA - An integrated development environment (IDE) that made it easy to
writing, debugging and testing code. IntelliJ offers convenient tools for
working with a Java project, as well as support for Maven and the SQLite database.
- SQLite - A lightweight, built-in database that stores data locally in a file.
It's ideal for small applications that don't require an extensive database server
database.

- JDBC - Used to connect an application to a SQLite database, allowing you to
performing CRUD (Create, Read, Update, Delete) operations.
- Swing - A library for creating graphical user interfaces in Java. With
Swing you have created a simple but functional application user interface,
enabling easy management of student data.
- Maven - A tool for managing dependencies and building applications.
Maven allows you to automatically download libraries and manage versions, which
facilitates integration with the database and other libraries. The project is
configured to support SQLite via dependencies in the pom.xml file.
- Java Swing Layout Managers (GridLayout, BorderLayout, etc.) - Used to
organize components in the GUI, which allowed for easy and flexible
placement of buttons, text boxes and output areas.
- PreparedStatement (JDBC) - Used to protect applications from attacks such as.
SQL Injection, providing secure execution of database queries.

Translated with DeepL.com (free version)
