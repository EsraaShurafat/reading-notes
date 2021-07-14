# JS Debugging
![JS Debugging](https://miro.medium.com/max/1024/1*1Myc_L27F1nGuK5duCxjMw.jpeg)

### Code Debugging
- Programming code might contain syntax errors, or logical errors.Many of these errors are difficult to diagnose.Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.Searching for (and fixing) errors in programming code is called code debugging.
- ORDER OF EXECUTION : To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.
- EXECUTION CONTEXTS: The JavaScript interpreter uses the concept of execution contexts. There is  one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 
## ERROR OBJECTS 
#### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

### HOW TO DEAL WITH ERRORS
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY 

- Debugging is the process of finding errors. It involves a process of deduction. 
- The console helps narrow down the area in  which the error is located, so you can try to find the exact error. 
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 