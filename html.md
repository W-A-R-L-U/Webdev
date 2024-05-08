# HTML - HYPER TEXT MARKUP LANGUAGE
* Creating web pages, describes structure of web page

### Structure of html
```
<!DOCTYPE html>
<html>
    <head>
    
    </head>
    <body>

    </body>
</html>
```

**HTML element** - An HTML element is defined by a start tag, some content, and an end tag
```
<tagname>Content</tagname>
```

* html - root element 
* head - contains meta information about HTML page
* title - specifies a title of page(shown in browser's title bar)
* body - caontains all visible elements

Empty elements does not contain any content like "br" <br>
doctype declaration for html5 is 
```
<!DOCTYPE html>
```
### HTML headings
defined from h1 to h6
```
<h1>Heading</h1>
```
### HTML paragraphs
```
<p>Para</p>
```
### HTML links
* specifies the URL of the page link goes to
```
<a href="website link">Link</a>
```
### HTML image
* src specifies the path to the image
```
<img src="image source" alt="alternative image" width="50" height="50">
```
### HTML Attributes
* attributes provide additional information about elements

* style attribute
  - used to add styles such as color, font, size etc
```
<p style="color:red;">Para</p>
```
* lang attribute
  - to specify the language of the html page, used in html tag
```
<html lang="en"></html>
```
* title attribute
  - defines some extra information when hovered on the text with mouse
```
<p title="This is a title">para</p>
```
<p title="This is a title">para</p>

### HTML display
* You cannot be sure how HTML will be displayed.
* With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.
### HTML horizontal rules
* adds a horizonatal line
```
<hr>
```
### HTML line breaks
* adds new line to the current line
```
<br>
```
### HTML "pre" element
* defines a preformatted text, displays as given in the text within the tags
```
<pre>
Line1
Line2
</pre>
```
<pre>
Line1
Line2</pre>

