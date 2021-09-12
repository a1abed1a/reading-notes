# State and Props
1) Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?  
**The render happens first then the componentDidMount.**

2) What is the very first thing to happen in the lifecycle of React?  
**Constructor().**

3) Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates  
   - **constructor**
   - **render**
   - **React Updates**
   - **componentDidMount**
   - **componentWillUnmount**  
4) What does componentDidMount do?  
**It is a process that is called immediately after a component has been installed. If you need to load anything using network request or DOM config you should go here. This method is a good place to set up any subscriptions.**  

---

1) What types of things can you pass in the props?  
**It allows us to pass values from the parent component to the child component. Values can be of any data type.**

2) What is the big difference between props and  state?  
**The state is internal and controlled by the component itself while props are external and controlled by whatever makes the component.**

3) When do we re-render our application?  
**React components automatically re-render whenever there is a change in their state or props.**

4) What are some examples of things that we could store in state?  
**A string , number or any complex object.**
