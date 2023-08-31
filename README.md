# odin-css-foundations
This repository contains exercises done for a course in web development with theodinproject.com

The course tests understanding of basic css concepts such as selectors and various ways of including css into html files


## Project 1: Css Methods
In this exercise, you're going to practice adding CSS to an HTML file using all three methods: external CSS, internal CSS, and inline CSS. You should only be using type selectors for this exercise when adding styles via the external and internal methods. You should also use keywords for colors (e.g. "blue") instead of using RGB or HEX values.

There are three elements for you to add styles to, each of which uses a different method of adding CSS to it, as noted in the outcome image below. All other exercises in this section will have a CSS file provided and linked for you, but for this exercise you will have to create the file and link it in the HTML file yourself. This is all about practicing using these different methods and getting the syntax right.

### The properties you need to add to each element are:

- div: a red background, white text, a font size of 32px, center aligned, and bold
- p: a green background, white text, and a font size of 18px
- button: an orange background and a font size of 18px

### Output of my work
![Alt text](<Outcome 1.png>)

***
***

## Project 2: Class and ID Selectors

Knowing how to add class and ID attributes to HTML elements, as well as use their respective selectors, is invaluable. It's important to practice using them.

There are several elements in the HTML file provided, which you will have to add either class or ID attributes to, as noted in the outcome image below. You will then have to add rules in the CSS file provided using the correct selector syntax. Look over the outcome image carefully, and try to keep in mind which elements look similarly styled (classes), which ones may be completely unique from the rest (ID), and which ones have slight variations from others (multiple classes).

It isn't entirely important which class or ID values you use, as the focus here is on being able to add the attributes and use the correct selector syntax to style elements. For the colors in this exercise, try using a non-keyword value (RGB, HEX, or HSL). The properties you need to add to each element are:

All odd numbered elements: a light red/pink background, and a list of fonts containing Verdana and DejaVu Sans with sans-serif as a fallback
The second element: blue text and a font size of 36px
The third element: in addition to the styles for all odd numbered elements, add a font size of 24px
The fourth element: a light green background, a font size of 24px, and bold

![Alt text](<Outcome 2.png>)

***
***


***

## Project 3: Grouping Selectors
Let's build a little off the previous exercise, in which you (hopefully) added multiple classes to a single element in order to apply two different rules to it.

Instead of having a single element with two different rules applied, though, you're instead going to give two elements each a unique class name, then add rules for styles that both elements share as well as their own unique styles. Make sure you take a good look at the outcome image to see exactly what is unique about each element, and what both elements have in common.

This will help you further practice adding classes and using class selectors, so be sure you add the class attribute in the HTML file. For the remainder of these exercises, the format of any colors is entirely up to you; we trust you'll practice using the different values! The properties you need to add to each element are:

- The first element: a black background and white text
- The second element: a yellow background
- Both elements: a font size of 28px and a list of fonts containing Helvetica and Times New Roman, with sans-serif as a fallback
