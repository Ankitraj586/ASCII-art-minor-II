Grayscale to ASCII Art Project
Project Purpose

This project changes a grayscale image (given as numbers) into ASCII art.
ASCII art means making a picture using keyboard characters like @, #, *, and space.

Each number shows how dark or light a pixel is.
The program replaces these numbers with characters to create a picture in text form.

The final output is saved in a text file called decoded_ascii.txt.

How the Code Works
1. Image Data (p_chind)

p_chind is a list of lists (2D list).

Each number is a pixel value.

Smaller numbers mean darker color.

Bigger numbers mean lighter color.

2. Characters for Colors
gray_order = ['@', '#', '%', '*', '+', '=', '-', ':', '.', ' ']


@ is used for very dark pixels.

Space ( ) is used for very light pixels.

Characters in between show medium brightness.

3. Matching Numbers to Characters

The code connects grayscale values (0–255) with characters.

A dictionary is made to store this matching.

This helps to quickly replace numbers with characters.

4. Creating ASCII Lines

The code goes through each row.

Every number is replaced with its matching character.

Characters are joined to make one line.

All lines together make the ASCII picture.

5. Saving the Result

The ASCII picture is saved in a file:

decoded_ascii.txt


Each line is written exactly as it should appear.

How to Run the Program
What You Need

Python 3 installed

No extra libraries needed

Steps to Run

Save the code in a file, for example:

ascii_art.py


Open terminal or command prompt.

Run this command:

python ascii_art.py


You will see this message:

Output saved in decoded_ascii.txt


Open decoded_ascii.txt to see the ASCII art.

Output File

File name: decoded_ascii.txt

Contains: ASCII picture made from numbers

Can open with: Notepad, VS Code, or any text editor

