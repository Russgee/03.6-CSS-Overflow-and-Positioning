# 03.6 CSS Overflow & Positioning

## Part 1 - Code Along (CSS Overflow)

1. In CSS, create a class called `.overflow-auto`. Inside this class, set the property `overflow:auto;` This property will automatically trigger the overflow property.
2. In CSS, create a class called `.overflow-show`. Inside this class, set the property `overflow:visible;` This is the default property of overflow: it will show all the content outside the box you have created, if the box is not large enough to fit everything.
3. Create another class called `.overflow-hidden`. Inside this class, set the property `overflow:hidden;` This will hide all the content that overflows outside the box.
4. Create another class called `.overflow-scroll` Inside this class, set the property `overflow:scroll;`. This will create a scroll bar.
 
## Part 2 - Code Along (CSS Positioning)

There 4 main CSS positioning values: static, absolute, fixed, and relative. Let's see how each one works.

1. Static. Static really just means that an element (in these exercises, divs) are positioned just as they would be in the normal flow of the page. This is useful to override other positioning commands.
2. On line 45 of your CSS, set the position to static
3. Now, on the line below, set left to 10px...wait! It didn't move! Static maintains the default alignment of an element!
4. Absolute. Absolute elements are positioned to their nearest ancestor (HTML element that is wrapped around it - often a div). In the following example, we'll work with a div inside of wrapper 
5. On line 52 of your CSS, set the position to absolute. Nothing should look different yet.
6. Now set left to a value of 100px. It moved!
7. Adjust the screen size - you'll notice that Div Two is moving according to where the edge of wrapper 1 is - that's absolute positioning!
8. Fixed. Fixed positioning is relative to the browser window (or the "viewport"), regardless on what divs or anything else are around it.
9. On line 58 set the position to fixed. Nothing will seem to change yet.
10. Now, on the next line, set left to 200px. Div three appears to have moved outside of its wrapper! It's now only respecting its position relative to the browser window (or "viewport")!
11. Relative. Relative positioning means that the HTML element moves only in relation to itself. In other words, it stays the way it would normally look if it were static, but will then move any direction from its starting place based on how far you tell it to move.
12. On line 64, set the position to relative. Nothing should change. *Now set left to 60px. Div four should now have move to the right!
