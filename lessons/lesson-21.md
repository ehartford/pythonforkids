# Lesson 21: Inheritance and Polymorphism

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the concept of inheritance in OOP
2. Create child classes that inherit from parent classes
3. Override methods in child classes
4. Understand and implement polymorphism
5. Use the `super()` function to call parent class methods
6. Create a hierarchy of shape classes demonstrating inheritance and polymorphism

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples demonstrating inheritance and polymorphism

## Lesson Plan

### 1. Introduction to Inheritance (20 minutes)
- Explain the concept of inheritance and its benefits
- Show how to create a child class that inherits from a parent class
- Demonstrate inheriting attributes and methods
- Use VS Code's outline view to visualize class hierarchies

### 2. Method Overriding (25 minutes)
- Explain the concept of method overriding
- Show how to override methods in child classes
- Discuss when and why to override methods
- Demonstrate the `super()` function to call parent class methods
- Use VS Code's "Go to Definition" feature to navigate between parent and child class methods

### 3. Polymorphism (20 minutes)
- Introduce the concept of polymorphism
- Explain how polymorphism works with inheritance
- Demonstrate using objects of different classes interchangeably
- Show examples of polymorphism in Python's built-in functions
- Use VS Code's debugging features to step through polymorphic method calls

### 4. Multiple Inheritance (15 minutes)
- Briefly introduce multiple inheritance in Python
- Discuss potential issues with multiple inheritance (diamond problem)
- Show how Python resolves method calls in multiple inheritance
- Use VS Code's IntelliSense to explore method resolution order

### 5. Hands-on Practice: Shape Class Hierarchy (30 minutes)
Guide students in creating a hierarchy of shape classes:
1. Create a new Python file in VS Code
2. Define a base Shape class with methods for calculating area and perimeter
3. Create child classes for specific shapes (e.g., Rectangle, Circle, Triangle)
4. Override area and perimeter methods in each child class
5. Implement a display method to demonstrate polymorphism
6. Use VS Code's integrated terminal to test the shape classes

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Expand the shape hierarchy (e.g., add more shapes, implement a drawing method)
- Preview next week's topics (intermediate Python concepts)

## Additional Resources
- Visual Studio Code Code Navigation: https://code.visualstudio.com/docs/editor/editingevolved
- Python's official documentation on inheritance: https://docs.python.org/3/tutorial/classes.html#inheritance

## Common Issues and Solutions
- Confusion about method resolution order: Explain Python's MRO algorithm
- Overuse of inheritance: Discuss composition as an alternative in some cases
- Forgetting to call `super()` in `__init__`: Emphasize its importance in proper initialization

## Extension Activities
For students who finish early or want extra challenges:
- Implement an abstract base class using the `abc` module
- Create a simple game with different character classes demonstrating inheritance and polymorphism
- Experiment with mixins to add functionality to classes

Encourage students to use VS Code's "Python Docstring Generator" extension to document their class hierarchies. Demonstrate how clear documentation can help in understanding complex inheritance structures.
