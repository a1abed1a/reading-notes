# HTML | Design Form
**What is HTML Form :** 
HTML Form is a document which stores information of a user on a web server using interactive controls. An HTML form contains different kind of information such as username, password, contact number, email id etc. 
The elements used in an HTML form are check box, input box, radio buttons, submit buttons etc. Using these elements the information of an user is submitted on a web server.Input Element in HTML Forms :
Input Elements are the most common elements which are used in HTML Forms. Various user input fields can be created such as textfield, check box, password field, radio button, submit button etc. The most common input elements are listed below: 
Text Field in HTML Forms : The text field is a one line input field allowing the user to input text. Text Field input controls are created using the “input” element with a type attribute having value as “text”.
Password Field in HTML Forms : 
Password fields are a type of text field in which the text entered is masked using asterisk or dots for prevention of user identity from another person who is looking onto the screen. Password Field input controls are created using the “input” element with a type attribute having value as “password”.
Radio Buttons in HTML Form : 
Radio Buttons are used to let the user select exactly one option from a list of predefined options. Radio Button input controls are created using the “input” element with a type attribute having value as “radio”.
Checkboxes in HTML Form : 
Checkboxes are used to let the user select one or more options from a pre-defined set of options. Checkbox input controls are created using the “input” element with a type attribute having value as “checkbox”.
EVENT IN JS What is an Event ?
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.
When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.
Developers can use these events to execute JavaScript coded responses, which cause buttons to close windows, messages to be displayed to users, data to be validated, and virtually any other type of response imaginable.
Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.
Example
Try the following example.
`<html>`

`   <head>   `

`      <script type = "text/javascript">`

`         <!--`

`            function sayHello() {`

`               alert("Hello World")`

`            }`

`         //-->`

`      </script>      `

`   </head>`
   
`   <body>`

`      <p>Click the following button and see result</p>   `   

`      <form>`

`         <input type = "button" onclick = "sayHello()" value = "Say Hello" />`

`      </form>      `

`   </body>`

`</html>`