# Introductory HTML and JavaScript
## HTML
## Structure
An HTML document mainly consists of a Head and Body. The Head contains the data, which informs the browser and even web servers that it is an HTML document. On the other hand, the Body contains content that web browsers actually display.

Each and every HTML 5 document employs a unique combination of elements and content to define a page. The structure of all the property documented pages is the same and contains:
+ A declaration at the top, which indicates that it is an HTML 5 document
+ A document header
+ A document body

```<!DOCTYPE>``` informs the browsers that it is actually an HTML 5 document. Although there are other types of DOC Types, this is the most commonly used declaration.

The DOCType Declaration is followed by ```<html></html>``` opening and closing tags. These tags contain everything inside the document, including the Head and Body

```<head> </head>``` opening and closing tags, follow the opening Html tag. These tags contain information about the body, title of the page, definitions, labels, etc. You can only use certain markup elements in the HTML 5 head. Some of these elements include style, title, base, link, script, and meta. In HTML 5, these elements are collectively known as HTML Head Elements.

After the closing head tag is the ```<body> </body>```opening and closing body tags. They contain all the content which appears on the browser, as well as the related HTML 5 codes.

Theoretically, you can create an HTML 5 document without anything in the body, but you need to have a well-crafted Head and Body to index your page properly in the browser.

## Extra Markup
**Versions of HTML**
+ HTML 1.0. The basic version of HTML has support for basic elements like text controls and images
+ HTML 2. HTML version 2.0 was developed in 1995 with basic intention of improving HTML version 1.0
+ HTML 3.2. It was developed in 1997
+ HTML 4.01. It was developed in 1999
+ HTML5

**Comments in HTML**
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:

```<!-- comment goes here -->```
 
 **ID Attribute**

 The id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document. The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

 **Class attribute**

The class attribute specifies one or more classnames for an element. The class attribute is mostly used to point to a class in a style sheet. However, it can also be used by a JavaScript (via the HTML DOM) to make changes to HTML elements with a specified class.

**Block Elements**

Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements.
Examples of block elements are
`<h1>`, `<p>`, `<ul>`, and `<li>`.

**Inline Elements**

Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.
Examples of inline elements are
`<a>`, `<b>`, `<em>`, and `<img>`.

**Grouping Te xt & Elements In a Block**

The `<div>` element allows you to
group a set of elements together
in one block-level box.

**Grouping Text & Elements Inline**

The `<span>` element acts like
an inline equivalent of the `<div>`
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text.
2. Contain a number of inline
elements.

You will usually see that a class
or id attribute is used with
`<span>` elements:
+ To explain the purpose of this
`<span>` element.
+ So that CSS styles can be
applied to elements that
have specific values for these
attributes.

**Iframes**

`<iframe>` 08/iframes.html HTML
An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame.

`src`
The src attribute specifies the
URL of the page to show in the
frame.

`height`
The height attribute specifies
the height of the iframe in pixels.

`width`
The width attribute specifies
the width of the iframe in pixels.

## HTML5 Layout 
![Layout](https://www.itgeared.com/images/content/1455-1.png)

**HTML Layout Elements**

HTML has several semantic elements that define the different parts of a web page:

+ `<header>` - Defines a header for a document or a section
+ `<nav>` - Defines a set of navigation links
+ `<section>` - Defines a section in a document
+ `<article>` - Defines an independent, self-contained content
+ `<aside>` - Defines content aside from the content (like a sidebar)
+ `<footer>` - Defines a footer for a document or a section
+ `<details>` - Defines additional details that the user can open and close on demand
+ `<summary>` - Defines a heading for the `<details>` element