# Passing Functions as Props

## Lists and Keys

### What does .map() return?

map() iterates through an array and returns those items to a new array.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

use an arrow function and map to display each item in the array

### Each list item needs a unique ____.

Key. Why? Never really explained other than do it. I read that whole page and it never really explained WHY they are needed despite having a section that would "go indepth"

### What is the purpose of a key.

Best I can tell is to provide an id to a rendered item. Why? I don't know. What does it do? I don't know.

## The Spread Operator

### What is the spread operator?

(...)

### List 4 things that the spread operator can do.

> Copying an Array

> Using math functions

> Adding an item to a list

> Adding to state in React

### Give an example of using the spread operator to combine two arrays.

let newArr = [...firstArr,...secondArr];

### Give an example of using the spread operator to add a new item to an array.

let newArr = ['new item', 'new item', ...oldArr];

### Give an example of using the spread operator to combine two objects into one.

let newObj = [...objOne, ...objTwo];

## Pass Functions Between Components

### In the video, what is the first step that the developer does to pass functions between components?

Creates the function? I didn't understand the video

### In your own words, what does the increment function do?

Which one? The one on app increments the counter while the one on person added the updated tag. It did not make sense to me

### How can you pass a method from a parent component into a child component?

by referencing it it seems?

### How does the child component invoke a method that was passed to it from a parent component?

this.props.methodname

### Further thoughts

The key thing still does not really answer WHY. I get it needs to be, but there really isn't a good explanation of why. The passing between components. I didn't really see anything special or that stood out here. Not sure what the point of that was. I'll watch the video again later maybe, but so far it really didn't explain things in a way that I understood.