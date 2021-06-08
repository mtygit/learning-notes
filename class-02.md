## HTML Text

There are two kinds of markups, structural markup and semantic markup:
- Structural markup is using the elements to describe both headings and paragraphs
- Semantic markup will not change the presentation of the text but provide extra information to it

The structural elements:
- Headings: \<h1> to \<h6>
- Paragraphs: \<p>
- Bold: \<b>
- Italic: \<i>
- Superscript: \<sup>
- Subscript: \<sub>
- Line breaks: \<br />
- Horizontal rules: \<hr  />

The semantic elements:
- Importance: \<strong>
- Emphasis: \<em>
- Longer quotes: \<blockquote>
- Shorter quotes: \<q>
- Abbreviations and acronyms: \<abbr>
- Citations: \<cite>
- Definitions: \<dfn>
- Author details: \<address>
- Insertion: \<ins>
- Deletion: \<del>
- No longer accurate: \<s>

## Introducing CSS

CSS works by associating rules with HTML elements. These rules will cause the display of the specified elements. There are two parts are involved, a selector and a declaration.

- Selectors associate to the spicific element
- Declarations will tell us how the selected element should be styled

Using \<link> element in HTML to call the external CSS file:
- href specifies the path to the CSS file
- type spcifies the type of document being linked to, text/css
- rel specifies the relationship between the HTML page and the linked file, stylesheet for CSS file

Using \<style> element to indicate an internal CSS

CSS selectors:
- Universal selector: * {}
- Type selector: h1, p, body {}
- Class selector: .note {} or p.note {}
- ID selector: #idName {}
- Child selector: li>a {}
- Descendant selector: p a {}
- Adjacent sibling selector: h1+p {}
- General sibling selector: h1~p {}

CSS rules cascade:
- The last selector will rule
- The more specific selector will rule
- Add !important after any property value will rule

## Basic JavaScript Instructions

Tips to write a script for a web page:

- It is best to keep JavaScript code in its own Javascript file
- Using <\script> to load the JavaScript file, <\link> is for a CSS file
- Writing comments to explain your code
- Declaring the variable before using it
- There are three types of variables:
  - Numeric data type
  - String data type
  - Boolean data type

Rules for naming variables:

- The name must begin with a letter, dolar sign, or an underscore, it must not not start with a number
- The name can contain letters, numbers, dollar sign, or an underscore, but must not use a dash or a period
- Cannot use keywords or reserved words, like var 
- All variables are case sensitive
- Use a name that describes the kind of information that the variable stores
- Use a capital letter for the first letter of every word after the first word, if the variable name is made up of more than one word

## Decisions and Loops

By using the results of evaluations, you can set the path for your script to proceed. There are two components to a decision:
1. An evaluating expression that will return a value
2. A conditional statement to give a instruction

Comparision operators:
- ==: equal to 
- !=: not equal to
- ===: strict equal to
- !==: strict not equal to
- \>: greater than
- \<: less than
- \>=: greater than or equal to
- \<=: less than or equal to

Logical operators:
- &&: logical and
- ||: logical or
- !: logical not

The if statement is used to check a condition. The code block will be executed if the condition is true.

The if...else statement also is used to check a condition. The first code block will be executed if the condition is true. The second code block will be executed if the condition is false.


[<==Back](README.md)