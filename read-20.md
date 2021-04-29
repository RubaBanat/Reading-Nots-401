# Component Based UI 

## 1 - Name 5 Javascript UI Frameworks (other than React) ?

- Vue
- Ember
- Svelte 
- Sencha
- Angular

---

## 2 - What’s the difference between a framework and a library?

**The technical difference between a framework and library lies in a term called inversion of control. When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow.**

- Frameworks and libraries are both code written by someone else that helps you perform some common tasks in a less verbose way. 

- A framework inverts the control of the program. It tells the developer what they need. A library doesn’t. The programmer calls the library where and when they need it.

- The degree of freedom a library or framework gives the developer will dictate how “opinionated” it is.


---


## Important Terms


Word | Definition 
------------ | -------------
Rendering| refers to processing any piece of code that we have written and showing the result of it
Templates | is a blueprint or formula for creating a generic class or a function. 
State | the State of a component is an object that holds some information that may change over the lifetime of the component

---

# React 

![React](imgs/React.png)


**React is an open-source, front end, JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.**


## What is JSX?

- *JSX stands for JavaScript XML.*

- *SX allows us to write HTML in React.*

- *JSX makes it easier to write and add HTML in React.*

---

**Coding JSX**

- *JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods.*

- *JSX converts HTML tags into react elements.*

---

**Expressions in JSX**

- *With JSX you can write expressions inside curly braces { }.*

- *The expression can be a React variable, or property, or any other valid JavaScript expression.*

---

## What is ReactDOM?


**ReactDOM is a package that provides DOM specific methods that can be used at the top level of a web app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with an API containing the following methods and a few more.**

- render()
- findDOMNode()
- unmountComponentAtNode()
- hydrate()
- createPortal()


---

# THE END