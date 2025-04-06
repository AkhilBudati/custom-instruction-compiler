# Simple Compiler Frontend (Python)

This project implements a basic compiler frontend using Python. It includes key stages of compilation such as lexical analysis, parsing, intermediate representation (IR) generation, and code generation.

---

## Project Structure

```
cd python/
│
├── output.png                # Output screenshot (optional visual result)
└── src/
    ├── input.txt             # Sample input for testing
    ├── main.py               # Entry point of the compiler
    ├── lexer.py              # Lexical analysis (tokenizer)
    ├── parser.py             # Syntax analysis
    ├── ir.py                 # Intermediate representation builder
    ├── codegen.py            # Final code generation stage
    ├── utils.py              # Utility functions
    └── __pycache__/          # Python bytecode cache (can be ignored)
```

---

## How to Run
github link : "https://github.com/AkhilBudati/custom-instruction-compiler"

### 1. Clone or Extract the Project

If zipped, extract the folder.


### 2. Run the Compiler

Make sure you have Python 3 installed.
now open the main file and run to get the output in the terminal

- `input.txt` – contains the input code to compile

> 📝 You can also edit `main.py` to use default filenames if arguments are not passed.

---

##  What It Does
- **Lexical Analysis:** Breaks input into tokens.
- **Syntax Analysis:** Builds a parse tree or validates grammar.
- **IR Generation:** Builds an intermediate representation of code.
- **Code Generation:** Outputs simplified machine-like code or target format.
---

## Notes

- Tested with Python 3.10+
- This is a simple educational compiler frontend and does not include optimization or backend code generation.
