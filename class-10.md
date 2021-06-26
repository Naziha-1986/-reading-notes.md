## “Error Handling & Debugging”
![error](https://th.bing.com/th/id/OIP.w-ojos6RaXOZ7H8RV8wTJQHaFj?pid=ImgDet&rs=1)

**EXECUTION CONTEXT & HOISTING**:

-Each time a script enters a new execution context, there are two phases of activity:
1. **PREPARE**:

• The new scope is created.

• Variables, functions, and arguments are created .

• The value of the this keyword is determined .

2. **EXECUTE**:

• Now it can assign values to variables 
• Reference functions and run their code 
• Execute statements mage.

## UNDERSTANDING ERRORS:



-If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code.

-Error objects can help you find where your mistakes are and browsers have tools to help you read them.

![error](https://i.stack.imgur.com/yniah.png)

## HOW TO DEAL WITH ERRORS:

1. **DEBUG THE SCRIPT TO FIX ERRORS**: 

If you come across an error while writing a script(or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

2. **HANDLE ERRORS GRACEFULLY**:

You can handle errors gracefully using try, catch, throw, and finally statements.

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE :


**FIREFOX**

On a PC, press Ctrl + Shift + K or: 
1. Go to the Firefox menu. 
2. Select Web Developer. 
3. Open the Web Console. 
On a Mac press Alt + Cmd + K. Or: 
1. Go to the Tools menu. 
2. Select Web Developer. 
3. Open the Web Console. 

**SAFARI**

Press Alt + Cmd + C or: 
1. Go to the Develop menu. 
2. Select Show Error Console. 
If the Develop menu is not shown: 
1. Go to the Safari menu. 
2. Select Preferences. 
3. Select Advanced. 
4. Check the box that says "Show Develop menu in menu bar."

**HOW TO LOOK AT ERRORS IN CHROME**

-The console will show you when there is an error in your JavaScript. It also displays the line
where it became a problem for the interpreter. 

## GROUPING MESSAGES :

-If you want to write a set of
related data to the console, you can use the` console. group ()` 
method to group the messages together. You can then expand and contract the results.

**WRITING TABULAR DATA:**

-In browsers that support it, the `console. table ()` method lets you output a table showing: 
• objects 
• arrays that contain other objects or arrays 

**BREAKPOINTS:**
-by using breakpoints, You can pause the execution of a script on any line.
![break](https://th.bing.com/th/id/R329f0462fe353fe5d09efe673fb42f16?rik=U15oaB5QIQ8qiQ&pid=ImgRaw)


**TRY, CATCH, FINALLY**

![try](https://th.bing.com/th/id/R5ac822506d47045046c66d552e81a1d9?rik=xW5AMJzYX6%2fJXQ&pid=ImgRaw)

**THROWING ERRORS**:
-If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them. 
-To create your own error, you use the following line: `throw new Error( '
message '
) ; `