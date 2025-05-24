# CS50 Mario – Pyramid Printing in C

This project is part of Harvard's [CS50x](https://cs50.harvard.edu/x) course, specifically **Problem Set 1 (Pset1)**.  
It is a simple C program that prints a pyramid of blocks (`#`), inspired by the **Mario** game series.

The user is prompted to enter the height of the pyramid (1 to 8), and the program prints a left-aligned or right-aligned pyramid accordingly.

## 🧱 Features

- Takes user input for height (1–8)
- Prints pyramid using `#` characters
- Validates input using loops
- Includes two versions:
  - `mario_less.c` → Left-aligned pyramid
  - `mario_more.c` → Right-aligned pyramid

## 🚀 How to Run

1. Compile the code:
   ```bash
   clang -o mario mario.c
2. Run the program:
   ```bash
   ./mario
3. Enter a height between 1 and 8.
   
## 📸 Sample Output

```shell
Height: 4
   #  #
  ##  ##
 ###  ###
####  ####

