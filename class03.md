# why this topic matters as it relates to what you are studying in this module.
its matter because I will deal with many lists to create many elements

## Questions1
1. **What does .map() return?**
    - it returns new array with new values or same values whatever the purpose of use it.
2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**
    - I can use map() methods and then braces to assign value of props for each element
3. **Each list item needs a unique _Key or Id___.**
     
4. **What is the purpose of a key?**
  - keys will help react identify which items has been added, changed or removed.

### Spread operators answers
-What is the spread operator?
 Spreading an array out into a function’s arguments.

-List 4 things that the spread operator can do.
adding items to arrays, combining arrays or objects, Using Math functions and Adding an item to a list

-Give an example of using the spread operator to combine two arrays.
  var arr1 = [1,2,3];
      var arr2 = [4,5,6];
      var merged = [...arr1, ...arr2];

-Give an example of using the spread operator to add a new item to an array.
var oldArray = [{'value': '1', 'label': 'a'}, {'value': '2', 'label': 'b'}]
var newObj = {'value': 'all', 'label': 'all'}
var result = [newObj, ...oldArray]

-Give an example of using the spread operator to combine two objects into one.
const person = { name: 'David Walsh', gender: 'Male' };
const tools = { computer: 'Mac', editor: 'Atom' };

const summary = {...person, ...tools};

### Video Answers
-In the video, what is the first step that the developer does to pass functions between components?
  create a function and a button to trigger that function
-In your own words, what does the increment function do?
  Increase the value of a numerical value
-How can you pass a method from a parent component into a child component?
  Take the textbox's value and add it to your parent's state using the setState function
-How does the child component invoke a method that was passed to it from a parent component?
  The save button click will call handleSaveClick on the child, once the Child component mounts and passes the callback to the Parent component
  
  
### About this topic
- I am still confused about dealing with spread operators

## Things I want to know more about
1. Spraed operators
2. Passing functions into components

### References
freeCodeCamp, geeksForGeeks

  
