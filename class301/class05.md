## Putting it all together

**What is the single responsibility principle and how does it apply to components?**
The SRP is a software design principle that states that each module or class should have only one reason to change. In React components, this means that each component should be responsible for rendering a specific piece of the UI and should not be responsible for anything else,like managing the state of the application or fetching data from a server. 

**What does it mean to build a ‘static’ version of your application?**
Building a static version of your application means creating a version of the UI that doesn't depend on any user interactions or data changes.
**Once you have a static application, what do you need to add?**
Once you have a static version of your application, you need to start adding interactivity and dynamic behavior to it. You may also need to make API calls to a server to fetch data and update your UI in response to the returned data.

**What are the three questions you can ask to determine if something is state?**

Is it passed in from a parent with props? 
Does it remain unchanged over time? If so, it's probably not state.
Can you compute it based on any other state or props in your component? 
Another approach is to identify which component or components need to respond to user input or changes in the application's state, and then move the state management logic to those components.

**What is a “higher-order function”?**
 a higher-order function is a function that takes one or more functions as arguments, and/or returns a function as its result. 

**Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**
line 2 of this function is returning a new function that takes a single argument m and returns a boolean value indicating whether m is greater than the original argument n.

**Explain how either map or reduce operates, with regards to higher-order functions.**
Both the map and reduce functions are higher-order functions that operate on arrays.
The map function takes an array and a function as arguments, and returns a new array that is the result of applying the function to each element of the original array. It "maps" each element of the original array to a new value using the provided function. The function passed to map is a higher-order function, because it takes each element of the array as input and returns a new value based on that input.

## Things I would like to know more about