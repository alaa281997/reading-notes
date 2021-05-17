## Class 3
#### map
> we use the map() function to take an array of numbers and double their values. 
#### Basic List Component
> Usually you would render lists inside a component.

#### Keys
> Keys help React identify which items have changed, are added, or are removed

#### Questions

What does .map() return? the new array
If I want to loop through an array and display each value in JSX, how do I do that in React?
<li>{number}</li> using curly braces {}
Each list item needs a unique _key___.
What is the purpose of a key? Keys help React identify which items have changed, are added, or are removed


#### Questions
What is the spread operator? The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
The spread operator was added to JavaScript in ES6 (ES2015)
List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
Give an example of using the spread operator to combine two arrays.
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) /
Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) 
Give an example of using the spread operator to combine two objects into one.

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩



#### Questions 
In the video, what is the first step that the developer does to pass functions between components?
In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?

#### Questions
In the video, what is the first step that the developer does to pass functions between components?
creating increment function passing the person 
In your own words, what does the increment function do?
Count what inside the object that was passed
How can you pass a method from a parent component into a child component?
icrement = this .increment
this.props.increment
How does the child component invoke a method that was passed to it from a parent component?
this.props.name