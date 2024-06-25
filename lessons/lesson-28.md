# Lesson 28: Flask Templates

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the concept of template inheritance in Flask
2. Create and use base templates
3. Implement template blocks and extensions
4. Pass data to templates and use Jinja2 syntax for dynamic content
5. Use filters and macros in Jinja2 templates
6. Debug template issues using VS Code

## Materials Needed
- Computers with Python, Flask, and Visual Studio Code installed
- Jinja2 extension for VS Code
- Flask application from the previous lesson
- Projector or screen sharing capability
- Prepared Flask template examples

## Lesson Plan

### 1. Review and Introduction to Template Inheritance (15 minutes)
- Recap basic template rendering from the previous lesson
- Introduce the concept of template inheritance
- Explain the benefits of using base templates
- Show how to create a base template in VS Code

### 2. Creating and Using Base Templates (25 minutes)
- Demonstrate creating a base template with common elements (header, footer, navigation)
- Show how to use the `{% block %}` tag to define areas for child templates
- Explain how to extend base templates in child templates
- Use VS Code's HTML and Jinja2 extensions for efficient template editing

### 3. Passing Data to Templates (20 minutes)
- Review how to pass data from routes to templates
- Demonstrate using variables in templates with `{{ }}` syntax
- Show how to use conditional statements in templates
- Explain loops in Jinja2 templates
- Use VS Code's IntelliSense to explore Jinja2 syntax

### 4. Jinja2 Filters and Macros (25 minutes)
- Introduce Jinja2 filters for modifying variables in templates
- Demonstrate creating and using custom filters
- Explain the concept of macros in Jinja2
- Show how to create reusable macros for common HTML elements
- Use VS Code's snippets feature to create custom Jinja2 snippets

### 5. Hands-on Practice: Enhancing Flask Application with Advanced Templates (35 minutes)
Guide students in improving their Flask application:
1. Create a base template with common elements
2. Implement child templates for different pages
3. Use template inheritance to maintain consistent layout
4. Create a macro for form inputs and use it across templates
5. Implement a custom filter (e.g., for date formatting)
6. Use VS Code's Live Server extension to preview template changes in real-time

### 6. Debugging Templates (15 minutes)
- Demonstrate common template errors and how to identify them
- Show how to use Flask's debug mode to troubleshoot template issues
- Explain how to use VS Code's debugger with Flask templates
- Introduce the Flask-DebugToolbar extension for advanced debugging

### 7. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Create a more complex template structure for a multi-page application
- Preview the next lesson's topic (Flask forms)

## Additional Resources
- Jinja2 Documentation: https://jinja.palletsprojects.com/
- VS Code Jinja2 Snippets: https://marketplace.visualstudio.com/items?itemName=samuelcolvin.jinjahtml

## Common Issues and Solutions
- Template not found errors: Explain Flask's template loading mechanism
- Confusion between Jinja2 and Python syntax: Clarify the differences and when to use each
- Overuse of logic in templates: Discuss separation of concerns and when to move logic to the backend

## Extension Activities
- Implement a theme switcher using template inheritance
- Create a complex navigation system using macros and template logic
- Experiment with asynchronous template loading using JavaScript and Flask

Encourage students to use VS Code's split editor view to work on routes and templates side by side. Demonstrate how this can improve the workflow when developing Flask applications.
