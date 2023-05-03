# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML

### When should you use an unorder list?

Unordered lists are great when you need a list without numbers. They are commonly used in navigation.

### How do you change the bullet style of unordered lists?

Simply with the CSS property `list-style-type`

### When should you use an ordered list vs an unorder list in your HTML document?

When you need items ordered in a particular order you would use an ordered list, an unordered list for anything else whos order doesn't matter.

### Describe two ways you can change the numbers on list items provided by an ordered list?

The type property applied to an ordered list will allow you to change the list numbers to other things like roman numerals or numbers. the start property can be used to start the list at anypoint in whatever list style you are using.

## CSS

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding is a guard at the local castle who keeps people away from the front lawn while margin is a guard that keeps people away from the fenceline. Their role is to keep the area clean and spaced so that the property isn't encroached on and always looks its best.

### List and describe the four parts of an HTML elements box as referred to by the box model.

> Content Edge

This is the edge of the very thing you put in the html tag, whether it be text or an image this is the size of the content, and perhaps the whole row.

> Padding Edge

This is the box around the content that provides a buffer between the content and the border.

> Border Edge

You can make a border as thick or as thin as you like and it sits between the padding edge and the margin.

> Margin Edge

This is the padding around the border, providing space outside the border.

## JavaScript

### What data types can you store inside of an Array?

In Javascript any and all types of data can be stored in an array, even other arrays.

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

I believe it is, and you can get all the data by for of array to pull every item out. You can also pull out individual items by their reference number.

### List five shorthand operators for assignment in javascript and describe what they do.

> `Addition Assignment Operator - x += y is the same as x = x + y`
> `Multiplication Assignment Operator - x *= y is the same as x = x * y`
> `Exponetation Assignment Operator - x **= y is the same as x = x ** y or x = x^y`
> `Subtraction Assignment Operator - x -= y is the same as x = x -y`
> `Division Assignment Operator - x /= y is the same as x = x/y`

### Read the code below and evaluate the last expression and explain what the result would be and why.

10dog, dog is a string so the + signs become concatinations and since false is an empty string the answer simply becomes 10dog.

### Describe a real world example of when a conditional statement should be used in a JavaScript program.

Password is the first thing to come to mind. You want to check if it is correct, and if not send them elsewhere.

### Give an example of when a Loop is useful in JavaScript.

When you want to pull multiple pieces of data from a list or array.

[Return to Code 201 notes](README.md)
