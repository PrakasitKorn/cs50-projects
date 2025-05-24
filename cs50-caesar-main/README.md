# Caesar Cipher – CS50 Problem Set 2

This project is part of Harvard's CS50 Introduction to Computer Science course (Pset2).  
It implements the **Caesar cipher**, a simple encryption technique that shifts each letter of the plaintext by a given key.

## 📌 Description

The Caesar cipher is a substitution cipher where each letter in the plaintext is shifted a fixed number of places down the alphabet.  
For example, with a key of 2, `A` becomes `C`, `B` becomes `D`, etc.

This program takes a single command-line argument (the key), prompts the user for plaintext, and prints the encrypted ciphertext.

## 💻 How to Run

1. **Compile the program:**
   ```markdown
   clang -o caesar caesar.c -lcs50
2. **Run with a numeric key:**
   ```markdown
   ./caesar 2
4. **Enter plaintext when prompted:**
   ```less
   Plaintext: HELLO
   Ciphertext: JGNNQ
   
## 🔐 Example Output
  ```shell
$ ./caesar 5
Plaintext: Hello, CS50!
Ciphertext: Mjqqt, HX50!

```

## 🧠 Concepts Practiced

- Command-line arguments
- String manipulation
- ASCII arithmetic
- Modular arithmetic (`% 26`)
- Working with loops and conditionals in C

## 📁 Files

- `caesar.c` — main source code implementing the Caesar cipher logic

---

This project was completed as part of CS50 to deepen understanding of cryptography, ASCII values, and string processing in C.
