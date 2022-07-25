## Passing Functions as Props

# What does .map() return?

new array with the same length as the original array

# If I want to loop through an array and display each value in JSX, how do I do that in React?
-use the {}
-use the .map()
-assign a html tag for the iterated array

# Each list item needs a unique ____.

key

# What is the purpose of a key?

should be given to the elements inside the array to give the elements a stable identity

# What is the spread operator? 

JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.


# List 4 things that the spread operator can do.
-combine 2 arrays
-add new item to the array
-combine 2 objects
-spread the array into separate arguments


# Give an example of using the spread operator to combine two arrays

[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" } 

# Give an example of using the spread operator to add a new item to an array

const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

# Give an example of using the spread operator to combine two objects into one.

const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

# In the video, what is the first step that the developer does to pass functions between components?

Create a function wher the state is changing

# In your own words, what does the increment function do?

increament will increase the counter value by 1  each time I passed to it a value, and it will loop through the array of objects and update the relative counter

# How can you pass a method from a parent component into a child component?

by passing the method as a props

# How does the child component invoke a method that was passed to it from a parent component?

using this.props."method name"
