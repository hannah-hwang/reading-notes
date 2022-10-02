# Design Web Pages with CSS

***CSS*** (Cascading Style Sheets) is used to stylize elements in HTML and specify how they are presented in the web browser.

You can do many thing is CSS such as:

- change the color, font, size of text
- add a background color
- add animation

## Syntax

In CSS, groups of styles are applied to an element or a group of elements.

In this code,

p {
  color: blue;
}

- *p* is the selector which indicates the element that will be styled
- *color* is the property
- *blue* is the value
- so the contents within all of the *p* elements in the HTML will become blue.

There are 3 ways to use CSS:

1. External CSS: written in a separate file that is linked to a HTML file
2. Internal CSS: written inside the *style* elemts inside the head section
3. Inline CSS: written inside the opening tag of an element in HTML; applied to a single element

The order of priority is Inline -> External & Internal -> Browser default
