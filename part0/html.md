[title](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/)#HTML_basics

##HTML 
is a markup language that defines the structure of your content. HTML consists of a series of elements

##Anatomy of an HTML element
The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
The content: This is the content of the element, which in this case, is just text.
The element: The opening tag, the closing tag, and the content together comprise the element.

##Nesting elements
<p>My cat is <strong>very</strong> grumpy.</p>
##Void elements
<img src="images/firefox-icon.png" alt="My test image" />

##Anatomy of an HTML document
`
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>
`

DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92),
`
<html></html> — the <html> element.
<head></head> — the <head> element.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages.
<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport
<title></title> — the <title> element.
<body></body> — the <body> element.
`
#Images
<img src="images/firefox-icon.png" alt="My test image" />
#Headings
<h1>My main title</h1>
...
#Paragraphs
<p>This is a single paragraph</p>
#Lists
Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a <ul> element.
Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an <ol> element.

#Links
<a>Mozilla Manifesto</a>