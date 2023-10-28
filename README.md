# Minishell Implementation in C

## Introduction

This project is a minimal Unix shell implementation in C, commonly known as "minishell." A shell is a command-line interface that allows users to interact with an operating system. This minishell provides basic shell functionalities, allowing users to execute commands, navigate directories, and manage processes.

## Requirements
You must have gcc compiler and readline libraries installed

## Features

- **Command Execution:** Execute various shell commands and programs.
- **Built-in Commands:** Implement built-in shell commands like `cd`, `exit`, and `help`.
- **Input/Output Redirection:** Support input and output redirection using `<`, `<<`, `>>` and `>` operators.
- **Piping:** Enable command piping using the `|` operator.
- **Signal Handling:** Handle signals like Ctrl+C and Ctrl+D  and Ctrl+\.

## How to Use

1. **Compilation:** Compile the minishell program using a C compiler like gcc.
    ```bash
    make
    ```

2. **Execution:** Run the compiled minishell executable.
    ```bash
    ./minishell
    ```

3. **Shell Commands:**
   - **Basic Commands:** Enter standard shell commands like `ls`, `pwd`, etc.
   - **Built-in Commands:**
     - `cd [directory]`: Change current directory.
     - `exit`: Exit the minishell.
     - `help`: Display help information.
   - **Redirection:** Use `<`, `<<`, `>>` and `>` for input and output redirection.
     ```bash
     cat < input.txt > output.txt
     ```
   - **Piping:** Use `|` for command piping.
     ```bash
     command1 | command2
     ```
