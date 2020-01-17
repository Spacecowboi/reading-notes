# Errors and Debugging
 - To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:
 - The JavaScript interpreter uses the concept of *execution contexts*. There is one global execution context; plus, each function creates a new execution context. These correspond to **Variable Scope**
 - The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks (or piles) the new function on top of the current task.
 
 ## Hoisting
  - Each time a script enters a new execution context, there are two phases of activity:
    1. Prepare
        - The new scope is prepared
        - Variables, functions, and arguments are created.
        - the value of this keyword is determined
    2. Execute
        - Now it can assign values to variables
        - Reference functions and run their code
        - Execute statements
 ## Errors
- If a JS statement generates an error, then it throws an *exception*. At that point, the interpreter stops and looks for exception-handling code.
- Error objects can help you find where your mistakes are and browsers have tools to help you read them.
    - There are two primary ways to deal with errors
        1. Debug the script
        2. Handle errors gracefully using try, catch, throw and finally statements.
     - Debugging is about deduction: eliminating potential causes of error.
     - Try asking the following questions: 
        1. Where is the problem?
        2. What exactly is the problem?
    
     - You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.
     - If you set multiple breakpoints, you can "step" through them one by one to see where values change and a problem might occur.
     - You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables. 

    