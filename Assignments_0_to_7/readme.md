📚 Python Assignments 🚀
Welcome to the Python Assignments repository! This collection of assignments is designed to help you master Python from the basics to more intermediate concepts. Whether you're just starting out or looking to reinforce your skills, you'll find practical exercises to strengthen your knowledge.

🧑‍💻 Assignments Overview 📋
This section outlines all the assignments you'll be completing in this course, starting from the fundamentals of Python, progressing to intermediate topics, and enhancing your understanding with hands-on practice.

00 - Introduction & Basic Python Scripts 💡
In this section, you'll be introduced to Python programming. You'll learn basic concepts such as:

Syntax: The structure and rules of Python code.

Variables: How to store and manipulate data.

Running Python Scripts: Executing Python code from a file.

Printing Output: Displaying results in the console.

User Input: Accepting user input via the terminal.

Simple Calculations: Basic arithmetic operations in Python.

This section sets the foundation for all future assignments.

01 - Expressions ➗
Learn how to perform calculations and evaluate conditions in Python:

Mathematical Operations: Addition, subtraction, multiplication, etc.

Logical Conditions: Using comparison operators (e.g., ==, >, <) and logical operators (e.g., and, or).

Variable Manipulation: Changing the values of variables and combining expressions.

Practical exercises will help you write Python expressions and use them in real-world scenarios.

02 - Lists 📚
Python lists are versatile data structures used to store ordered collections of items:

List Creation: Creating lists with different data types.

Indexing & Slicing: Accessing and extracting parts of a list.

Appending & Inserting: Adding new items to a list.

List Operations: Sorting, reversing, and finding list elements.

This section focuses on building an understanding of how to work with lists in Python.

03 - Dictionaries 🔑
Dictionaries are a key feature in Python that store key-value pairs:

Creating Dictionaries: How to initialize dictionaries with various data types.

Accessing Values: Retrieving data using keys.

Adding/Removing Items: Modifying the dictionary by adding or removing elements.

Looping Through Dictionaries: Iterating through keys and values in a dictionary.

A vital section for those looking to manage data in a more structured way.

04 - If Statements 🔄
Conditional logic allows the program to execute different code based on certain conditions:

If-Else Statements: Implementing decision-making logic.

Elif Clause: Using multiple conditions to handle different scenarios.

Logical Expressions: Combining conditions to create complex decisions.

This section provides the foundation for creating responsive Python programs.

05 - Loops & Control Flow 🔁
Loops are essential for repetitive tasks. This section teaches:

For Loops: Iterating over lists, strings, and ranges.

While Loops: Running code as long as a condition is true.

Break & Continue: Controlling the flow within loops.

Nested Loops: Using loops within loops for more complex tasks.

Mastering loops will enable you to create more efficient and powerful Python programs.

06 - Functions 🧑‍🏫
Functions allow for code reusability and modularity:

Defining Functions: How to write your own functions.

Parameters & Arguments: Passing data to functions.

Return Statements: Returning results from functions.

Scope & Lifetime of Variables: Understanding how variables behave inside and outside of functions.

Functions are key for writing clean, readable, and maintainable code.

07 - Information Flow 🔄
Information flow explains how data moves throughout your program:

Variable Scope: Local vs. global variables.

Data Passing Between Functions: Sending and receiving data between functions.

Best Practices: Organizing your code to make it efficient and easy to maintain.

Mastering information flow will ensure your programs are organized and scalable.

🖥️ ANSI Escape Codes for Terminal Formatting 🎨
ANSI escape codes are sequences used to manipulate text formatting, colors, and cursor movements in terminal outputs. These codes are supported by most modern terminals and can enhance the readability and appearance of your console outputs.

Why Use ANSI Escape Codes? 💡
Change Text Color: Highlight important information with different colors.

Text Styling: Make text bold, italic, or underlined.

Reset Formatting: Ensure that text styling doesn't persist unexpectedly.

Basic ANSI Escape Codes 🛠️
Here are some common ANSI escape codes to use for text formatting:

Code	Effect
\033[0m	Reset formatting
\033[1m	Bold text
\033[3m	Italic text
\033[4m	Underline text
\033[31m	Red text
\033[32m	Green text
\033[33m	Yellow text
\033[34m	Blue text
\033[1;33m	Bold Yellow text
\033[1;34m	Bold Blue text

print("\033[1;34mBold Blue Text\033[0m")  # Bold Blue
print("\033[3;31mItalic Red Text\033[0m")  # Italic Red
print("\033[4;32mUnderlined Green Text\033[0m")  # Underlined Green

🔵 Bold Blue Text
🔴 Italic Red Text
🟢 Underlined Green Text

Resetting Formatting 🔄
It is essential to reset the formatting after applying styles using \033[0m. If not reset, the styling will continue for all subsequent text.

print("\033[1mBold Text!")
print("Normal Text")  # This will also be bold!

print("\033[1mBold Text!\033[0m")
print("Normal Text")  # Now it's normal

More Color Codes 🎨
Here are additional colors you can use with ANSI escape codes:

Code	Color
\033[30m	Black
\033[31m	Red
\033[32m	Green
\033[33m	Yellow
\033[34m	Blue
\033[35m	Magenta
\033[36m	Cyan
\033[37m	White

📌 Conclusion 🏁
ANSI escape codes are a powerful tool for making your Python console applications more user-friendly and visually appealing. They are essential for improving output readability and highlighting important information in terminal-based applications.

💡 Tip for Windows Users 💻:
While Windows Command Prompt may not natively support ANSI codes, you can use Windows Terminal or enable ANSI support in PowerShell to take full advantage of these formatting features.

📚 Happy Coding! 🚀
We hope this repository provides you with valuable learning experiences. As you progress through the assignments, you'll build strong Python skills and be ready for more advanced programming challenges!

Feel free to contribute to this project, provide feedback, or reach out for any clarifications.

