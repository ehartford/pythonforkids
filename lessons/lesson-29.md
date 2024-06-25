# Lesson 29: Flask Forms

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the basics of web forms and their importance
2. Use Flask-WTF extension to create and handle forms
3. Implement form validation and display error messages
4. Create custom form fields and validators
5. Handle file uploads using Flask-WTF
6. Use VS Code effectively for Flask form development

## Materials Needed
- Computers with Python, Flask, Flask-WTF, and Visual Studio Code installed
- Python and Flask extensions for VS Code
- Flask application from previous lessons
- Projector or screen sharing capability
- Prepared Flask form examples

## Lesson Plan

### 1. Introduction to Web Forms and Flask-WTF (15 minutes)
- Explain the importance of forms in web applications
- Introduce Flask-WTF and its benefits
- Demonstrate installing Flask-WTF using pip in VS Code's integrated terminal
- Show how to configure Flask-WTF in a Flask application

### 2. Creating Forms with Flask-WTF (25 minutes)
- Demonstrate creating a form class using Flask-WTF
- Show how to define different field types (StringField, IntegerField, etc.)
- Explain how to add validators to form fields
- Use VS Code's IntelliSense to explore available field types and validators

### 3. Rendering Forms in Templates (20 minutes)
- Show how to pass a form object to a template
- Demonstrate rendering form fields in HTML
- Explain Cross-Site Request Forgery (CSRF) protection
- Use VS Code's HTML and Jinja2 extensions for efficient form template editing

### 4. Handling Form Submissions (25 minutes)
- Demonstrate how to handle form submissions in Flask routes
- Show how to access form data and perform server-side validation
- Explain how to display validation errors in templates
- Use VS Code's debugger to inspect form data during submission

### 5. Custom Form Fields and Validators (20 minutes)
- Show how to create custom form fields
- Demonstrate implementing custom validators
- Explain when and why to use custom fields and validators
- Use VS Code's refactoring tools to organize custom form code

### 6. Hands-on Practice: Implementing a Complex Form (35 minutes)
Guide students in creating a more advanced form in their Flask application:
1. Create a new form (e.g., a user registration form) with multiple field types
2. Implement custom validation (e.g., password strength checker)
3. Handle form submission and display success/error messages
4. Add file upload functionality to the form
5. Style the form using CSS
6. Use VS Code's integrated terminal to test the form submission

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the application with multiple interconnected forms
- Preview the next lesson's topic (Flask and Databases)

## Additional Resources
- Flask-WTF Documentation: https://flask-wtf.readthedocs.io/
- WTForms Documentation: https://wtforms.readthedocs.io/

## Common Issues and Solutions
- CSRF token missing: Ensure `{{ form.csrf_token }}` is included in all forms
- Validation errors not displaying: Check if errors are being passed to the template
- File upload issues: Verify correct enctype on form and proper handling on the server side

## Extension Activities
- Implement AJAX form submission using JavaScript
- Create a multi-step form wizard
- Experiment with dynamic form field generation based on user input

Encourage students to use VS Code's "Todo Tree" extension to mark areas in their code that need further attention or improvement. Demonstrate how this can help manage complex form implementations.
