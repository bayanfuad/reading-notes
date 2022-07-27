# Thinking in React

One of the many great parts of React is how it makes you think about apps as you build them.

## What is the single responsibility principle and how does it apply to components? 

that means that every funcTion or class should only do one thing, if it ends up having more than functionality, then it needs to decomposed into smaller functions.

## What does it mean to build a ‘static’ version of your application?

it means to build your function without any functionality

## Once you have a static application, what do you need to add?

think about the minimum number of states that your app will need

## What are the three questions you can ask to determine if something is state?

-Is it passed in from a parent via props? If so, it probably isn’t state.

-Does it remain unchanged over time? If so, it probably isn’t state.

-Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

-For each  state identify every component that renders something based on that state.

-Find a common owner component "a single component above all the components that need the state in the hierarchy".

-Either the common owner or another component higher up in the hierarchy should own the state.

-If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

# Higher-Order Functions 

## What is a “higher-order function”?

Functions that operate on other functions,  by taking them as arguments or by returning them.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

it is calling an arrow function to compare between 2 values and return a Boolean value

## Explain how either map or reduce operates, with regards to higher-order functions.

reduce is used to summarize the array to a certain number of values 


## Things I want to know more about

Higher order functions 

sort,filter,forms and map 
