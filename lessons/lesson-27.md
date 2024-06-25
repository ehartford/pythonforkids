# Lesson 27: Introduction to Flask

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the basics of web frameworks and Flask's role
2. Set up a Flask development environment in VS Code
3. Create a simple Flask application with routes
4. Render HTML templates using Flask
5. Handle basic form submissions
6. Run and debug Flask applications using VS Code

## Materials Needed
- Computers with Python, Flask, and Visual Studio Code installed
- Python extension for VS Code
- Projector or screen sharing capability
- Prepared Flask code examples

## Lesson Plan

### 1. Introduction to Web Frameworks and Flask (15 minutes)
- Explain what web frameworks are and their purpose
- Introduce Flask and its philosophy
- Compare Flask to other frameworks (briefly mention Django)
- Demonstrate installing Flask using pip in VS Code's integrated terminal

### 2. Setting Up a Flask Project (20 minutes)
- Show how to create a new Flask project structure
- Explain the purpose of virtual environments
- Demonstrate setting up a virtual environment in VS Code
- Create a basic Flask application file
- Use VS Code's Python extension to select the correct interpreter

### 3. Creating Routes in Flask (25 minutes)
- Explain the concept of routes in web applications
- Show how to define routes using Flask decorators
- Demonstrate creating multiple routes
- Introduce URL parameters and how to handle them
- Use VS Code's IntelliSense to explore Flask's API

### 4. Rendering Templates (30 minutes)
- Introduce the Jinja2 templating engine
- Show how to create HTML templates
- Demonstrate rendering templates from Flask routes
- Explain how to pass data to templates
- Use VS Code's HTML and Jinja extensions for better template editing

### 5. Handling Form Submissions (20 minutes)
- Create a simple HTML form in a template
- Show how to handle form submissions in Flask
- Demonstrate accessing form data in the backend
- Explain the difference between GET and POST requests
- Use VS Code's debugger to inspect form data during submission

### 6. Hands-on Practice: Creating a Basic Flask App (30 minutes)
Guide students in creating a simple Flask application:
1. Set up a new Flask project in VS Code
2. Create routes for home and about pages
3. Implement a template for the layout and individual pages
4. Add a simple form (e.g., a contact form) and handle its submission
5. Use VS Code's integrated terminal to run the Flask application
6. Debug the application using VS Code's debugging features

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the Flask app (e.g., add more pages, implement a simple database using SQLite)
- Preview next week's topics (advanced Flask concepts)

## Additional Resources
- Flask Documentation: https://flask.palletsprojects.com/
- VS Code Flask Debugging: https://code.visualstudio.com/docs/python/tutorial-flask

## Common Issues and Solutions
- Environment setup issues: Provide a troubleshooting guide for common setup problems
- Template not found errors: Explain Flask's template loading mechanism
- Debug mode security warnings: Discuss the importance of turning off debug mode in production

## Extension Activities
For students who finish early or want extra challenges:
- Implement user sessions in Flask
- Create a RESTful API endpoint
- Integrate a CSS framework like Bootstrap with Flask templates

Encourage students to use VS Code's "Flask Snippets" extension to speed up Flask development. Demonstrate how these snippets can help in quickly creating routes, forms, and other Flask-specific code.
