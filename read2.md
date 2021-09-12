# React lifecycle

1- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

### *render*

2- What is the very first thing to happen in the lifecycle of React?

###  *Constructor* 

3- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor ----> render -----> React updates ------>componentDidMount -------->componentWillUnmount


4- What does componentDidMount do?

 invoked immediately after a component is mounted.


 ![img](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

[You can read more about React lifecycle here](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

 # React State Vs Props

 1- What types of things can you pass in the props?
 any data type, from strings to functions, objects

2- What is the big difference between props and state?

state is handled in the component and you can update it inside the component.

props are handled outside the component and must be updated outside 
of the component


3- When do we re-render our application?
 when the user done. if you want to change something in your application you need to store that in stste 

4- What are some examples of things that we could store in state?
 a form if you have an input elemnt check box select a box, that need to be able to be  updated by the user. usig state to store what they're updating that value to end what they're changing that value to.

[you can watch this video for more info](https://www.youtube.com/watch?v=IYvD9oBCuJI)