# Compare Shell Builtins
Purpose: Compares shell builtin commands.

This program compares the **names of shell builtin commands** with the builtin commands of Bash. The currently supported shells are: elvish, fish, ksh, tcsh and zsh.

## Usage

```bash
cmp_builtins <shell name>
```

```bash
cmp_builtins --help|-h
```

```bash
cmp_buildins --version
```

### Restrictions

- `<shell name>` has to be a value out of: elvish, fish, ksh, tcsh and zsh. 
- The shell, for which you call `cmp_builtins` should be installed. **Be cautious:** Currently the program does not check, if the shells are installed!




