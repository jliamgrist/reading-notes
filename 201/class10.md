# What Went Wrong? Troubleshooting JavaScript.

Syntax errors - spelling errors.
Logical errors - incorrect results/logic. Does not always provide error/warning.

I have come across mistakes where something is undefined and I have to backtrack to where it should be defined and what it's inputs are to the definition or value. Often the inputs to the definition are what cause it to be undefined. 

They say 70% of coding is debugging. I know my brother spends a lot of time also refactoring other peoples code or his own code. I like seeing the big picture and picking out the pieces that make or break that big picture. 

## The Javascript Debugger and Chrome Devtools

Mac shortcut: command option i

"The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly."
[What_are_browser_developer_tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

I want to be great at debugging, I think it is a good way to provide value on a team and is creative work. 

We use breakpoints to set where we want to pause execution of the code. You can then go through the code in steps, to help diagnose where things go wrong. 
We use the call stack to show us what code was executed to get to the current line. 