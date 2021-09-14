# React Docs - Forms


1- What is a ‘Controlled Component’?
A controlled component is a component that renders form elements and 
controls them by keeping the form data in the component's state. In a 
controlled component, the form element's data is handled by the React 
component (not DOM) and kept in the component's state.


2- Should we wait to store the users 
responses from the form into state 
when they submit the form OR should 
we update the state with their 
responses as soon as they enter them? 
Why.

Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.


3- How do we target what the user is 
entering if we have an event handler 
on an input field?

we can use event.target

### HTML

<`input placeholder="Enter some text" name="name"/><p id="values"></p`>


### JavaScript

const input = document.querySelector('input');]

const log = document.getElementById('values');

input.addEventListener('input', updateValue);

function updateValue(e) {
  log.textContent = e.target.value;
}

[you can read more from here](https://reactjs.org/docs/forms.html)

# The Conditional (Ternary) Operator Explained

Why would we use a ternary operator?
A ternary operator allows you to assign one value to the variable if 
the condition is true, and another value if the condition is false. .
. A ternary operator makes the assignment of a value to a variable 
easier to see, because it's contained on a single line instead of an 
if else block.


2- Rewrite the following statement using a ternary statement:


  if(x===y){

 console.log(true);

  } else {

 console.log(false);

  }

   👇

  x===y ? console.log(true) : console.log(false)


[you can read more from here](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
