React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

Single responsibility is a principle that states a component should have one responsibility and if it grows it should then be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?

The app will render in the browser.

3. Once you have a static application, what do you need to add?

You will implement your app.

4. What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?

Either the common owner or another component higher up in the hierarchy should own the state.
(<https://reactjs.org/docs/thinking-in-react.html> Links to an external site.).

Higher-Order Functions

1. What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

The function is comparing if m is greater than n and returns the value as m.

3. Explain how either map or reduce operates, with regards to higher-order functions.

Map will apply the function to all the elements and return a new array with updated values. the length stays the same

(<https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK> Links to an external site.).
