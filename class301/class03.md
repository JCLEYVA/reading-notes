## Passing Functions as Props

**1.What does .map() return?**
The .map  function is a built-in method in JavaScript that allows you to loop over an array and perform some operation on each element. When you use it on an array, it returns a new array with the same length as the original array.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**
You can use the .map function to loop through an array and return a new array of JSX elements. We can loop through an array and return a new array of using div elements, with each element containing one value from the original array. We then render the array of div elements within another div.


**Each list item needs a unique ____.**
The answer is "key"

**What is the purpose of a key?**
The "key" attribute in React is used to help React identify which items have changed, been added, or been removed from a list of elements. 