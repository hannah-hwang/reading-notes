# Read: Class 10 Debugging

## Troubleshooting JavaScript

1. Some key differences between a *Syntax Error* and a *Logic Error* are that syntax errors refer to typing errors (such as spelling mistakes or a misplaced parenthses) that cause the program to not run, while logic errors refers to when the program runs but gives incorrect results due to unintended code being written out (or being written in the wrong place).
2. A logic error I made while working on Salmon Cookies was when I invoked the functions for the sales table in the wrong order, which caused the totals row to not run as 'not a number'. This took a while to figure out because I thought that there was something wrong with the function itself, but I was finally able to get it to work by simply invoking the functions in the order of where the data needed to be on the table.
3. Practicing and learning more about this topic will help me to become better at recognizing types of errors, and solutions to those errors, that may come up.

## The JavaScript Debugger

 1. The JavaScript Debugger tool is located in Developer tools. It allows you to watch the value of variables and set breakpoints.
 2. A *breakpoint* is a place in the code that you want to pause execution in order to identify problems that are preventing your code from running properly.
 3. The *call stack* is a section in the Debugger tool that shows what code was executed, or what function is being called to get the current line.  It helps to keep track of a JS file that calls multiple functions.
