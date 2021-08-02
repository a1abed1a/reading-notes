# HTML Lists, Control Flow with JS, and the CSS Box Model
**Lists**

+ Ordered lists are lists where each item in the list is
numbered.where each point needs to be identified by a section number.
The ordered list is created with
the `<ol>` element. Each item in the list is placed
between an opening `<li>` tag and a closing `</li>` tag.
+ Unordered lists are lists that begin with a bullet point.
The unordered list is created with the `<ul>` element.
+ Definition lists are made up of a set of terms along with the definitions for each of those terms.
The definition list is created with the `<dl>` element and usually consists of a series of terms and their definitions.`<dt>`This is used to contain the term
being defined.`<dd>`This is used to contain the definition.
+ Nested list You can put a second list inside
an `<li>` element to create a sublist
or nested list.

**Boxes**

In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.
+ Content - The content of the box, where text and images appear.
+ Padding - Clears an area around the content. The padding is transparent.
+ Border - A border that goes around the padding and content.
+ Margin - Clears an area outside the border. The margin is transparent.

![Boxes](https://media.gcflearnfree.org/content/5ef2084faaf0ac46dc9c10be_06_23_2020/box_model.png)

**USING A VARIABLE TO STORE A BOOLEAN**

The values true or fa 1 se are used in the class attributes of HTML elements. These values trigger different CSS class rules: true shows a check, false shows a cross.
the value can only be true/false. You could also think of these values as on/off or 0/1: true is equivalent to on or 1, false is equivalent to off or 0 Second, Booleans are used when your code can take more than one path. Remember, different code may run in different circumstances.

**SHORTHAND FOR CREATING VARIABLES**

1. Variables are declared and
values assigned in the same
statement.
2. Three variables are declared
on the same line, then values
assigned to each.
3. Two variables are declared
and assigned values on the same
line. Then one is declared and
assigned a value on the next line
4. Here, a variable is used to
hold a reference to an element in
the HTML page. This allows you
to work directly with the element
stored in that variable.

**RULES FOR NAMING VARIABLES**

There are 6 rules:
+ The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number.
+ The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.
+ You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.
+ All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.
+ Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age.
+ If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash).

**Logical operators**
Logical operators compare two values and give back a boolean value: either true or false. Logical operators are used in decision making and loops.
Operator | Description
---|---
&& | Logical AND: true if both the operands/boolean values are true, else evaluates to false
\|\| | Logical OR: true if either of the operands/boolean values is true . evaluates to false if both are false
! | Logical NOT: true if the operand is false and vice-versa.

**If Statement**

Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

**Switch statement**

Use the switch statement to select one of many code blocks to be executed.

