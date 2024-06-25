# Lesson 9: Creating Custom Modules

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the structure and purpose of custom modules
2. Create their own Python modules
3. Import and use functions from custom modules
4. Organize code effectively using modules
5. Create a program that utilizes a custom module

## Materials Needed
- Computers with Python and IDLE installed
- Projector or screen sharing capability
- Prepared code examples

## Lesson Plan

### 1. Review (10 minutes)
- Recap the previous lesson on built-in functions and importing modules
- Address any questions from the homework (math quiz program)
- Quick quiz on using built-in functions and imported modules

### 2. Introduction to Custom Modules (15 minutes)
- Explain why creating custom modules is useful
- Discuss code organization and reusability
- Show how custom modules relate to functions learned in previous lessons

### 3. Creating a Simple Custom Module (25 minutes)
- Demonstrate how to create a new Python file for the module
- Show how to define functions within the module
- Explain the `if __name__ == "__main__":` idiom
- Guide students through creating a simple utility module with basic functions

### 4. Importing and Using Custom Modules (20 minutes)
- Show different ways to import custom modules:
  - `import module`
  - `from module import function`
  - `from module import *`
- Discuss the pros and cons of each import method
- Demonstrate how to use functions from the custom module
- Explain how Python searches for modules (module search path)

### 5. Module Documentation (15 minutes)
- Introduce the concept of docstrings
- Show how to add docstrings to modules and functions
- Demonstrate how to access documentation using `help()`
- Discuss the importance of well-documented code

### 6. Hands-on Practice: Create and Use a Custom Module (15 minutes)
- Guide students in creating a custom module with utility functions:
  1. Create a new Python file for the module
  2. Define at least 3 useful functions (e.g., temperature conversion, basic math operations)
  3. Add appropriate docstrings to the module and functions
  4. Create a main program that imports and uses the custom module

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Expand the custom module and create a program that makes extensive use of it
- Preview next week's topics (lists and tuples)

## Additional Resources
- "Python for Kids" by Jason R. Briggs, Chapter 7 - Recycling Your Code with Functions and Modules (review and expand)
- Python's official documentation on modules: https://docs.python.org/3/tutorial/modules.html

## Common Issues and Solutions
- Module not found errors: Ensure students understand the importance of file location and the module search path
- Circular import issues: Explain how to avoid circular dependencies between modules
- Confusion about `__name__ == "__main__"`: Clarify the purpose and usage of this idiom

## Extension Activities
For students who finish early or want extra challenges:
- Create a module with functions for working with strings (e.g., palindrome checker, word counter)
- Implement a simple game engine as a module and create a game using it
- Develop a module for data analysis functions and use it to analyze a dataset

Encourage students to think about how they can use modules to organize larger projects. Discuss best practices for module design and emphasize the importance of creating reusable, well-documented code.
