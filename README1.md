Compiler Design Lab Experiments (Lab 1 – Lab 6) 🧑‍💻
📘 Overview

This repository contains the complete implementation of Compiler Design Laboratory Experiments (Lab 1 to Lab 6) using Python.

Each experiment is organized into a separate folder containing:

Python source code

Individual README file

Sample input and output

Clear explanation of the experiment

The repository is designed to be faculty-friendly, viva-ready, and GitHub-professional for academic submission.

📂 Repository Structure
Compiler_Design_LabExp-Lab1-Lab6/

│
├── Lab-01-Lexical-Analyzer/
│   ├── lexical_analyzer.py
│   └── README.md
│
├── Lab-02-Regex-to-NFA/
│   ├── regex_to_nfa.py
│   └── README.md
│
├── Lab-03-NFA-to-DFA/
│   ├── nfa_to_dfa.py
│   └── README.md
│
├── Lab-04-Left-Recursion-Elimination/
│   ├── left_recursion.py
│   └── README.md
│
├── Lab-05-FIRST-FOLLOW/
│   ├── first_follow.py
│   └── README.md
│
├── Lab-06-Predictive-Parsing-Table/
│   ├── predictive_parsing_table.py
│   └── README.md
│
└── README.md   ← Main README
🧠 Technologies Used

Programming Language: Python

IDE: Visual Studio Code

Version Control: Git

Platform: GitHub

📖 List of Experiments
🔹 Lab 1: Lexical Analyzer

Implementation of a Lexical Analyzer that identifies tokens such as:

Keywords

Identifiers

Operators

Numbers

Special Symbols

from a given source code input.

📁 Folder: Lab-01-Lexical-Analyzer

🔹 Lab 2: Regular Expression to NFA

Conversion of a Regular Expression into an equivalent Non-Deterministic Finite Automaton (NFA) using standard construction techniques.

📁 Folder: Lab-02-Regex-to-NFA

🔹 Lab 3: NFA to DFA Conversion

Conversion of a Non-Deterministic Finite Automaton (NFA) into a Deterministic Finite Automaton (DFA) using the Subset Construction Method.

📁 Folder: Lab-03-NFA-to-DFA

🔹 Lab 4: Elimination of Left Recursion

Implementation of an algorithm to remove left recursion from a given context-free grammar (CFG) so that it becomes suitable for top-down parsing.

📁 Folder: Lab-04-Left-Recursion-Elimination

🔹 Lab 5: FIRST and FOLLOW Sets

Computation of FIRST and FOLLOW sets for all non-terminals in a given grammar.

These sets are essential for:

Syntax analysis

LL(1) parsing

📁 Folder: Lab-05-FIRST-FOLLOW

🔹 Lab 6: Predictive Parsing Table

Construction of an LL(1) Predictive Parsing Table using FIRST and FOLLOW sets.

This table helps implement top-down predictive parsing.

📁 Folder: Lab-06-Predictive-Parsing-Table

▶️ How to Run the Programs

1️⃣ Open the required .py file in VS Code or any Python IDE.

2️⃣ Run the program using the terminal:

python filename.py

Example:

python lexical_analyzer.py

3️⃣ Provide input as specified in the respective lab README file.

📌 Notes

All experiments are implemented according to the standard Compiler Design Laboratory syllabus.

ε (epsilon) is used where required in grammar rules.

Each lab folder contains its own detailed README explaining the algorithm, input, output, and working of the program.

🎓 Author

V. Brijesh Sudharsan

Course: Compiler Design Laboratory

Department: Computer Science and Engineering

Institution: SRM Institute of Science and Technology, Tiruchirappalli
