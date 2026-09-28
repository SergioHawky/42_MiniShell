*This project has been created as part of the 42 curriculum by seilkiv and shi-wudu.*

# Minishell

## Description

Minishell is a small Unix shell developed in C as part of the 42 curriculum.
It reads and executes commands, handles environment variables, pipes,
redirections, heredocs, signals, and the built-in commands `echo`, `cd`,
`pwd`, `export`, `unset`, `env`, and `exit`.

## Instructions

The project requires a C compiler, GNU Make, GNU Readline, and the standard
Unix development tools.

### Compiling and Running

```sh
make
./minishell
```

### Cleaning Generated Files

To remove generated files:

```sh
make fclean
```

## Resources

- 42 Minishell subject and project documentation.
- https://harm-smits.github.io/42docs/projects/minishell
- https://apoorvasn.medium.com/minishell-building-a-simple-shell-in-c-55a64a401a4f
- `man fork`, `man pipe`, `man dup2`, `man execve`, `man waitpid`, and `man signal`.

## AI Usage

AI was used to help structure and to review the code.
