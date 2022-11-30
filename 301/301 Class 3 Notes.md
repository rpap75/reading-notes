React Docs - lists and keys

1. What does .map() return?

A new array

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

Using the map() function.

3. Each list item needs a unique ____.

string

4. What is the purpose of a key?

The purpose of a key is to help react and identify which items have changed, are added, or are removed.

(<https://reactjs.org/docs/lists-and-keys.html> Links to an external site.).

The Spread Operator

1. What is the spread operator?

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2. List 4 things that the spread operator can do.

Combine arrays, add items to arrays, combine objects, and spread an array out into a function’s arguments.

3. Give an example of using the spread operator to combine two arrays.

const combineArray = [...one, ...two];

4. Give an example of using the spread operator to add a new item to an array.

const addItem = [...originalArray, 'newItem'];

5. Give an example of using the spread operator to combine two objects into one.

const oneTwo = {

        ...one,

        ...two

};

How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

The first step was to create the increment function.

2. In your own words, what does the increment function do?

The increment function takes in 'name' and then loops through the constructor until it matches with a 'name' and updates the 'count'.

3. How can you pass a method from a parent component into a child component?

By passing the 'name' back up to the 'increment' method.

4. How does the child component invoke a method that was passed to it from a parent component?

The state change will cause a rerender and will pass down.
