# FUNCTIONAL PROGRAMMING

1) What is functional programming?  
**Functional Programming is a programming paradigm where you mostly construct and structure your code using functions. These functions take input which is called as arguments then shows the output based on the inputs being taken which, given the same input always results in the same output.**

2) What is a pure function and how do we know if something is a pure function?  
**The definition of a pure function is: The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.**

3) What are the benefits of a pure function?  
**One of the major benefits of using pure functions is they are immediately testable. They will always produce the same result if you pass in the same arguments. They also makes maintaining and refactoring code much easier.**

4) What is immutability?  
**Immutable data cannot change its structure or the data in it. It's setting a value on a variable that cannot change, making that value a fact, or sort of like a source of truth — the same way a princess kisses a frog hoping it will turn into a handsome prince. Immutability says that frog will always be a frog.**

5) What is Referential transparency?  
**Referential transparency, a term commonly used in functional programming, means that given a function and an input value, you will always receive the same output. That is to say there is no external state used in the function.**

---

1) What is a module?  
**The Module pattern is used to mimic the concept of classes (since JavaScript doesn't natively support classes) so that we can store both public and private methods and variables inside a single object.**  

2) What does the word ‘require’ do?  
**The require() method is used to load and cache JavaScript modules. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.**

3) How do we bring another module into the file the we are working in?  
**The static import statement is used to import read only live bindings which are exported by another module.**

4) What do we have to do to make a module available?  
**The first thing you do to get access to module features is export them. This is done using the export statement.**
