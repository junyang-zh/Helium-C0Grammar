# Helium-C0Grammar
Helium's C0Grammar Analyzer

 Personal C0 parser by James Zhang, as an individual assignment of the course *COMP450305*: "形式语言与编译", XJTU.



## Project description

This project aims to use `yacc` tool to develop a grammatic analyzer for C0 (CMU 15-122).


Some of the language specifications in `C0Grammer.y` are generated by python scripts in `DevUtils`, and there are also  some visualization scripts for the grammar tree.


## How to use

Simply call `make` to make the `TestFile.tree` outcome, which represents the grammar tree of `TestFile.c0`.