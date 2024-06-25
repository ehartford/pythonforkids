# Lesson 13: Introduction to Dictionaries

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand what dictionaries are and why they're useful
2. Create and initialize dictionaries in Python
3. Access, modify, and delete dictionary elements
4. Use dictionary methods (keys(), values(), items())
5. Create a simple address book program using dictionaries in VS Code

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples

## Lesson Plan

### 1. Review and Introduction (10 minutes)
- Recap the previous lesson on tuples
- Introduce the concept of dictionaries as key-value pairs
- Explain real-world analogies for dictionaries (e.g., actual dictionaries, phone books)

### 2. Creating and Initializing Dictionaries (20 minutes)
- Demonstrate creating dictionaries using curly braces {}
- Show different ways to initialize dictionaries
- Explain the concept of keys and values
- Use VS Code's IntelliSense to explore dictionary syntax

### 3. Accessing and Modifying Dictionary Elements (25 minutes)
- Show how to access values using keys
- Demonstrate adding new key-value pairs
- Explain how to modify existing values
- Show how to delete key-value pairs using del keyword
- Use VS Code's debugging features to inspect dictionary contents

### 4. Dictionary Methods (20 minutes)
- Introduce and demonstrate common dictionary methods:
  - keys(): returns a view of all keys
  - values(): returns a view of all values
  - items(): returns a view of all key-value pairs
- Show how to use these methods in loops
- Use VS Code's Python Interactive window to experiment with these methods

### 5. Hands-on Practice: Simple Address Book (25 minutes)
- Guide students in creating an address book program using dictionaries:
  1. Create a new Python file in VS Code
  2. Implement functions to add new contacts
  3. Create a function to display all contacts
  4. Implement a function to search for a contact by name
  5. Use VS Code's integrated terminal to test the program

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the address book program (e.g., add email addresses, allow editing contacts)
- Preview the next lesson's topic (dictionary operations and nested structures)

## Additional Resources
- Visual Studio Code Python Tutorial: https://code.visualstudio.com/docs/python/python-tutorial
- Python's official documentation on dictionaries: https://docs.python.org/3/tutorial/datastructures.html#dictionaries

## Common Issues and Solutions
- KeyError when accessing non-existent keys: Introduce the get() method as a safe alternative
- Confusion between lists and dictionaries: Clarify when to use each data structure
- Mutable keys: Explain why dictionary keys must be immutable

## Extension Activities
For students who finish early or want extra challenges:
- Implement a feature to save and load the address book from a JSON file using VS Code's JSON viewer
- Create a program that uses dictionaries to represent and manipulate student grades
- Experiment with using tuples as dictionary keys

Encourage students to use VS Code's features like code snippets and multi-cursor editing to work efficiently with dictionaries. Demonstrate how these tools can speed up coding and reduce errors.
