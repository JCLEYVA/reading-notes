Css- how we style our websites?
stands for cascading style sheets.
we can select all elements, or specific elements- and apply style to them

There are three ways to use CSS.
1. external stylesheet- insert by adding style.css file
2. Internal style-
3. inline style

CSS syntax 
rule based languae. you define the rules by specifying groups of styles that should be applied to elements or groups of elements on your page

Changing color and font sizes

A selector selects the HTML element that we are going to style. Inside the braces will be a declaration which take the form of property and value parts.

color property
font size property etc.

css specifications
All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos) and define precisely how those technologies are supposed to behave.

There are three ways to insert css
external css
internal css
inline css


External css- with an external style sheet, you can change the look of an etire website by changing just one file.
each HTML page must inclue a reference to the external style sheet file inside the <link> element, inside the head section.

<<<<<<< HEAD
=======
example:
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>


>>>>>>> 155baf1dc7e2b41453c15b5806fab080d715a16d
