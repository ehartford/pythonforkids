# Lesson 20: Methods and Self

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the role of `self` in Python methods
2. Differentiate between instance methods, class methods, and static methods
3. Use the `__init__` method effectively
4. Work with class variables vs instance variables
5. Extend the "Pet" class with more advanced methods and variables

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples demonstrating different types of methods

## Lesson Plan

### 1. Review and Deep Dive into `self` (20 minutes)
- Recap the basics of class definition and object creation
- Explain the purpose of `self` in detail
- Demonstrate how Python passes `self` automatically
- Use VS Code's debugger to show how `self` refers to the instance

### 2. Instance Methods in Detail (25 minutes)
- Explain what instance methods are
- Show how to define and use instance methods
- Demonstrate accessing and modifying instance variables within methods
- Use VS Code's refactoring tools to convert functions to methods

### 3. Class Variables and Class Methods (20 minutes)
- Introduce the concept of class variables
- Show how to define and use class methods with the `@classmethod` decorator
- Explain the difference between class and instance variables
- Demonstrate using `cls` parameter in class methods
- Use VS Code's multi-cursor editing to efficiently work with class variables

### 4. Static Methods (15 minutes)
- Explain the purpose of static methods
- Show how to define static methods using the `@staticmethod` decorator
- Discuss when to use static methods vs instance or class methods
- Use VS Code's Python Interactive window to experiment with different method types

### 5. Advanced `__init__` and Other Special Methods (20 minutes)
- Dive deeper into the `__init__` method
- Introduce other special methods like `__str__` and `__repr__`
- Demonstrate how these methods are used by Python internally
- Use VS Code's IntelliSense to explore special method names

### 6. Hands-on Practice: Enhancing the Pet Class (30 minutes)
Guide students in expanding the Pet class:
1. Open the Pet class file in VS Code
2. Add class variables to track the total number of pets
3. Implement a class method to report the total pet count
4. Create a static method for validating pet names
5. Override the `__str__` method to provide a nice string representation of a pet
6. Use VS Code's integrated terminal to test the enhanced Pet class

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Create a new class (e.g., a Vehicle class) implementing various types of methods
- Preview the next lesson's topic (inheritance and polymorphism)

## Additional Resources
- Visual Studio Code Python Environments: https://code.visualstudio.com/docs/python/environments
- Python's official documentation on method objects: https://docs.python.org/3/c-api/method.html

## Common Issues and Solutions
- Confusion between instance and class methods: Provide clear examples of when to use each
- Forgetting to use `self` or `cls`: Emphasize their importance in different method types
- Misunderstanding when to use static methods: Discuss appropriate use cases

## Extension Activities
For students who finish early or want extra challenges:
- Implement a class that uses all three types of methods in a meaningful way
- Create a class with method chaining (methods that return self)
- Experiment with property decorators to create getter and setter methods

Encourage students to use VS Code's "Python Test Explorer" extension to write and run unit tests for their classes. Demonstrate how testing can help ensure methods are working correctly.
