This Hospital Management System with C++ simulates the management of patients across different departments in a hospital setting. This system can be used as a starting point for anyone aiming to develop a more comprehensive hospital management system or looking for a hands-on approach to understanding data structures and algorithms, particularly the use of linked lists.

Objectives
1. Creating Departments: To establish four departments in the hospital—General Clinic, Heart Clinic, Lung Clinic, and Plastic Surgery. Each department maintains a queue (linked list) of patients waiting for treatment.

2. Patient Management: To add patients to any department. There are two categories of patients – normal and critically ill. A critically ill patient is always added to the beginning of the queue (prioritizing their treatment), while a normal patient is added to the end of the queue.

3. Searching Patients: To provide the ability to search for a patient within a department using their unique ID.

4. Service Management: When a patient is taken to the doctor, they are removed from the queue. The system follows a first-in, first-out (FIFO) approach, meaning that the patient who arrived first (is at the front of the queue) gets treated first.

5. Displaying Patient List: To display the list of all patients in a particular department, showing details such as ID, name, age, blood group, and gender.

6. Repetitive Actions: The system keeps running until explicitly stopped by the user, allowing for continuous addition, removal, search, and listing of patients in different departments.

Knowledge Prerequisites:

Basic C++ Knowledge: You need to understand the basics of C++, including variables, data types, operators, loops, and conditionals. This program uses all of these concepts.
Advanced C++ Knowledge: The code also uses more advanced concepts like structures (struct), classes, pointers, and dynamic memory allocation (new and delete). It’s crucial to understand how these work in C++.
File Input/Output: The code assumes that data is being read from or written to files. Understanding how C++ handles file I/O is important.
String Manipulation: Familiarity with string manipulation in C++ is essential, particularly with functions like getline, strcmp, and strcpy.
Knowledge of Linked Lists: The program uses a singly linked list to manage patient data. Linked lists are a fundamental data structure in computer science, so knowing how they work is crucial.
Software Prerequisites:

C++ Compiler: You need a compiler to build and run C++ code. The GNU Compiler Collection (GCC) is a commonly-used free compiler that can handle C++ code.
Integrated Development Environment (IDE): While not strictly necessary, an IDE makes writing, building, and debugging C++ code easier. Some popular C++ IDEs include Code::Blocks, Eclipse CDT, and Visual Studio.
