# Minishell

## Overview

Minishell is a simple command-line shell implemented as a project at École 42. It aims to mimic the behavior of a basic Unix shell, allowing users to execute commands, manage environment variables, and handle simple redirections and pipes.

## Features

- Execution of built-in commands (e.g., `cd`, `echo`, `exit`, `env`, `export`, `unset`)
- Execution of external programs by searching the `PATH`
- Support for command chaining with pipes (`|`)
- Input and output redirections (`>`, `>>`, `<`)
- Signal handling (e.g., `Ctrl+C` to interrupt)
- Environment variable management

## Usage

Compile the project and run the executable. You will get a prompt where you can type commands just like in a normal shell.

```bash
make
$ ./minishell
minishell> ls -l | grep txt > output.txt
minishell> cat output.txt
minishell> exit
