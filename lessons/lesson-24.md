# Lesson 24: Regular Expressions

## Lesson Objectives
By the end of this lesson, students should be able to:
1. Understand the concept and purpose of regular expressions
2. Create and use basic regular expression patterns
3. Utilize special characters and character classes in regex
4. Apply regex for pattern matching and text processing tasks
5. Use Python's re module for regex operations
6. Implement regex in a practical text analysis program

## Materials Needed
- Computers with Python and Visual Studio Code installed
- Projector or screen sharing capability
- Prepared code examples demonstrating regular expressions
- Sample text files for regex practice

## Lesson Plan

### 1. Introduction to Regular Expressions (20 minutes)
- Explain what regular expressions are and their purpose
- Discuss common use cases for regex
- Introduce basic regex syntax (literals, metacharacters)
- Use VS Code's "Regular Expression Preview" extension to visualize regex patterns

### 2. Basic Regex Patterns (25 minutes)
- Demonstrate creating simple patterns (exact matches, character sets)
- Show how to use quantifiers (*, +, ?, {})
- Explain anchors (^ and $) and word boundaries (\b)
- Use VS Code's find and replace feature with regex to demonstrate practical uses

### 3. Special Characters and Character Classes (20 minutes)
- Introduce special characters (\d, \w, \s, etc.)
- Explain character classes and how to create custom classes
- Show how to use negation in character classes
- Use VS Code's multi-cursor editing to efficiently create test strings for regex

### 4. Python's re Module (25 minutes)
- Introduce the re module and its main functions (search, match, findall, sub)
- Demonstrate compiling regex patterns for efficiency
- Show how to use groups in regex
- Explain the difference between greedy and non-greedy matching
- Use VS Code's Python Interactive window to experiment with the re module

### 5. Hands-on Practice: Text Analysis with Regex (30 minutes)
Guide students in creating a text analysis program:
1. Create a new Python file in VS Code
2. Implement functions to:
   - Extract all email addresses from a text
   - Find and count specific word patterns
   - Replace sensitive information (e.g., phone numbers) with asterisks
3. Use regex to validate user input (e.g., password strength)
4. Use VS Code's integrated terminal to test the program with sample texts

### 6. Wrap-up and Homework Introduction (10 minutes)
- Recap the main points of the lesson
- Introduce the homework assignment: Create a more advanced text processing tool using regex (e.g., log file analyzer, simple markup language parser)
- Preview next week's topics (introduction to web development)

## Additional Resources
- Visual Studio Code Regex Tutorial: https://code.visualstudio.com/docs/editor/codebasics#_find-and-replace
- Python's official documentation on the re module: https://docs.python.org/3/library/re.html

## Common Issues and Solutions
- Overly complex regex patterns: Encourage breaking down complex patterns into smaller parts
- Forgetting to escape special characters: Remind about the use of raw strings (r"pattern")
- Performance issues with inefficient regex: Discuss optimization techniques (e.g., using anchors, avoiding excessive backtracking)

## Extension Activities
For students who finish early or want extra challenges:
- Create a program that extracts structured data from unformatted text using regex
- Implement a simple regex-based search engine for local text files
- Experiment with lookahead and lookbehind assertions in regex

Encourage students to use online regex testing tools (e.g., regex101.com) alongside VS Code to visualize and debug their regex patterns. Demonstrate how these tools can help in understanding complex regex behavior.
