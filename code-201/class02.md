# Basics of HTML, CSS, and JS

## HTML

### Semantic Elements

Semantic elements are useful as they are self-descriptive of their purpose. Makes coming back to the document later, or opening someone elses easier to read and understand the flow of.

### Headings

There are 6 levels of headings h1 through h6

### Sup and Sub elements

Super script raises the text half a character above the normal line. The Sub element puts it half a character below.

### abbr tag (Abbreviation tag)

Pretty semantic, you use it when using abbreviations so you can add extra styling. Using the title element will fully expand the term.

## CSS

### Applications

There are three ways I know of to apply css to the HTML. 

- First is internal where you write all your css styles inside your html file, typically in the header surrounded by a `<style></style>` tag.

- Second is inline, and that is writing the style in the actual element itself. For example; `<p style="background-color: red;"></p>`

- Third is linking a style sheet in your header using a link tag. for example; `<link rel="stylesheet" href="style.css">`

### Disadvantages of inline styles

Lack of reusability - the style simply applies to that line, not all elements of that type. So if you invent the wheel for one`<p>` tag you have to invent the same wheel for all `<p>` tags rather than just being able to apply it once.

Messy - It makes your HTML much denser and harder to read

## Answer Code Question

`   h2 {
     color: black;
     padding: 5px;
   } `

The representing selectior is h2. The CSS declerations are everything between `{}`. The properties are `color` and `padding`.

## JavaScript

What data type is a sequence of text enclosed in single quote marks?

- String

List 4 types of JavaScript operators.

- Addition (`+`)

- Assignment (`=`)

- Not equal value or not equal type (`!==`)

- Subtraction (`-`)

### Conditionals

An if statement checks a condition and if it evaluates to true then the code block will execute.

`elseif` is used in a conditional if you want to have more than one condition tested before exiting to the all others response.

- `==` is equal to

- `!=` is not equal

- `>=` is greater than or equal to

`&&` means both conditions must evaluate to true, while `||` (or) only one condition must evaluate to true.

[Return to Code 201 notes](README.md)
