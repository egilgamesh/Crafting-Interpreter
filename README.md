# Crafting interpreter Summary with examples

![](https://github.com/egilgamesh/Crafting-Interpreter/blob/main/header.png)



Start mountain from left



1- Start with Scanning which means lexical analysis which converts the string to words, each word or lexeme is called token which can me one character like '(' or ',' or numbers '123' or string like "hi" and identifiers min, scanner usually discard the space or the comments.

2- next step is parsing, this is where our syntax gets a grammar, grammar is the ability to compose larger expressions out of smaller parts, parse tasks the flat sequence of tokens, and build a tree structure that represents the nested nature of the grammar this tree called parse tree or AST (Abstract syntax tree), it exactly convert the expression to BFS ... back to the data structure

3- analysis is to bind each identifier (variable) to it is value and its scope like global or local. 

4- Optimization is to evaluate the expression in the compiler if the expression always refers to the same value like area =4*4 => area =16
5- the virtual machine is to translate the bytecode. either by write a little mini compiler to convert to native code for that machine. or you can write VM 

VM is a program that emulates a hypothesis chip supporting your virtual architecture at runtime. but it is slower than translating it to native code. because every instruction must be simulated at runtime each time it executes.
