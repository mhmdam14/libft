# Libft

Libft is my very first project at 42! 🚀  
The goal of this project is to strengthen my C foundations, sharpen my skills with pointers and memory management, and build a reusable library for future 42 projects.

---

## 📚 About

In this project, I recreated a set of functions from the C standard library (like those from `<string.h>` and `<ctype.h>`), along with additional utility functions.  
These functions form a personal C library (`libft.a`) that I can use later on in other 42 projects.

---

## 🛠️ Features

- Re-implemented standard C functions  
- Additional utility functions for strings, memory, and lists  
- A static library `libft.a` ready to be linked to future projects  

---

## ⚡ Usage

Clone the repository and run `make` to compile the library:

```bash
git clone https://github.com/mhmdam14/libft.git
cd libft
make
gcc your_code.c -L. -lft -o your_program
./your_program
