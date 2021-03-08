# INTRODUCING CSS

CSS allows you to create rules that specify how the content of an element should appear. Forexample, you can specify that the background of the page is cream, all paragraphs should Appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
Once you have learned how to write a CSS rule, learning CSS mostly involves learning thedifferent properties you can use.

So this chapter will:
● Introduce you to how CSS works
● Teach you how to write CSS rules
● Show you how CSS rules apply to HTML pages

## CSS Associates Style rules with HTML elements

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

- **Selectors** indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

- **Declarations** indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

**EX** :
p {
 font-family: Arial;}

## Foreground Color

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

- rgb values
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
- hex codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
- color names
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.

body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}

## SUMMARY COLOR

- Color not only brings your site to life, but also helps convey the mood and evokes reactions.
- X There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
- X Color pickers can help you find the color you want.
- X It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- X CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
- X CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.
