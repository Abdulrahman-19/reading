# CSS Layout

- Controlling the position of elements
- Creating site layouts
- Designing for different sized screens

## NORMAL FLOW (position:static)

In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax 
would be:
position: static; 
I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.

## Relative Positioning(position:relative)

Relative positioning moves an element in relation to where it would have been in normal flow.
For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right.
You can indicate that an element should be relatively positioned using the position property with a value of relative.
You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow.

## Absolute Positioning(position:absolute)

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)
The box offset properties (top
or bottom and left or right) specify where the element should appear in relation to its containing element.
In this example, the heading has been positioned at the top of the page and 500 pixels from its left edge. The width of the heading is set to be 250 pixels wide.

## Fixed Positioning(position:fixed)

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.
It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.
