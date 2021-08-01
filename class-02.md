# Basics of HTML, CSS & JS
## Text
**Headings**

HTML has six "levels" of
headings:

`<h1>`
`<h2>`
`<h3>`
`<h4>`
`<h5>`
`<h6>`

**Paragraphs**

To create a paragraph, surround
the words that make up the
paragraph with an opening `<p>`
tag and closing `</p>` tag.

**Bold & It alic**

By enclosing words in the tags
`<b>` and `</b>` we can make
characters appear bold.

By enclosing words in the tags
`<i>` and `</i>` we can make
characters appear italic.

**Superscript & Subscript**

The `<sup>` element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.

The `<sub>` element is used to
contain characters that should
be subscript.

**Line Breaks & Horizontal Rules**

the browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag `<br />`.

To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the `<hr />` tag.

**Strong & Emphasis**

The use of the ``<strong>``
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.

The `<em>` element indicates
emphasis that subtly changes
the meaning of a sentence.

**Changes to Content**

The `<ins>` element can be used
to show content that has been
inserted into a document, while
the `<del>` element can show text
that has been deleted from it.

The `<s>` element indicates
something that is no longer
accurate or relevant (but that
should not be deleted).
Visually the content of an `<s>`
element will usually be displayed
with a line through the center.

## Introducing CSS
In this section, we will look at how to
make your web pages more attractive,
controlling the design of them using CSS.

CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.

CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

**CSS Associates Stylerules with HT ML elements**

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

**Using External CSS**

The `<link>` element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.
It should use three attributes:

This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).

This attribute specifies the type
of document being linked to. The
value should be text/css.

This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.

You can also include CSS rules
within an HTML page by placing
them inside a `<style>` element,
which usually sits inside the
`<head>` element of the page.
The `<style>` element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css.

CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

Declarations are made up of two parts: the propertiesof the element that you want to change, and the valuesof those properties. For example, the font-familyproperty sets the choice of font, and the value arialspecifies Arial as the preferred typeface.

CSS rules usually appear in a separate document, although they may appear within an HTML page.

