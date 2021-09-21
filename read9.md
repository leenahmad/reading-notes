# FUNCTIONAL PROGRAMMING

What is functional programming?

Functional programming is a programming paradigm in which we try to bind everything in pure mathematical functions style. It is a declarative type of programming style. Its main focus is on “what to solve” in contrast to an imperative style where the main focus is “how to solve”. It uses expressions instead of statements. An expression is evaluated to produce a value whereas a statement is executed to assign variables. 

What is a pure function and how do we know if something is a pure function?

Pure functions: These functions have two main properties. First, they always produce the same output for same arguments irrespective of anything else. 
Secondly, they have no side-effects i.e. they do not modify any arguments or local/global variables or input/output streams. 
Later property is called immutability. The pure function’s only result is the value it returns. They are deterministic. 

What are the benefits of a pure function?

- Pure functions are better than impure functions

- Pure functions are easier to test

- Functional programming leads to fewer bugs

- Functional code tends to have its state isolated, making it easier to comprehend

- Function signatures are more trusted

- Concurrency is more easily kept safe

- Recursion is simpler, though not necessarily easier to learn

- Immutable variables lead to fewer side-effects

In functional and in object-oriented programming, an object is considered as immutable when its state can’t be changed after it was created. The opposite of such an object is a mutable object, which can be modified after its creation.
But what is the state of an object? If, at a given time, for a given object, we wrote down on a piece of paper all the variables of this same object, we would get the state of this object. A program also has a state and this one corresponds to the state of all its objects at a given time. But, to evolve, a program needs to change state and that rapidly. So, an immutable object has a fixed state over time and even if the whole state of the program changes, once created, the state of such an object doesn’t.

What is Referential transparency?

![img](https://www.xenonstack.com/hubfs/xenonstack-functional-programming.png)
<!-- 
# Node JS Tutorial for Beginners #6 - Modules and require()



What is a module?

What does the word ‘require’ do?

How do we bring another module into the file the we are working in?

What do we have to do to make a module available? -->