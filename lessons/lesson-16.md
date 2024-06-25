# Lesson 16: Reading and Writing Text Files

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the basics of file I/O in Python
2. Open and close files properly
3. Read from text files using different methods
4. Write to text files
5. Use the 'with' statement for file handling
6. Create a program that processes a text file and counts word occurrences

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples and sample text files

## Lesson Plan

### 1. Introduction to File I/O (15 minutes)
- Explain the importance of file handling in programming
- Discuss different types of files (focus on text files for this lesson)
- Introduce the concept of file paths and working directories
- Show how to use VS Code's file explorer to navigate project structures

### 2. Opening and Closing Files (20 minutes)
- Demonstrate how to open files using the open() function
- Explain different file modes (read, write, append)
- Show how to properly close files using the close() method
- Introduce the 'with' statement for automatic file closing
- Use VS Code's IntelliSense to explore file object methods

### 3. Reading from Files (25 minutes)
- Show different methods to read from files:
  - read(): reading entire file content
  - readline(): reading one line at a time
  - readlines(): reading all lines into a list
- Demonstrate iterating over file objects
- Use VS Code's Python Interactive window to experiment with file reading

### 4. Writing to Files (20 minutes)
- Demonstrate writing strings to files
- Show how to write multiple lines
- Explain the difference between write() and writelines()
- Discuss appending vs. overwriting files
- Use VS Code's integrated terminal to verify file contents after writing

### 5. Hands-on Practice: Word Occurrence Counter (30 minutes)
- Guide students in creating a program that:
  1. Reads a text file
  2. Counts the occurrences of each word
  3. Writes the results to a new file
- Steps:
  1. Create a new Python file in VS Code
  2. Implement file reading functionality
  3. Process the text and count word occurrences (use dictionaries)
  4. Write the results to a new file
  5. Use VS Code's split editor view to compare input and output files

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Enhance the word counter program (e.g., ignore common words, handle punctuation)
- Preview the next lesson's topic (working with CSV files)

## Additional Resources
- Visual Studio Code File Management: https://code.visualstudio.com/docs/editor/codebasics#_file-explorer
- Python's official documentation on file objects: https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files

## Common Issues and Solutions
- File not found errors: Ensure correct file paths and working directory
- Encoding issues: Explain the importance of specifying file encoding
- Not closing files: Emphasize the importance of proper file closing or using 'with' statements

## Extension Activities
For students who finish early or want extra challenges:
- Implement a simple log file system for the word counter program
- Create a program that merges multiple text files into one
- Experiment with reading and writing binary files

Encourage students to use VS Code's Source Control features to track changes in their file handling programs. Demonstrate how to use the diff viewer to compare different versions of their code.
