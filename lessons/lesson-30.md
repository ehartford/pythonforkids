# Lesson 30: Flask and Databases (SQLite)

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the basics of databases and their role in web applications
2. Set up SQLite with Flask using Flask-SQLAlchemy
3. Create database models and perform migrations
4. Implement basic CRUD operations using SQLAlchemy
5. Display database data in Flask templates
6. Use VS Code for efficient database development and debugging

## Materials Needed
- Computers with Python, Flask, Flask-SQLAlchemy, and Visual Studio Code installed
- SQLite extension for VS Code
- Flask application from previous lessons
- Projector or screen sharing capability
- Prepared Flask-SQLAlchemy code examples

## Lesson Plan

### 1. Introduction to Databases and SQLite (15 minutes)
- Explain the importance of databases in web applications
- Introduce SQLite and its benefits for small to medium-sized applications
- Demonstrate installing Flask-SQLAlchemy using pip in VS Code's integrated terminal
- Show how to configure Flask-SQLAlchemy in a Flask application

### 2. Creating Database Models (25 minutes)
- Explain the concept of ORM (Object-Relational Mapping)
- Demonstrate creating a simple database model using SQLAlchemy
- Show how to define relationships between models
- Use VS Code's IntelliSense to explore SQLAlchemy's API

### 3. Database Migrations (20 minutes)
- Introduce the concept of database migrations
- Demonstrate using Flask-Migrate for handling migrations
- Show how to create and run migrations
- Use VS Code's integrated terminal to manage migrations

### 4. Implementing CRUD Operations (30 minutes)
- Demonstrate how to:
  - Create new records in the database
  - Read records from the database
  - Update existing records
  - Delete records from the database
- Show how to query the database using SQLAlchemy
- Use VS Code's debugger to inspect database queries

### 5. Displaying Database Data in Templates (20 minutes)
- Show how to pass database query results to templates
- Demonstrate iterating over query results in Jinja2 templates
- Explain pagination and how to implement it
- Use VS Code's HTML and Jinja2 extensions for efficient template editing

### 6. Hands-on Practice: Implementing a Todo List Application (35 minutes)
Guide students in creating a simple Todo List application:
1. Create a Todo model with appropriate fields
2. Implement routes for listing, adding, editing, and deleting todos
3. Create templates to display and interact with todos
4. Add form handling for creating and editing todos
5. Implement basic styling for the application
6. Use VS Code's SQLite extension to directly view and edit the database

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the Todo List app (e.g., add user authentication, categories for todos)
- Preview next week's topics (Introduction to Game Development with Pygame)

## Additional Resources
- Flask-SQLAlchemy Documentation: https://flask-sqlalchemy.palletsprojects.com/
- SQLAlchemy Documentation: https://docs.sqlalchemy.org/

## Common Issues and Solutions
- Database file not found: Ensure correct path to the SQLite database file
- Migration errors: Check for inconsistencies between models and existing database schema
- Performance issues with large datasets: Discuss query optimization and indexing

## Extension Activities
- Implement a more complex data model with multiple related tables
- Add search functionality to the Todo List application
- Experiment with raw SQL queries alongside SQLAlchemy ORM

Encourage students to use VS Code's "SQLite" extension to directly interact with their databases. Demonstrate how this can be useful for debugging and understanding database structure.
