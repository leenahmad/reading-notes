# Text

 ## HTML Formatting Elements

### Formatting elements were designed to display special types of text:

* <(b> - Bold text
* <(strong> - Important text
* <(i> - Italic text
* <(em> - Emphasized text
* <(mark> - Marked text
* <(small> - Smaller text
* <(del> - Deleted text
* <(ins> - Inserted text
* <(sub> - Subscript text
* <(sup> - Superscript text

## Structural markup in html 


What is Structural Markup? Structure is the information components within an HTML document. For instance: headings, lists and paragraphs. HTML provides some elements that are strictly "structural" - meaning that they are used to define the structure for a web page, in semantic terms.


## Semantic markup in html

emantic markup is a way of writing and structuring your HTML (Hypertext Markup Language) so that it reinforces the semantics, or meaning, of the content rather than its appearance. ... Writing semantic markup means understanding the hierarchy of your content and how both users and machines will read it.


![markup](https://fretfiver.files.wordpress.com/2015/02/html5_semantic.png)

## Text Summary

* HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
* They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

# *Introducing CSS*

### What is CSS?
CSS stands for Cascading Style Sheets with an emphasis placed on “Style.” While HTML is used to structure a web document (defining things like headlines and paragraphs, and allowing you to embed images, video, and other media), CSS comes through and specifies your document’s style—page layouts, colors, and fonts are all determined with CSS. Think of HTML as the foundation (every house has one), and CSS as the aesthetic choices (there’s a big difference between a Victorian mansion and a mid-century modern home).

![css](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTb9f0Ayeh_3Xag9MVWe7Dv3cR0XzUL2XqbB8ybIcLUX8wSWRS1ZEIKhl2IcI7w6EBFZZg&usqp=CAU)

### How Dose CSS work 
How Does CSS Work?

1. CSS brings style to your web pages by interacting with HTML elements. Elements are the individual HTML components of a web page—for instance a paragraph—which in HTML might look like this:
 <(p>This is my paragraph!</p)>

2. If you wanted to make this paragraph appear pink and bold to people viewing your web page through a web browser, you’d use CSS code that looks like this:  p  {  color:pink;  font-weight:bold;  }

3. In this case, “p” (the paragraph) is called the “selector”—it’s the part of CSS code specifying which HTML element the CSS styling will effect. In CSS, the selector is written to the left of the first curly bracket. The information between curly brackets is called a declaration, and it contains properties and values that are applied to the selector. Properties are things like font size, color, and margins, while values are the settings for those properties. In the example above, “color” and “font-weight” are both properties, and “pink” and “bold” are values. The full bracketed set of
{  color:pink;  font-weight:bold;  } 

4. is the declaration, and again, “p” (meaning the HTML paragraph) is the selector. These same basic principles can be applied to change font sizes, background colors, margin indentations, and more. For instance. . .

5. body  {  background-color:lightblue;  }
. . .would make your page’s background light blue, or. . .

6. p  {  font-size:20px;  color:red;  }
. . .will create a 20 point font paragraph with red letters.





## Introducing CSS SUMMARY
* CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Different types of selectors allow you to target your
rules at different elements.
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document,
although they may appear within an HTML page.


# Basic JavaScript Instructions

## What is JavaScript?
JavaScript ("JS" for short) is a full-fledged dynamic programming language that can add interactivity to a website. It was invented by Brendan Eich (co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation).

JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!

JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:

Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.


![js](https://www.tutorialrepublic.com/lib/images/javascript-illustration.png)


## Basic JavaScript Instructions Summary
* A script is made up of a series of statements. Each
statement is like a step in a recipe.
* Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.
* Variables are used to temporarily store pieces of
information used in the script.
* Arrays are special types of variables that store more
than one piece of related information.
* JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
* Expressions evaluate into a single value.
* Expressions rely on operators to calculate a value.


# Decisions and Loops

Decision Making in programming is similar to decision making in real life.

A programming language uses control statements to control the flow of execution of the program based on certain conditions.

*JavaScript’s conditional statements are:* 

* if
* if-else
* if…else…if  

## Decisions and Loops summary

1. Conditional statements allow your code to make
decisions about what to do next.
2. Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
3. Logical operators allow you to combine more than one
set of comparison operators.
4. if ... else statements allow you to run one set of code
   if a condition is true, and another if it is false.


   