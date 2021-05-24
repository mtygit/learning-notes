## What is CSS?

CSS (Cascading Style Sheets) allows you to create great-looking web pages. It is a language for specifying how documents are presented to users.

## How to add CSS?

- External CSS
  - One external style sheet can change the entire website by changing just one file
  - It can be written in any text editor and saved with a .css extension
  - The external .css file should not contain any HTML tags
- Internal CSS
  - An internal style sheet may be used if one single HTML page has a unique style
  - The internal style is defined inside the \<style> element, inside the head section
- Inline CSS
  - An inline style may be used to apply a unique style for a single element
  - Add the style attribute to the relevant element, which can contain any CSS property

## Multiple style sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

## Cascading order

All the styles in a page will "cascade" into a new "virtual" style sheet by the following order:
1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

## Color property

The color property specifies the color of text and there are several ways to choose its value:

- HEX value
- RGB value
- RGBA value
- HSL value
- HSLA value


[<==Back>](README.md)