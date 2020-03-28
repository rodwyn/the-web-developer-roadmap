# The web developer roadmap.
This is a list of skills to get a job as a developer.

## 1. Required Learning for Any Path
## Command Line
The command line is how you run your code. You must be able to navigate and execute the required commands. The better you are on the command line, the more efficient you will be as a developer.
### Prompt
Every command line starts with some symbol or symbols designed to “prompt” you to action. The prompt usually ends with a dollar sign $, and is preceded by information that depends on the details of your system.

![](images/command-line.png)

### Basic commands

| Command | Description | Syntax | Example |
| ------- | ----------- | ------ | ------- |
| echo | Print string to screen | echo <string> | $ echo hello |
| man  | Display manual page for command | man <command> | $ man echo |
| pwd | Display the path of the current directory user are in |
| alias | Lets you give your own name to a command or sequence of commands | alias_name=“command” | alias cls=clear |
| unalias | Remove system alias |
  
### Wildcards

| Wildcard | Description | Example |
| -------- | ----------- | ------- |
| &ast; | Matches one or more occurrences of any character, including no character | cp &ast; directory <br> cp abc*xyz directory <br> cp &ast;xyz directory <br> cp abc&ast; directory  |
| ? | Represents or matches a single occurrence of any character | cp a?b directory <br> cp ?b directory <br> cp a? directory |
| [ ] | Matches any occurrence of character enclosed in the square brackets. <br> It is possible to use different types of characters:<br> numbers, letters, other special characters etc. | cp [range-of-characters]* directory <br> cp [!range-of-characters]* directory <br> cp [range-of-numbers]* directory <br> cp [[:upper:]]* directory <br> cp [[:lower:]]* directory <br> cp [[:digit:]]* directory <br> cp [[:alpha:]]* directory <br> cp [[:alnum]]* directory |
  
### Shortcuts

| Shortcut | Description |
| -------- | ----------- |
| ⌃C | Get out of trouble |
| ⌃A | Move to beginning of line |
| ⌃E | Move to end of line |
| ⌃U | Delete to beginning of line |
| Option-click | Move cursor to location clicked |
| Up & down arrow | Scroll through previous commands |
| ⌃L | Clear screen |
| ⌃D | Exit terminal |

## Git and Version Control
Git is the tool used to save code and create different versions, allowing you to collaborate with other developers. The top place to store code and collaborate on open source software is GitHub.

### Why source control?
- Backup / Archive
- Versioning / History
- Undo Changes
- Comparing
- Collaboration / Teamwork
- Blame / Learning moment
- Isolation of changes 
- Experimentation
- Context Switching 
- Code review 
