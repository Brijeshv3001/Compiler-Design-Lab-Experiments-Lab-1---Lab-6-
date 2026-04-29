Compiler Design Lab Experiments (Lab 1 – Lab 15) 🧑‍💻
📘 Overview

This repository contains the complete implementation of Compiler Design Laboratory Experiments (Lab 1 to Lab 15) using C++.

Each experiment is organized into a separate C++ file containing:
- C++ source code
- Documentation (Algorithm, Input/Output, Explanation) embedded in the file headers.

The repository is designed to be faculty-friendly, viva-ready, and GitHub-professional for academic submission.

📂 Repository Structure
Compiler_Design_LabExp/

├── lexical_analyzer.cpp
├── regex_to_nfa.cpp
├── nfa_to_dfa.cpp
├── left_recursion.cpp
├── first_follow.cpp
├── parsing_table.cpp
├── leading_trailing.cpp
├── shift_reduce.cpp
├── lr0_items.cpp
├── icg_postfix_prefix.cpp
├── icg_quad_triple.cpp
├── simple_code_generator.cpp
├── dag_implementation.cpp
├── data_flow_analysis.cpp
├── storage_allocation.cpp
└── README1.md   ← Main README

🧠 Technologies Used
Programming Language: C++
Compiler: GCC / G++
IDE: Visual Studio Code
Version Control: Git
Platform: GitHub

📖 List of Experiments

🔹 Lab 1: Lexical Analyzer
Implementation of a Lexical Analyzer that identifies tokens (Keywords, Identifiers, Operators, Numbers, Special Symbols).

🔹 Lab 2: Regular Expression to NFA
Conversion of a Regular Expression into an equivalent Non-Deterministic Finite Automaton (NFA).

🔹 Lab 3: NFA to DFA Conversion
Conversion of an NFA into a Deterministic Finite Automaton (DFA) using the Subset Construction Method.

🔹 Lab 4: Elimination of Left Recursion
Implementation of an algorithm to remove left recursion from a given Context-Free Grammar (CFG).

🔹 Lab 5: FIRST and FOLLOW Sets
Computation of FIRST and FOLLOW sets for all non-terminals in a given grammar.

🔹 Lab 6: Predictive Parsing Table
Construction of an LL(1) Predictive Parsing Table using FIRST and FOLLOW sets.

🔹 Lab 7: Computation of LEADING and TRAILING Sets
Computation of LEADING and TRAILING sets for operator precedence parsing.

🔹 Lab 8: Shift-Reduce Parser
Implementation of a bottom-up Shift-Reduce Parser using parsing tables.

🔹 Lab 9: Computation of LR(0) Items
Construction of LR(0) items and the canonical collection of LR(0) states.

🔹 Lab 10: Intermediate Code Generation (Postfix/Prefix)
Conversion of infix arithmetic expressions to Postfix and Prefix intermediate forms.

🔹 Lab 11: ICG (Quadruple, Triple, Indirect Triple)
Representation of intermediate code as Quadruples, Triples, and Indirect Triples.

🔹 Lab 12: Simple Code Generator
Generation of pseudo assembly code from intermediate Three Address Code (TAC).

🔹 Lab 13: DAG Implementation
Implementation of a Directed Acyclic Graph (DAG) for common subexpression elimination.

🔹 Lab 14: Global Data Flow Analysis
Implementation of data flow analysis using reaching definitions.

🔹 Lab 15: Storage Allocation Strategies
Demonstration of stack-based memory allocation and activation records.

▶️ How to Run the Programs
1️⃣ Open the required .cpp file in VS Code or any C++ IDE.
2️⃣ Compile the program using:
`g++ filename.cpp -o output`
3️⃣ Run the program:
`./output`

📌 Notes
All experiments are implemented according to the standard Compiler Design Laboratory syllabus.
Detailed algorithms, inputs, and outputs are documented within each .cpp file.

🎓 Author
V. Brijesh Sudharsan
Course: Compiler Design Laboratory
Department: Computer Science and Engineering
Institution: SRM Institute of Science and Technology, Tiruchirappalli
