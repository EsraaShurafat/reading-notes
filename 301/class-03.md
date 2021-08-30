# Passing Functions as Props
![img](https://i.ytimg.com/vi/MhkGQAoc7bc/maxresdefault.jpg)
### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
## What does .map() return? 
- map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) 
## If I want to loop through an array and display each value in JSX, how do I do that in React?
- use map() function returns a map object(which is an iterator) , Embedding map() in JSX
In the examples above we declared a separate listItems variable and included it in JSX
## Each list item needs a unique _key_.
## What is the purpose of a key?
- A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.

![img](https://livecodestream.dev/post/how-to-use-the-spread-operator-in-javascript/featured_hu552373e3dd9cfa7192fd6d6eeac47a64_53660_680x0_resize_q75_box.jpg)


## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## What is the spread operator?
- InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
## List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
## Give an example of using the spread operator to combine two arrays.
As seen in the last example, the spread operator can quickly combine two arrays, an operation known as array concatenation: 
```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

```

## Give an example of using the spread operator to add a new item to an array.
```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

```
## Give an example of using the spread operator to combine two objects into one.
```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

```

## [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

## In the video, what is the first step that the developer does to pass functions between components?
- use props to pass bteween components.
## In your own words, what does the increment function do?
- is a method use it to use state also and increment the counter.
## How can you pass a method from a parent component into a child component?
- using state .
## How does the child component invoke a method that was passed to it from a parent component?
- Create a boolean variable in the state in the parent class. Update this when you want to call a function. Create a prop variable and assign the boolean variable.


## Things I want to know more about :
- [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)


