# React Docs - lists and keys


1- What does .map() return?
new array

2- If I want to loop through an array
 and display each value in JSX, how
 do I do that in React?

 You can build collections of 
 elements and include them in JSX 
 using curly braces {}.

 we loop through the numbers array 
 using the JavaScript map() function. 
 We return a `<li>` element for each 
 item.
 we assign the resulting array of 
 elements to listItems
We include the entire listItems array
 inside a `<ul>` element, and render 
 it to the DOM.


3- Each list item needs a unique 
__String__.

4- What is the purpose of a key?'

Keys help React identify which items 
have changed, are added, or are
 remove.

[👉 you can read more here 👈](https://reactjs.org/docs/lists-and-keys.html)

# The Spread Operator

1- What is the spread operator?
Spread operator allows an iterable to 
expand in places where 0+ arguments 
are expected. It is mostly used in 
the variable array where there is 
more than 1 values are expected. It 
allows us the privilege to obtain a 
list of parameters from an array

2- List 4 things that the spread 
operator can do.

+ Adding an item to a list
+ Adding to state in React
+ Combining objects
+ Converting NodeList to an array

3- Give an example of using the s
pread operator to combine two arrays.
const fewFruit = ['1','2','3']
const fewMoreFruit = ['4', '5', ...
fewFruit]
console.log(fewMoreFruit) //  Array
(5) [ "1", "2", "3", "4", "5" ]

4- Give an example of using the 
spread operator to add a new item to 
an array.

const fruits = ['🍏','🍊','🍌','🍉',
'🍍']

const moreFruits = [...fruits];

console.log(moreFruits) // Array(5) [ 
"🍏", "🍊", "🍌", "🍉", "🍍" ]

fruits[0] = '🍑'

console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍

5- Give an example of using the 
spread operator to combine two 
objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...
objectTwo, laugh: "😂"}
console.log(objectThree) // Object { 
hello: "🤪", world: "🐻", laugh: "😂" 
}
const objectFour = {...objectOne, ...
objectTwo, laugh: () => {console.log
("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

[👉 you can read more here 👈](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)


# How to Pass Functions Between Components?

1- In the video, what is the first 
step that the developer does to pass 
functions between components?

create the function wherever the state is that we're going to change

2- In your own words, what does the 
increment function do?

a function to find match name and 
if it match the name it will increment the count and add to it.

3- How can you pass a method from a 
parent component into a child 
component?

to pass from a parent component into a child component we will use *props*

4-How does the child component invoke 
a method that was passed to it from a 
parent component? 

this is way to invoke a method that 
was passed to it from a parent 
component 

#### *this.props.increment*

[👉 you can watch here 👈](https://www.youtube.com/watch?v=c05OL7XbwXU)

