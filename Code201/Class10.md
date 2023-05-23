# Foundations of Software Development: Class 10

* Class notes for Code 201 with code fellows

## Class 10

### *Reading 10: JS Debugging*

#### [What Went Wrong? Troubleshooting JavaScript.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

A key difference between a syntax error and a logic error is that a syntax error is just cause by wrong spelling that can trigger a error as well, but with a logic error the syntax is correct - running successfully despite providing with incorrect answers than intended. Logic errors are also harder to fix than syntax errors because it likely wont trigger an error message that indicates where the bug is, since the syntax is likely correct.

I have experienced syntax errors logic errors before and found different ways to solve them. Most recently I decided to change the names for variables throughout my code to try to make it easier to understand what is being stored in the variable at first glance, but when changing it throughout my whole code I noticed in some places I did forget to change it. This triggered errors that let me find where I forgot changes. I decided to look up so hotkeys to make changes like this easier, and find the Ctrl + Shift + L hotkey combination that allows you to select all instances of a word highlighted in VS code.
I am currently dealing with a logic error in code that I am working on for salmon cookies, where everything is correct, except the output is very different than what is expected. I am still working ont the fix but will update as soon as possible.

This topic will continue to influence my long term goals because errors will come up no matter what I am doing, because really no one is perfect. Being able to find these bugs and make changes on your own is really important, because sometimes there wont anyone else there to help so you'll have to learn ways to do it efficiently and effectively.

#### [The JavaScript Debugger.](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

I would describe the JavaScript Debugger tool to someone almost as kind of a spellcheck for code, or even as one of those grammar corrector websites for essays. It's a useful tool for isolating parts of code to see what is wrong.

A breakpoint is a place in your code that you want to pause execution and identify problems that prevent code from executing properly.

The call stack shows you what code was executed to get to the current line, so basically the code that was run without breakpoints.