# Calling functions

Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters.


The arguments of a function are not limited to strings and numbers. You can pass whole objects to a function. The showProps() function (defined in Working with objects) is an example of a function that takes an object as an argument.

There are other ways to call functions. There are often cases where a function needs to be called dynamically, or the number of arguments to a function vary, or in which the context of the function call needs to be set to a specific object determined at runtime.

## Function scope
Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. However, a function can access all variables and functions defined inside the scope in which it is defined.

In other words, a function defined in the global scope can access all variables defined in the global scope. A function defined inside another function can also access all variables defined in its parent function, and any other variables to which the parent function has access.

## Scope and the function stack
Recursion
A function can refer to and call itself. There are three ways for a function to refer to itself:

- The function's name.
- arguments.callee.
- An in-scope variable that refers to the function.


Within the function body, the following are all equivalent:

- bar()
- arguments.callee()
- foo()

A function that calls itself is called a recursive function. In some ways, recursion is analogous to a loop. Both execute the same code multiple times, and both require a condition (to avoid an infinite loop, or rather, infinite recursion in this case).

# Document Object Model

## Introduction to the DOM
The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. In this guide, we'll briefly introduce the DOM. We'll look at how the DOM represents an HTML or XML document in memory and how you use APIs to create web content and applications.

## What is the DOM?
The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.

A Web page is a document. This document can be either displayed in the browser window or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.

The W3C DOM and WHATWG DOM standards are implemented in most modern browsers. Many browsers extend the standard, so care must be exercised when using them on the web where documents may be accessed by various browsers with different DOMs.


All of the properties, methods, and events available for manipulating and creating web pages are organized into objects (for example, the document object that represents the document itself, the table object that implements the special HTMLTableElement DOM interface for accessing HTML tables, and so forth). This documentation provides an object-by-object reference to the DOM.

The modern DOM is built using multiple APIs that work together. The core DOM defines the objects that fundamentally describe a document and the objects within it. This is expanded upon as needed by other APIs that add new features and capabilities to the DOM. For example, the HTML DOM API adds support for representing HTML documents to the core DOM.

## Why called an Object Model?
Documents are modeled using objects, and the model includes not only the structure of a document but also the behavior of a document and the objects of which it is composed of like tag elements with attributes in HTML.
## Properties of DOM:
Let’s see the properties of the document object that can be accessed and modified by the document object.

1. Window Object: Window Object is always at top of the hierarchy.
2. Document object: When an HTML document is loaded into a window, it becomes a document object.
3. Form Object: It is represented by form tags.
4. Link Objects: It is represented by link tags.
5. Anchor Objects: It is represented by a href tags.
6. Form Control Elements:: Form can have many control elements such as text fields, buttons, radio buttons, and checkboxes, etc.

![img](https://media.geeksforgeeks.org/wp-content/uploads/DOM.png)

## Methods of Document Object: 

1. write(“string”): writes the given string on the document.
2. getElementById(): returns the element having the given id value.
3. getElementsByName(): returns all the elements having the given name value.
4. getElementsByTagName(): returns all the elements having the given tag name.
5. getElementsByClassName(): returns all the elements having the given class name.


Example:

  `<TABLE>`

      <ROWS> 
      <TR> 
      <TD>Shady Grove</TD>
      <TD>Aeolian</TD> 
      </TR> 
      <TR>
      <TD>Over the River, Charlie</TD>
      <TD>Dorian</TD> 
      </TR> 
      </ROWS>
      </TABLE>

![img](https://www.w3.org/TR/WD-DOM/table.gif)


## What DOM is not? 
 
1. The Document Object Model is not a binary description where it does not define any binary source code in its interfaces.
2. The Document Object Model is not used to describe objects in XML or HTML whereas the DOM describes XML and HTML documents as objects.
3. The Document Object Model is not represented by a set of data structures; it is an interface that specifies object representation.
4. The Document Object Model does not show the criticality of objects in documents i.e it doesn’t have information about which object in the document is appropriate to the context and which is not.
 
 1. Level 0: Provides a low-level set of interfaces.
2. Level 1: DOM level 1 can be described in two parts: CORE and HTML.
- CORE provides low-level interfaces that can be used to represent any structured document.
- HTML provides high-level interfaces that can be used to represent HTML documents.
3. Level 2 : consists of six specifications: CORE2, VIEWS, EVENTS, STYLE, TRAVERSAL, and RANGE.
- CORE2: extends the functionality of CORE specified by DOM level 1.
- VIEWS: views allows programs to dynamically access and manipulate the content of the document.
- EVENTS: Events are scripts that are either executed by the browser when the user reacts to the web page.
- STYLE: allows programs to dynamically access and manipulate the content of style sheets.
- TRAVERSAL: allows programs to dynamically traverse the document.
- RANGE: allows programs to dynamically identify a range of content in the document.
4. Level 3: consists of five different specifications: CORE3, LOAD and SAVE, VALIDATION, EVENTS, and XPATH.
- CORE3: extends the functionality of CORE specified by DOM level 2.
- LOAD and SAVE: allows the program to dynamically load the content of the XML document into the DOM document and save the DOM Document into an XML document by serialization.
- VALIDATION: allows the program to dynamically update the content and structure of the document while ensuring the document remains valid.
- EVENTS: extends the functionality of Events specified by DOM Level 2.
- XPATH: XPATH is a path language that can be used to access the DOM tree.

## Summary of  DOM

- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
- From an element node, you can access and update its
content using properties such as textContent and
- i nnerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and
child elements that are siblings of each other.
- In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree .

