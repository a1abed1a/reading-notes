# Passing Functions as Props

1) What does .map() return?  
It return an array with the same length, and results of applying the given function to each item.

2) If I want to loop through an array and display each value in JSX, how do I do that in React?  
You can build collections of elements and include them in JSX using curly braces { }.  

3) Each list item needs a unique __Key__.  

4) What is the purpose of a key?  
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.  

---

1) What is the spread operator?  
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.  

2) List 4 things that the spread operator can do.  
   1) Copying an array
   2) Concatenating or combining arrays
   3) Using Math functions
   4) Using an array as arguments

3) Give an example of using the spread operator to combine two arrays.  
`const myArray = [`🤪`,`🐻`,`🎌`]`\
`const yourArray = [`🙂`,`🤗`,`🤩`]`\
`const ourArray = [...myArray,...yourArray]`\
`console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩`

4) Give an example of using the spread operator to add a new item to an array.  
`const fewFruit = ['🍏','🍊','🍌']`\
`const fewMoreFruit = ['🍉', '🍍', ...fewFruit]`\
`console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]`

5) Give an example of using the spread operator to combine two objects into one.  
`const objectOne = {hello: "🤪"}`\
`const objectTwo = {world: "🐻"}`\
`const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}`\
`console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }`\
`const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}`\
`objectFour.laugh() // 😂😂😂😂😂`

---

1) In the video, what is the first step that the developer does to pass functions between components?  
you'll need to create two components, one parent and one child, import the child component in the parent component and return it.  

2) In your own words, what does the increment function do?  
Increases the count of a given name.

3) How can you pass a method from a parent component into a child component?  
   1) import React from "react";export default function Child({data, onChildClick}) { return ( <div className="child">
   2) import Child from './Child'
   3) import React from "react"; import "./styles.css";

4) How does the child component invoke a method that was passed to it from a parent component?  
To call a parent component method from the child component, we need to pass the method as a prop to the child component and access it as a props data inside the child component.
