# Introduction to React and Components

## Why It's Important

This is important because it gives us the syntax needed to add to our code. 

## Class 03 Reading 

### React Docs - lists and keys
<https://legacy.reactjs.org/docs/lists-and-keys.html>

## What does .map() return?

+ It iterates an array and manipulates or changes the data in the items


## If I want to loop through an array and display each value in JSX, how do I do that in React?**

+ You put a component in the function

## Each list item needs a unique ____.

- Key

## What is the purpose of a key?

+ The Key is used to identify something when it doesn't have a stable ID and keeps track of the items.


### The Spread Operator
<https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>

## What is the spread operator?**

+ A quick syntax for adding items to arrays, combining arrays or objects. It spreads an array out into a function's arguments.



## List 4 things that the spread operator can do.**

1. Copy an array
2. Using Math functions
3. Adding an item to a list
4. Adding to state in React


## Give an example of using the spread operator to combine two arrays.**

```
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
```


## Give an example of using the spread operator to add a new item to an array.**

```
const fruits = ['Apple', 'Orange', 'Pineapple']
const moreFruits = [...fruits];
console.log(moreFruits) ['Apple', "Orange', 'Pineapple', 'Watermelon', 'Grapes']
fruits[0] = 'Plum'
console.log(...[...fruits,'...',...moreFruits])
```



## Give an example of using the spread operator to combine two objects into one.**


const myArray = [`,👌`😒`,`🎶`]
const yourArray = [`🙂👍`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(()ourArray) // [Both arrays]


### How to Pass Functions Between Components
<https://www.youtube.com/watch?v=c05OL7XbwXU>

## In the video, what is the first step that the developer does to pass functions between components?

+ The developer created a function in the parent that controls state


## In your own words, what does the increment function do?

+ It increases the count of an object by a number


## How can you pass a method from a parent component into a child component?

+ You pass it to the child component by calling the method down from the parent to the child.


## How does the child component invoke a method that was passed to it from a parent component?**

+ it calls the method that was passed to it as a prop


### Bookmarks & Review

React Tutorial through ‘Declaring a Winner’
<https://react.dev/learn/tutorial-tic-tac-toe>

React Docs - Lifting State Up
<https://legacy.reactjs.org/docs/lifting-state-up.html>


## Things I Want to Know More About