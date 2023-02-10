# What Went Wrong? Troubleshooting JavaScript.

1. Name some key differences between a Syntax Error and a Logic Error.
    [MDN - Types of error](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
    Syntax errors are spelling errors that will the code to not run at all - will usually throw an error.
    Logic errors may allow the program to work, but not with the desired results.

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
    - Most of my errors have been syntax errors - mis-spelling object names, etc.
    - One error that really got me was a missing "." in some strings that was throwing an error when going through test. Normally that wouldn't cause an error (I don't think) and it was a bit hard to track down.
    - Finally, there have been a couple times where I referenced the wrong object in some code and made my program not work quite right. A couple times I was able to track down the issue and correct it myself, but I did ask for help from a TA and fellow students a couple times.

3. How will this topic continue to influence your long term goals?
    First and foremost, I will reach out for help if it is something that I am struggling to figure out. But also, I think with this in mind I will try to slow myself down in the future in order to ensure greater accuracy.


# The JavaScript Debugger.

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
    [MDN - Developer tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
    Javascript debugger allows you to inspect each element of the code/page right in the browser.

2. Define what a breakpoint is.
    [MDN - Developer tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
    Breakpoints are places in code that pause execution, allowing you to potentially identify problems.

3. What is the call stack?
    [MDN - Developer tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
    The call stack section shows what code was executed