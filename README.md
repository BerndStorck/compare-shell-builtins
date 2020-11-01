# compare-shell-builtins
Purpose: Compares shell builtin commands.

In the initial version of this program only compares the names of shell builtin commands with the builtin commands of Bash. The initially supported shells are: elvish, fish, ksh, tcsh and zsh.

## Usage

### Call format
cmp_builtins <shell name>

`<shell name>` has to be a value out of: elvish, fish, ksh, tcsh and zsh. Additionally the shell, for which you call cmp_builtins shall be be installed. **Be cautious:** Currently the program does not check, if the shells are installed!
  
  
  

