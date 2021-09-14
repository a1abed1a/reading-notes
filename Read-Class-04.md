# React and Forms
1) What is a ‘Controlled Component’?  
**A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.**

2) Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
**In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with `setState().`**

3) How do we target what the user is entering if we have an event handler on an input field?  
**We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.**

---

1) Why would we use a ternary operator?  
**The ternary operator allows you to assign one value to a variable if the condition is true, and another value if the condition is false. The ternary operand makes it easy to see the assignment of a value to a variable, because it is on a single line rather than an if block.**

2) Rewrite the following statement using a ternary statement:  

`if(x===y){`

 `console.log(true);`

  `} else {`

 `console.log(false);`

  `}`

  Answer

`x===y ? console.log(true) : console.log(false)`