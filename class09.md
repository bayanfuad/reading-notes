# Functional Programming

## Functional Programming Concepts

## What is functional programming?

Itis a programming paradigm(a style of building the structure and elements of computer programs) that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## What is a pure function and how do we know if something is a pure function?

the function that contains fixed data inside it, and it will not affect any other global variables as an example.
we know the function is pure by : 1- it will return the same result for same argument every time. 2- it will not make any observable side effects.

## What are the benefits of a pure function?

The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

## Given a parameter A → expect the function to return value B Given a parameter C → expect the function to return value D

A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.

## What is immutability?

its state cannot change after it’s created.

## What is Referential transparency?

If a function consistently yields the same result for the same input, it is referentially transparent.

pure functions + immutable data = referential transparency

# Node JS Tutorial  

## What is a module?

Module is just essentially another javascript file.

## What does the word ‘require’ do?

To use module functionality elsewhere in the application.

## How do we bring another module into the file the we are working in?

we use require then the module path in side ("").

## What do we have to do to make a module available?

export it firstly from its original file, then import it to the new file by require.

## Things I want to know more about
Node js and functional programming.
