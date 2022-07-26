# React and Forms  

HTML form elements work a bit differently from other DOM elements in React,  form elements keep some internal state.

## What is a ‘Controlled Component’?

 Controlled Components are which maintain their own state and update it based on user input

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

we should update the state with the user's response when he submit the form because otherwise the app will re-render with each input

## How do we target what the user is entering if we have an event handler on an input field?

this.setState({value: event.target.value} inside the event handler this.state.value for targeting current value

## Why would we use a ternary operator? 

to make if statements shorter into one line of code 

## Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} 
else {
  console.log(false);
} 

answer

x===y ? console.log(true) : console.log(false)

## Things I want to know more about

How to use Forms in react apps 
