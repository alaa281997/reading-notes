# Read class 10

# Debugging
>JavaScript can be hard to learn and everyone makes 
mistakes when writing it. This chapter will help you learn 
how to find the errors in your code. It will also teach you how 
to write scripts that deal with potential errors gracefully.

>ORDER OF EXECUTION 
To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run.

>  EXECUTION CONTEXTS 
The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new 
new execution context. They correspond to variable scope. 

>EXECUTION CONTEXT & HOISTING
- PREPARE 
 - The new scope is created 
 - Variables, functions, and arguments are created 
 - The value of the this keyword is determined 
- EXECUTE 
 - Now it can assign values to variables 
 - Reference functions and run their code 
 - Execute statements
  
>UNDERSTANDING SCOPE 
In the interpreter, each execution context has its own va ri ables object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's v a ri ables object.

>UNDERSTANDING ERRORS 
If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. 
f you are anticipating that something in your code  may cause an error, you can use a set of statements 
to handle the error (you meet them on p480). This is important because if the error is not handled, 
the script will just stop processing and the user will not know why. So exception-handling code should 
inform users when there is a problem.

>HOW TO DEAL WITH ERRORS 
-  DEBUG THE SCRIPT TO FIX ERRORS 
  > If you come across an error while writing a script (or when someone reports a bug), you will need to 
debug the code, track down the source of the error,  and fix it. 
You will find that the developer tools available in  every major modern browser will help you with 
this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in 
Chrome are identical to those in Opera.) IE and Safari also have their own tools (but there is 
not space to cover them all). 
- HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements. 
Sometimes, an error may occur in the script for a reason beyond your control. For example, you might 
request data from a third party, and their server may not respond. In such cases, it is particularly 
important to write error-handling code. In the latter part of the chapter, you will learn how to 
gracefully check whether something will work, and offer an alternative option if it fails. 

> BREAKPOINTS 
You can pause the execution of a script on any line using breakpoints. Then you can check the 
values stored in variables at that point in time. 

>CONSOLE
The console will show you when there is an 
error in your JavaScript. It also displays the line 
where it became a problem for the interpreter. 

>CONDITIONAL BREAKPOINTS 
You can indicate that a breakpoint should be 
triggered only if a condition that you specify is 
met. The condition can use existing variables. 

*DEBUGGING TIPS*
- ANOTHER BROWSER 
Some problems are browserspecific. Try the code in another 
browser to see which ones are 
causing a problem. 
- ADD NUMBERS 
Write numbers to the console so you can see which the items 
get logged. It shows how far your code runs before errors stop it. 
- STRIP IT BACK 
Remove parts of code, and strip it down to the minimum you 
need. You can do this either by removing the code altogether, or 
by just commenting it out using 
multi-line comments: 
/* Anything between these 
characters is a cofllllent */ 
- EXPLAINING THE CODE 
Programmers often report finding a solution to a problem 
while explaining the code to someone else. 

- SEARCH 
Stack Overflow is a Q+A site for programmers. 
Or use a traditional search engine such as Google, Bing, or 
DuckDuckGo. 
- CODE PLAYGROUNDS 
If you want to ask about problematic code on a forum, in 
addition to pasting the code into 
a post, you could add it to a code 
playground site (such as JSBin.com, JSFiddle. com, or 
Dabbl et. corn) and then post a link to it from the forum. 



