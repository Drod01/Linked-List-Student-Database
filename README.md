# Linked List Student Database 

## Description

This program implements a singly linked list data structure to store student records. Each node in the linked list contains a student's ID, GPA, and name.

The linked list provides an efficient way to insert and delete nodes dynamically. New students can be added to the end of the list in O(1) time. Removing students is also fast, with removal from the head of the list being O(1).

## Features

- Create new linked list
- Add students to list  
- Remove students from list
- Check if list is empty
- Get number of students
- Get student at index
- Print all students  
- Calculate GPA stats
- Remove max GPA student
- Free list memory

## Usage

The `main()` function in `driver1.c` contains a menu loop that allows the user to test out the various linked list functions. 

To compile:

gcc driver1.c mylinkedlist.c -o main


To run:

./main


## Example Run

Add Student

Remove Student

Number of Students

Get Student

Print Students

GPA Stats

Remove Max GPA

Quit

Enter choice: 1

Enter student ID: 123

Enter GPA: 3.5

Enter name: John Doe

Student added successfully!

Add Student

Remove Student

Number of Students

Get Student

Print Students

GPA Stats

Remove Max GPA

Quit

Enter choice: 3

Number of students: 1

Add Student

Remove Student

Number of Students

Get Student

Print Students

GPA Stats

Remove Max GPA

Quit

Enter choice: 8

Exiting...


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
