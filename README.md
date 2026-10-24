# CodeFlow-Stack-Queue
C++ programs for Stack and Queue operations.

1. Introduction

This project implements Stack and Queue data structures using C++ classes and arrays. It demonstrates insertion, deletion, displaying elements, and accessing the top or front element.

Git and GitHub are used to store the source code, track changes, and maintain the project.

2. Objectives

- To understand Stack and Queue data structures.
- To implement Stack and Queue using C++ classes.
- To understand the LIFO and FIFO principles.
- To perform insertion, deletion, and display operations.
- To learn Git and GitHub for source code management.
- To maintain project files with proper documentation.

3. Repository Structure

The repository contains the following files:

CodeFlow-Stack-Queue
│
├── stack.cpp
├── queue.cpp
└── README.md

File Description

- stack.cpp: Contains the Stack implementation using a class and an array.
- queue.cpp: Contains the Queue implementation using a class and an array.
- README.md: Contains project details, objectives, features, and instructions.

4. Stack Implementation

Description

A Stack is a linear data structure that follows the LIFO principle (Last In, First Out). The element inserted last is removed first.

The Stack program uses a class named "Stack" and an integer array of size 5.

Operations

- Push: Inserts an element into the Stack.
- Pop: Removes the top element from the Stack.
- Peek: Returns the top element without removing it.
- Full: Checks whether the Stack is full.
- Empty: Checks whether the Stack is empty.
- Display: Displays the Stack elements from top to bottom.

Elements Inserted

The program attempts to insert the following elements:

12, 34, 56, 87, 92, 99

Since the array capacity is 5, only the first five elements are inserted.

Expected Output

Stack elements:
92
87
56
34
12
Removed: 92
Stack after pop:
87
56
34
12
Top element is: 87

Applications

- Undo operations in text editors.
- Function calls and recursion.
- Expression evaluation.
- Reversing data.

5. Queue Implementation

Description

A Queue is a linear data structure that follows the FIFO principle (First In, First Out). The element inserted first is removed first.

The Queue program uses a class named "queue" and an integer array of size 5.

Operations

- Enqueue: Inserts an element at the rear of the Queue.
- Dequeue: Removes an element from the front of the Queue.
- Peek: Returns the front element without removing it.
- Full: Checks whether the Queue is full.
- Empty: Checks whether the Queue is empty.
- Display: Displays the Queue elements from front to rear.

Elements Inserted

The program inserts the following elements:

25, 57, 25, 82, 99

The Queue can store a maximum of five elements.

Expected Output

Queue elements: 25 57 25 82 99
Removed: 25
Queue elements: 57 25 82 99
Front element is: 57

6. Difference Between Stack and Queue

Feature| Stack| Queue
Principle| LIFO| FIFO
Insertion| Push| Enqueue
Deletion| Pop| Dequeue
Access element| Top element| Front element
Display order| Top to bottom| Front to rear
Array size| 5| 5

7. Technologies Used

- Programming Language: C++
- Concepts: Classes, Arrays, and Data Structures
- Version Control: Git
- Code Hosting: GitHub
- Compiler: GCC or another compatible C++ compiler

8. System Requirements

- Windows or Linux operating system.
- A C++ compiler.
- Git installed for version control.
- A GitHub account.
- Visual Studio Code or another C++ editor (optional).

9. How to Compile and Run

Step 1: Download the Repository

Clone the repository using:

git clone YOUR_REPOSITORY_URL

Replace "YOUR_REPOSITORY_URL" with your actual GitHub repository URL.

Step 2: Compile the Stack Program

g++ stack.cpp -o stack

Run on Windows:

stack.exe

Run on Linux:

./stack

Step 3: Compile the Queue Program

g++ queue.cpp -o queue

Run on Windows:

queue.exe

Run on Linux:

./queue

10. Git and GitHub Version Control

Git is used to track changes in the source code, while GitHub hosts the repository online.

Important Git commands include:

Initialize a Repository

git init

Add Files

git add stack.cpp queue.cpp README.md

Commit Changes

git commit -m "Add Stack and Queue implementations"

Push Changes to GitHub

git push

These commands help maintain source code and track project changes.

11. Learning Outcomes

Through this activity, I learned:

- How Stack and Queue work.
- The difference between LIFO and FIFO.
- How to implement data structures using C++ classes and arrays.
- How to perform insertion, deletion, and display operations.
- How to use Git for version control.
- How to maintain and document a project on GitHub.

12. Conclusion

This project demonstrates the implementation of Stack and Queue data structures using C++. The Stack follows the LIFO principle, while the Queue follows the FIFO principle. The activity also provides practical experience in using Git and GitHub to manage source code, maintain version history, and document a software project.

13. Student Details

- Name: Prathamesh Arvind Wakchaure
- Roll no:263
- Div:B
- Subject: DSA
- Branch: Electronics and Communication Engineering (ECE)
  
  
