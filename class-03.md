# Lists

- Numberd lists
- Bullet lists
- Definition lists

There are lots of occasions when we need to use lists. HTML provides us with three different types:

1. **Ordered lists**: are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
(ol/li)

2. **Unordered lists**: are lists that begin with a bullet point.
(ul/li)

3. **Definition lists**: are made up of a set of terms along with the definitions for each of those terms.
(dl/dt/dd)

## Boxes

- Controlling size of boxes
- Box model for borders, margin and padding
- Displaying and hiding boxes.

At the beginning of this section on CSS, you saw how CSS treats each HTML element as if it lives in its own box.
You can set several properties that affect the appearance of these boxes. In this chapter you will see how to:

- Control the dimensions of your boxes.
- Create borders around boxes
- Set margins and padding for boxes
- Show and hide boxes.

## Basic JavaScript Instructions

- A script is made up of a series of statements. Each statement is like a step in a recipe.
- Scripts contain very precise instructions.
- before creating a calculation using that value.
- Variables are used to temporarily store pieces of information used in the script.
- Arrays are special types of variables that store more than one piece of related information.
- JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
- Expressions evaluate into a single value.
- Expressions rely on operators to calculate a value.

## Decisions and Loops

n this example, the purpose of the switch statement is to present the user with a different message depending on which level they are at. The message is stored in a variable called msg.

var msg;

var level = 2;

switch (level) {

case 1:

    msg = 'Good luck on the first test ' ;

    break;

case 2:

    msg = 'Second of three - keep going!';

    break;

case 3:

    msg = ' Final round, al most there!';

    break;

default :

<<<<<<< HEAD
    msg = 'Good l uck!';
=======
    msg = 'Good luck!';
>>>>>>> abbdd6e442a07e2b0c5c2c5f8819d075175b6816

    break;

var el = document.getEl ementByld('answer');

el .textContent = msg;
