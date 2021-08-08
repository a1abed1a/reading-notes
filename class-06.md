# Problem Domain, Objects, and the DOM
There are many common answers to What is the hardest thing about writing code?
+ Learning a new technology.
+ Naming things.
+ Testing your code.
+ Debugging.
+ Fixing bugs.
+ Making software maintainable.

The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.


Programming is easy if you understand the problem domain.

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

+ Make the problem domain easier.
+ Get better at understanding the problem domain.

**Functions**

We can pass arbitrary data to functions using parameters.

`function showMessage(from, text) { // parameters: from, text
  alert(from + ': ' + text);
}`

showMessage('Ann', 'Hello!'); // Ann: Hello! (\*)
showMessage('Ann', "What's up?"); // Ann: What's up? (**)
When the function is called in lines (\*) and (\*\*), the given values are copied to local variables from and text. Then the function uses them.

---

**NODELISTS:** DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT

When a DOM method can return more than one element, it returns a
Nodelist (even if it only finds one matching element).

**TRAVERSING THE DOM** When you have an element node, you can select another element in relation to it using these five
properties. This is known as traversing the DOM.

**WHITESPACE NODES** Traversing the DOM can be difficult because some browsers add a text node whenever they
come across whitespace between elements.
