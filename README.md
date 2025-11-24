Project title: Digit Picker from Number Sequence

Overview of the project
This project is a small Python script that first prints numbers from 1 to a user-given value 
n
n, then joins these numbers into a single long string, and finally lets the user select a specific digit by its position. It is aimed at beginners to practice loops, lists, string building, and index-based access in Python.​

Features
Takes an integer input 
n
n and prints numbers from 1 to 
n
n without spaces in between.​

Stores each printed number in a list and then concatenates them into one continuous string of digits.​

Asks the user for a position 
y
y and returns the digit at that 1-based position from the concatenated string.​

Technologies/tools used
Python 3 as the programming language.​

Basic Python standard input/output using input() and print().​

Core data types and features: integers, lists, strings, for loops, and indexing.​

Steps to install & run the project
Install Python 3 from the official Python website and ensure it is added to your system path.​

Save the provided code in a file named main.py (or any .py filename you prefer).​

Open a terminal or command prompt in the folder containing the file and run python main.py (or python3 main.py depending on your system).​

Instructions for testing
When prompted with enter:, type a positive integer such as 10 and press Enter; you should see numbers from 1 to 10 printed in one line like 12345678910.​

After that, when asked choose digit:, enter a valid position within the range of the total digits shown (for example 5) and check that the digit printed matches the 5th digit of the concatenated sequence.​

Try different values of n and different positions y, including the first and last possible positions, to verify that the script consistently returns the correct digit and handles typical user inputs.
