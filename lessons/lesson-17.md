# Lesson 17: Working with CSV Files

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the structure and purpose of CSV files
2. Read data from CSV files using Python's csv module
3. Write data to CSV files
4. Process and analyze data from CSV files
5. Create a program to manage student grades using CSV files

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples and sample CSV files

## Lesson Plan

### 1. Review and Introduction to CSV (15 minutes)
- Recap the previous lesson on text file handling
- Introduce CSV (Comma-Separated Values) file format
- Explain common uses of CSV files in data processing
- Show how to open and view CSV files in VS Code

### 2. Reading CSV Files (25 minutes)
- Introduce the csv module in Python
- Demonstrate reading CSV files using csv.reader()
- Show how to use csv.DictReader() for named fields
- Explain how to handle different delimiters and quote characters
- Use VS Code's Python Interactive window to explore CSV data

### 3. Writing CSV Files (20 minutes)
- Show how to write data to CSV files using csv.writer()
- Demonstrate using csv.DictWriter() for writing dictionaries
- Explain how to write headers and multiple rows
- Use VS Code's split editor view to compare input and output CSV files

### 4. Processing and Analyzing CSV Data (20 minutes)
- Demonstrate techniques for data cleaning and transformation
- Show how to perform basic data analysis (e.g., calculating averages, finding max/min values)
- Introduce the concept of data visualization (matplotlib can be mentioned, but not necessary to implement)
- Use VS Code's outline view to organize code for different data processing functions

### 5. Hands-on Practice: Student Grade Manager (30 minutes)
- Guide students in creating a program that manages student grades:
  1. Create a new Python file in VS Code
  2. Implement functions to read student data from a CSV file
  3. Create functions to calculate average grades and identify top performers
  4. Implement functionality to add new student records
  5. Write updated data back to the CSV file
  6. Use VS Code's integrated terminal to test the program with sample data

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the student grade manager (e.g., add grade visualization, implement sorting options)
- Preview the next lesson's topic (exception handling)

## Additional Resources
- Visual Studio Code CSV editor: https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv
- Python's official documentation on the csv module: https://docs.python.org/3/library/csv.html

## Common Issues and Solutions
- Handling different CSV formats (delimiters, quote characters): Show how to use csv.Sniffer
- Dealing with missing or inconsistent data: Discuss data cleaning techniques
- Performance issues with large CSV files: Introduce concepts of chunking and streaming

## Extension Activities
For students who finish early or want extra challenges:
- Implement a feature to export data to different formats (e.g., JSON, XML)
- Create a program that merges multiple CSV files based on a common field
- Experiment with the pandas library for more advanced CSV processing (if time allows)

Encourage students to use VS Code's extensions, such as "Excel Viewer" or "Edit csv", to work more efficiently with CSV files. Demonstrate how these extensions can help in quickly viewing and editing CSV data.
