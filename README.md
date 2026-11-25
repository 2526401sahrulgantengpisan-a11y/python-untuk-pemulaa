# Python for Beginners Project

This repository contains a collection of practice code and learning documentation for basic Python programming from the **Python for Beginners** (*Python untuk Pemula*) course by SantriKoding.

## 📂 Project Structure

```text
python-untuk-pemulaa/
├── python-untuk-pemula/
│   ├── hello.py               # Basic program (Hello World & output)
│   ├── variable.py            # Introduction to variables and data types
│   ├── operators.py           # Usage of arithmetic, comparison, and logical operators
│   ├── if_else.py             # Conditional statements (if, elif, else)
│   ├── looping.py             # Loops (for and while loops)
│   ├── list_dictionaries.py   # List and Dictionary data structures (CRUD items)
│   ├── function.py            # Creating and calling functions
│   └── class_object.py        # Object-Oriented Programming (OOP) basics
├── screenshot/                # Documentation of code execution & IDE setup
├── .gitignore                 # List of files/folders ignored by Git
├── README.md                  # Project documentation
└── requirements.txt           # List of Python library dependencies
```

## 📚 Topics Covered

1. **Basics & Syntax (`hello.py`)**: Running the first Python script and printing output to the terminal.
2. **Variables & Operators (`variable.py`, `operators.py`)**: Storing data in variables and performing basic operations.
3. **Control Flow (`if_else.py`, `looping.py`)**: Controlling program execution flow using conditionals and loops.
4. **Data Structures (`list_dictionaries.py`)**: Managing collections of data using *Lists* and *Dictionaries* (adding, updating with `.update()`, removing with `.pop()`, and clearing with `.clear()`).
5. **Functions (`function.py`)**: Modularizing code into reusable function blocks.
6. **Basic OOP (`class_object.py`)**: Creating simple *Classes*, *Objects*, attributes, and *methods*.

## 🚀 How to Run the Project

1. **Clone this repository** (or navigate to the project directory):
   ```bash
   git clone https://github.com/2526401sahrulgantengpisan-a11y/python-untuk-pemulaa.git
   cd python-untuk-pemulaa
   ```

2. **Create and Activate a Virtual Environment** (optional):
   * **Windows (PowerShell):**
     ```powershell
     python -m venv venv
     .\venv\Scripts\Activate.ps1
     ```
   * **Linux/macOS:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Install dependencies** (if any):
   ```bash
   pip install -r requirements.txt
   ```

4. **Run any Python script**:
   ```bash
   python python-untuk-pemula/list_dictionaries.py
   ```