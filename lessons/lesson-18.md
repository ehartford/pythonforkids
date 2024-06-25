# Lesson 18: Exception Handling

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the concept of exceptions in Python
2. Use try-except blocks to handle exceptions
3. Work with multiple exception types
4. Use finally and else clauses in exception handling
5. Raise custom exceptions
6. Implement robust error handling in their file processing programs

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples with intentional errors

## Lesson Plan

### 1. Introduction to Exceptions (15 minutes)
- Explain what exceptions are and why they're important
- Show common types of exceptions (e.g., ZeroDivisionError, FileNotFoundError)
- Demonstrate how unhandled exceptions can crash programs
- Use VS Code's debugging features to show exception occurrences

### 2. Basic Exception Handling (25 minutes)
- Introduce try-except blocks
- Show how to catch and handle specific exceptions
- Demonstrate handling multiple exceptions
- Explain the importance of not catching all exceptions blindly
- Use VS Code's IntelliSense to explore built-in exception types

### 3. Advanced Exception Handling (20 minutes)
- Introduce the finally clause and its uses
- Explain the else clause in exception handling
- Show how to access exception information using 'as' keyword
- Demonstrate nested try-except blocks
- Use VS Code's code folding to manage complex try-except structures

### 4. Raising Exceptions (20 minutes)
- Explain when and why to raise exceptions
- Show how to raise built-in exceptions
- Demonstrate creating and raising custom exceptions
- Discuss best practices for exception messages
- Use VS Code's Python Interactive window to experiment with raising exceptions

### 5. Hands-on Practice: Robust File Processor (30 minutes)
- Guide students in enhancing their file processing programs with exception handling:
  1. Open an existing file processing program in VS Code
  2. Implement exception handling for file operations
  3. Add input validation with custom exceptions
  4. Use finally blocks to ensure proper resource cleanup
  5. Implement logging for exceptions
  6. Use VS Code's integrated terminal and debugger to test error scenarios

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Create a robust version of a previous program (e.g., student grade manager) with comprehensive error handling
- Preview next week's topics (Object-Oriented Programming basics)

## Additional Resources
- Visual Studio Code Debugging: https://code.visualstudio.com/docs/editor/debugging
- Python's official documentation on errors and exceptions: https://docs.python.org/3/tutorial/errors.html

## Common Issues and Solutions
- Over-catching exceptions: Emphasize catching specific exceptions
- Silencing exceptions inappropriately: Discuss when to re-raise exceptions
- Confusion about exception hierarchy: Provide a visual representation of the exception class hierarchy

## Extension Activities
For students who finish early or want extra challenges:
- Implement a custom error handling and logging system
- Create a program that uses context managers (with statement) for resource management
- Experiment with the sys.excepthook function for global exception handling

Encourage students to use VS Code's Problems panel to identify and fix potential exceptions in their code. Demonstrate how to use custom task runners in VS Code to automate testing of different error scenarios.
