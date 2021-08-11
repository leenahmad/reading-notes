# Debugging

## What is Debugging?
In the development process of any software, the software program is religiously tested, troubleshot, and maintained for the sake of delivering bug-free products. There is nothing that is error-free in the first go.

So, it's an obvious thing to which everyone will relate that as when the software is created, it contains a lot of errors; the reason being nobody is perfect and getting error in the code is not an issue, but avoiding it or not preventing it, is an issue!

All those errors and bugs are discarded regularly, so we can conclude that debugging is nothing but a process of eradicating or fixing the errors contained in a software program.

Debugging works stepwise, starting from identifying the errors, analyzing followed by removing the errors. Whenever a software fails to deliver the result, we need the software tester to test the application and solve it.

Since the errors are resolved at each step of debugging in the software testing, so we can conclude that it is a tiresome and complex task regardless of how efficient the result was.


![img](https://www.elprocus.com/wp-content/uploads/Featured-image-2.png)

## Why do we need Debugging?
Debugging gets started when we start writing the code for the software program. It progressively starts continuing in the consecutive stages to deliver a software product because the code gets merged with several other programming units to form a software product.

Following are the benefits of Debugging:

- Debugging can immediately report an error condition whenever it occurs. It prevents hampering the result by detecting the bugs in the earlier stage, making software development stress-free and smooth.
- It offers relevant information related to the data structures that further helps in easier interpretation.
- Debugging assist the developer in reducing impractical and disrupting information.
- With debugging, the developer can easily avoid complex one-use testing code to save time and energy in software development.


# JavaScript Debugging
Sometimes a code may contain certain mistakes. Being a scripting language, JavaScript didn't show any error message in a browser. But these mistakes can affect the output.

The best practice to find out the error is to debug the code. The code can be debugged easily by using web browsers like Google Chrome, Mozilla Firebox.


## JavaScript Debugging Example
Here, we will find out errors using built-in web browser debugger. To perform debugging, we can use any of the following approaches:

1. Using console.log() method
2. Using debugger keyword

## Using console.log() method
The console.log() method displays the result in the console of the browser. If there is any mistake in the code, it generates the error message.

## Using debugger keyword
In debugging, generally we set breakpoints to examine each line of code step by step. There is no requirement to perform this task manually in JavaScript.

JavaScript provides debugger keyword to set the breakpoint through the code itself. The debugger stops the execution of the program at the position it is applied. Now, we can start the flow of execution manually. If an exception occurs, the execution will stop again on that particular line.

[You can read more about Debugging](https://www.oreilly.com/library/view/javascript-cookbook/9781449390211/ch10.html)


## How to Debug JavaScript Errors
Debugging JavaScript errors in a production environment can be a difficult experience. More often than not, the error reports are vague, and identifying the underlying causes can be difficult at best. That said, there are a few common steps that can be followed towards identifying and resolving errors that crop up in production.

![img](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors.jpg)


### Step 1: Attempt to replicate circumstances
In software development, the first step towards debugging any issue is attempting to replicate the circumstances. With most programming languages, this is bolstered by reviewing logs leading up to an error, but with client-side JavaScript, this type of diagnosis requires significantly more foresight (more on that below).

Before we can replicate any circumstances of an issue, and assuming we have access to any production logs, we first need to establish some testing guidelines. This involves doing things like mimicking the production database, the user accounts involved, and even the operating system. Everything is fair game here.

### Step 2: Test assumptions
Once you've established the circumstances that you think might throw the exception or error you are hunting down, it's time to test them. Never test exceptions in production. Development and staging environments are designed to be breakable without any impact on the end users, so always always always try to break your code in a safe environment.

### Step 3: Increase logging
More information is always better. Using the methods described in Where are JavaScript Errors Logged?, the first step towards diagnosing any issue is to increase the amount of data you are logging. This allows you to see everything that is happening before and after a problem occurs. There is a good chance that the problems you are experiencing have potential warnings associated with them that don't necessarily make it into the logs by default.

### Step 4: Adjust test parameters and try again
If you were unable to replicate the problem in Step 2, then it's back to the drawing board. Not every error is easy to reproduce, and may have time-based constraints or something else making it difficult to replicate in a non-production environment. Jump back to Step 1, adjust your test parameters, and try it all over again.

## What are Source Maps?
In a production environment, JavaScript files are often compressed. While this is a great way to speed up any application, it can make debugging a nightmare, as the files you are trying to debug are practically unreadable. This is where source maps come into the picture. Supported by most modern browsers, a source map is a file that maps uncompressed code to compressed code, allowing you to see exactly what is going on within a production environment.

While most minification tools have built-in support for source maps, it is important to understand exactly how the browser connects compressed code to uncompressed code. In a nutshell, this comes in the form of a comment within a compressed JavaScript file that points directly to the source map.

## Summary rror Handling & Debugging
- If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
- Debugging is the process of finding errors. It involves a
process of deduction.
- The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.



