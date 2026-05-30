# MINI-SHELL PROJECT IN C
## IMPORTANT NOTES

- This is version 1.0 of the mini-Shell
- Thanks to this project, i've learned how to make my own parser for user input
- Moreover, I've learned new concepts and functions in C that I didn't know about and
I decided to add them to my personal C manual. Examples of concepts and functions I learned while doing
this project are file descriptors, pipe(), fork(), chdir(), getenv(), fflush(), execvp()...
- I improved my logic as a C programmer as well while doing this project

### Things included is this version

- Simple parser
- Some built-in commands
- Execution of simple commands (commands that don't have pipe nor redirections)
- Support for single pipes
- Support for single redirections

### Things NOT included in this version (they will be added in version 2.0 or later)

- Pipelines
- Multiple redirections
- Advanced parser
- Small details like showing the directory you're currently in, for example
- More built-in commands
- Other tipes of special commands (like && or &)

## Why I didn't add pipelines in this version?

Honestly, this version should've included pipelines and multiple redirections, but after trying to make functional
pipelines for several days while frustrating because I was SO confused and didn't know what to do, I decided to let it be
and make this stable version without pipelines and multiple redirections. Also, I'd rather to have something simple that I fully
understand how it works that something more complex and cool that I don't know what the hell is going on.

Currently, I'm working actively to add these two features to my projects, even tho they may seem difficult to make
