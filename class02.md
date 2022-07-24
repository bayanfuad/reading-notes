
### State and Props

## React lifecycle 

React let you define its components as a functions or classes, the methods that you define in these called lifecycle events.
These events can be called during the component life cycle to update the UI and applications states.

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

the render will happen first.

## What is the very first thing to happen in the lifecycle of React?
Calling the constructor and creating the instances.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates :

-Constructor
-render
-React Updates
-componentDidMount
-componentWillUnmount

## What does componentDidMount do? 

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount()

## React State Vs Props

## 1. What types of things can you pass in the props?

any JavaScript data type

## 2. What is the big difference between props and state?2. What is the big difference between props and state?

he state is a local data storage that is local to the component only and cannot be passed to other components. Props are used to pass data from one component to another

## 3. When do we re-render our application?

whenever there is a change in a state or props.

## 4. What are some examples of things that we could store in state?

string , number or any complex object

## Things I want to know more about
React Lifecycle in a simpler way
