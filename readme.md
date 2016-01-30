# Shell learnings

## Shell commands
`cd -` : Return to the last directory.

`pwd | pbcopy` : Copy present working directory to clipboard.

`cat filename | pbcopy` : Copy contents of file to clipboard.

`echo "some text" >> filename` : Add a new line to a file. [`sed`](https://en.wikipedia.org/wiki/Sed) can do this as well (see [this Stackoverflow answer](http://stackoverflow.com/a/4640152/4461425)).

`find . -iname '*icon*' -type d -maxdepth 1` : Finds the following:

- in the present working directory
- a name containing the string "icon", ignoring case
- directories only
- at a maximum depth of 1

This could return, for example, these directories:

```
./AppIcons
./icon-repo
```

`ps -e | grep searchstring` : list out all running processes and search the results for a particular sting.

`kill -9 [pid]` : kill a process by process ID.

## Shell scripts
(Steps for creating a shell script, script syntax, variables, arugments, etc.)

## Shells
(`bash`, `zsh`, etc. How to set up, etc.).

