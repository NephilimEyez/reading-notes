# CSS Layout

## Flexbox!

### Flexbox is designed for one-dimensional content. Explain what this means.

You can control alignment in one direction only, no both.

### Explain the difference between the main axis and cross axis.

The main axis is the main direction of flow. So commands called on the main axis like `justify-content` will apply to the direction of flow rahter than a fixed direction. So if you decided to switch something to a row, it would maintain the spacing and conditions it had along it's previous main axis on it's new main axis. The cross axis is just the other axis and just like the main, any commands called on it will shift should the flow of content shift.

### How can using certain properties of flexbox negatively impact accessibility?

Screen readers will read the order of the HTML file while flexbox allows you to change their visual order. So a screen reader will always see things in the order they are written in html while you could have them reversed on the page visually. Make sure everything still makes sense even in your HTML.

### What are some advantages of using flexbox over float?

I'd say it allows for a more responive design. You don't have to just shrink your text, you can re-arrange blocks of content as the screen changes size.

### How does this topic connect with your long term goals?

I like flexbox. I acknowledge there is a lot of playing around with it to get it to work the way I want, but the same is true in everything I "program" at this point.

[Return to Code 201 notes](README.md)
