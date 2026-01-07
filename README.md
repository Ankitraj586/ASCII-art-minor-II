ASCII Art Generator (Python) 

Project Purpose

This project turns image data (numbers) into ASCII art.
ASCII art means making a picture using characters like @, #, *, and spaces.

Here, the image is already given as numbers in a 2D list.
Each number shows how dark or light a pixel is.
The program changes these numbers into characters and saves the result in a text file.

How the Code Works

The variable p_chind stores the image as rows and columns of numbers.

Smaller numbers mean dark pixels.

Bigger numbers mean light pixels.

A list called gray_order has characters from dark to light:

@ # % * + = - : . (space)


The program:

Matches pixel values with characters

Reads the image row by row

Replaces each number with a character

Joins characters to make lines

Saves all lines into a file called decoded_ascii.txt

If a number does not match exactly, the program uses a space.



