# ⚙️ Lexical Analyzer – Compiler Design Mini Assignments

This repository contains a set of Lex programs and scripts developed as part of compiler design coursework. These programs demonstrate the lexical analysis phase of a compiler using tools like **Lex** and **Bash** scripting.

---

## 📌 Contents

### 🧾 Mini Assignments
- **Mini Assignment 1** –  
  ➤ Implemented multiple Lex programs to perform:
  - Word, vowel, and character counting  
  - Recognition of keywords and identifiers  
  - Pattern matching for C-style numbers and variable names  
  - File redirection using command-line arguments  

- **Mini Assignment 2** –  
  ➤ Advanced pattern recognition and symbol table construction.

> All programs are written using **Lex (.l files)** and tested on a Linux environment.

---

## 🗂️ File Structure

```bash
📦 compilers-project/
├── Mini-Asgn-1.tar.gz       # Archive containing all Lex files and scripts
├── lex3.l                   # Word, vowel, and letter counting
├── lex4.l                   # Pattern recognition in C code
├── run.sh                   # Bash script to compile and run Lex programs
└── README.md
```

---

## ⚙️ How to Run

### 🧰 Requirements
- Linux/MacOS environment
- `lex` or `flex` installed
- `gcc` installed

### ▶️ Compilation & Execution

```bash
lex lex3.l
gcc lex.yy.c -o lexprog
./lexprog
```

For redirection using file input:
```bash
./lexprog < input.txt > output.txt
```

Or use `run.sh` for automated execution.

---

## 📚 Learning Outcomes

- Understanding of the lexical analysis phase in a compiler
- Hands-on with Lex for token recognition
- Bash scripting for compiler automation
- Integration of file I/O with lexical analyzers

---

## 👩‍💻 Author

**Meenakshi Kagita**  
B.Tech Mathematics and Computing, IIT Hyderabad  
[GitHub](https://github.com/KagitaMeenakshi) | [LinkedIn](https://www.linkedin.com/in/meenakshi-kagita-a085a5366)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).
