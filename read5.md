# React Docs - Thinking in React

1- What is the `single responsibility 
principle` and how does it apply to 
components?

single responsibility principle, 
that is, a component should ideally 
only do one thing. If it ends up 
growing, it should be decomposed 
into smaller subcomponents.

Since you’re often displaying a JSON 
data model to a user, you’ll find 
that if your model was built 
correctly, your UI (and therefore 
your component structure) will map 
nicely. That’s because UI and data 
models tend to adhere to the same 
information architecture. Separate 
your UI into components, where each 
component matches one piece of your 
data model.


2- What does it mean to build a 
‘static’ version of your application?

To make your UI interactive, you need 
to be able to trigger changes to your 
underlying data model. React achieves 
this with state.

To build your app correctly, you 
first need to think of the minimal 
set of mutable state that your app 
needs. The key here is DRY: Don’t 
Repeat Yourself. Figure out the 
absolute minimal representation of 
the state your application needs and 
compute everything else you need 
on-demand. For example, if you’re 
building a TODO list, keep an array 
of the TODO items around; don’t keep 
a separate state variable for the 
count. Instead, when you want to 
render the TODO count, take the
length of the TODO items array.


3- Once you have a static 
application, what do you need to add?

we’ve identified what the minimal set 
of app state is. Next, we need to 
identify which component mutates, or 
owns, this state.

4- What are the three questions you 
can ask to determine if something is 
state?

1- Is it passed in from a parent via 
props?
 
2-Does it remain unchanged over time? 

3- Can you compute it based on any 
other state or props in your 
component? 

5 How can you identify where state 
needs to live?

* Identify every component that renders something based on that state.
* Find a common owner component (a single component above all the components that need the state in the hierarchy).
* Either the common owner or another component higher up in the hierarchy should own the state.
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.



[you can read more here](https://reactjs.org/docs/thinking-in-react.html)

# Higher-Order Functions

What is a “higher-order function”?

Functions that operate on other 
functions, either by taking them as 
arguments or by returning them, are 
called higher-order functions. Since 
we have already seen that functions 
are regular values, there is nothing 
particularly remarkable about the 
fact that such functions exist. The 
term comes from mathematics, where 
the distinction between functions and 
other values is taken more seriously.

Higher-order functions allow us to 
abstract over actions, not just 
values. They come in several forms. F
or example, we can have functions 
that create new functions.

Explore the `greaterThan` function as 
defined in the reading. In your own 
words, what is line 2 of this 
function doing?

 return a function

Explain how either `map` or `reduce` 
operates, with regards to 
higher-order functions.

Say we have an array of objects 
representing scripts, produced by 
filtering the SCRIPTS array somehow. 
But we want an array of names, which 
is easier to inspect.

The map method transforms an array by 
applying a function to all of its 
elements and building a new array 
from the returned values. The new 
array will have the same length as 
the input array, but its content will 
have been mapped to a new form by the 
function.


The higher-order operation that 
represents this pattern is called 
reduce (sometimes also called fold). 
It builds a value by repeatedly 
taking a single element from the 
array and combining it with the 
current value. When summing numbers, 
you’d start with the number zero and, 
for each element, add that to the sum.

The parameters to reduce are, apart 
from the array, a combining function 
and a start value. This function is a 
little less straightforward than 
filter and map,


[you can read more here](https://eloquentjavascript.net/05_higher_order.html)