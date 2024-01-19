# React Interview Questions & Answers

## 🚀Introduction

### What is React? What is the Role of React in software development?

React is an open-source JavaScript library for building user interfaces based on UI components. It is created and maintained by Facebook and was released in 2013.

- A ReactJS application is made with multiple components, each component responsible for outputting a small, reusable piece of HTML code. So components are the heart of all React applications.
- React is also famous for building single-page applications and mobile apps.

### What are the key Features of React?

There are several features available on React because it is widely popular.

- **JSX:** JSX is a JavaScript syntax extension. It is faster than normal JavaScript as it performs optimizations while translating to regular JavaScript. By using that, we can write HTML structures in the same file that contains JavaScript code.
- **Virtual DOM:** Virtual DOM is nothing, but a lightweight copy of the Real DOM. Manipulating Real DOM is much slower compared to Virtual DOM, so it's used to improve the performance, update the real DOM, reducing the amount of direct manipulation.
- **Unidirectional Data Flow (One-way Data Binding):** ReactJS follows a unidirectional data flow, also known as one-way data binding. The data is transferred from top to bottom i.e. from parent components to child components. This helps in maintaining a clear and predictable flow of data.
- **Component Based Architecture:** A Component is one of the core building blocks of React. React follows a component-based architecture, where the UI is broken down into reusable and modular components. Each component depends on its own logic, state, and view that making it easier to manage and maintain the code.
- **Performance:** ReactJS is a high-performance library for creating user interfaces. This feature makes it much better than other frameworks. The reason behind, it manages a virtual DOM & use JSX which is faster compared to normal JavaScript and HTML.
- **Simplicity:** ReactJS uses JSX file which makes the application simple and to code as well as understand. We know that ReactJS is a component-based approach which makes the code reusable as your need.
- **Debugging:** React applications are straightforward and easy to test. Even Facebook provides a small browser extension that makes React debugging easier and faster.

### What are the Advantage of React or why we use React?

There are various reasons why you should choose ReactJS as a primary tool for building application.

- Simple to build Single Page Application
- React is cross platform (web & mobile) and open source (free to use)
- Light weight and very fast
- Easy to Learn and Use
- Creating Dynamic web applications becomes easier
- Reusable Components
- Making scalable apps where you may need to frequently add new features
- Better code stability
- Strong community support

### What are the Disadvantage of React?

There are some disadvantage of react like:

- React is not good choice for very small application
- Poor documention is big problem for new developers
- Its just a library for building UI components so complete the react application we need addition tools or libraries like routing, state management so on.
- React support single page application so its face challenges for **SEO** friendly application.

### What is DOM? What is difference between HTML and DOM?

DOM stands for Document Object Model. DOM is the actual tree-like structure of a web page, which is is dynamically generated by the browser when a web page is loaded.

- DOM allows JavaScript to interact and manipulate with the content, structure, and style of a document.
- HTML is a markup language used for creating the static structure of web pages.

### What is Virtual DOM?

Virtual DOM is nothing, but a lightweight copy of the Real DOM. Manipulating Real DOM is much slower compared to Virtual DOM, so it's used to improve the performance, update the real DOM, reducing the amount of direct manipulation.

### Difference between Virtual DOM and Real DOM?

Virtual DOM is nothing, but a lightweight copy of the Real DOM. Manipulating Real DOM is much slower compared to Virtual DOM, so it's used to improve the performance, update the real DOM, reducing the amount of direct manipulation.

Real DOM is the actual tree-like structure of a web page, which can be manipulated directly to change the layout or content of the page.

### How does Virtual DOM work?

When a component's state or props change, React will create a new virtual DOM tree, compare it to the previous tree, and then apply only the minimal set of changes necessary to the actual DOM. This improves the performance of the application and reduces the number of unnecessary re-renders.

### What is the difference between Shadow DOM and Virtual DOM?

The **Shadow DOM** is a browser technology designed to encapsulate the implementation of a component and keep it separate from the rest of the document.

The **Virtual DOM** is a concept used by libraries like React to optimize the process of updating the actual DOM for performance gains.

### What is Single Page Application (SPA)?

A Single Page Application (SPA) is a web application that have only one single page.

Whenever user do some action on the website, then in response content is dynamically updated without refreshing or loading a new page.

### What is the difference between Declarative & Imperative syntax?

- Declarative syntax focuses on **describing the desired result** without specifying the **step-by-step process** while imperative syntax involves step by step process to achive a paticular goal.

- **JSX** in React is used to write declarative syntax while **JavaScript** has an imperative syntax.

```javascript
// Declarative component in React
function Greeting() {
  return <h1>Hello Dev!</h1>;
}

// Imperative component in React
function Greeting() {
  const element = document.createElement("h1");
  element.textContext = "Hello Dev!";
  document.body.appendChild(element);
}
```

### What are the Main Files in a React project?

### How React App Load and Display the components in browser?

### What are the difference between React and Angular?

### Why use React instead of other frameworks, like Angular?

React is a JavaScript library, whereas Angular is a front-end framework.

- React uses one-way data binding and virtual DOM, whereas Angular uses two-way data binding and real DOM.
- React is faster than Angular as it has a smaller bundle size.
- React is developed by Facebook, whereas Angular is developed by Google.

### What are other 5 JS Frameworks other than React?

### Whether React is a Framework or a Library? What is the difference?

### What is the difference between library and framework?

### How React provides Reusability and Composition?

## 📁Files & Folders

### What is NPM? What is the role of node_module folder?

### What is the difference between NPM & NPX?

### What is the role of Package.json?

### What are the difference between package.json & package-lock.json?

### What is the role of public folder in React?

### What is the role of src folder in React?

### What is the role of index.html page in React?

### What is the role of index.js file and ReactDOM in React?

### What is the role of App.js file in React?

### What is the role of function and return inside App.js?

### Can we have a function without a return inside App.js?

### What is the role of export default inside App.js?

### What is the react-scripts package in react application?

### What is the use of the react-dom package?

## ⚡JSX

### What is JSX?

JSX is a JavaScript XML syntax extension used with React to write UI components. It is faster than normal JavaScript as it performs optimizations while translating to regular JavaScript.

### What is the role of JSX in React?

By using JSX, we can write HTML structures in the same file that contains JavaScript code. Its converted into javascript via tool like Babel. Beacuse Browser understand javascript not JSX.

### What are the Advantage of JSX?

- JSX makes it easier to write or add HTML in React.
- JSX can easily convert HTML tags to react elements.
- JSX is faster than regular JavaScript because it performs optimization while translating the code to JavaScript.
- JSX is type-safe, and most of the errors can be found at compilation time.

### What are the Disadvantage of JSX?

- JSX throws an error if the HTML is not correct.
- In JSX HTML code must be wrapped in one top-level element otherwise it will give an error.
- If HTML elements are not properly closed JSX will give an error.

### What is Arrow Function Expression in JSX?

In JavaScript and JSX, an arrow function expression is a concise way to define a function.

### What is Babel?

Babel is a JavaScript transpiler that converts **Modern JavaScript** into plain old ES5 JavaScript that code can run in older browser.

### What is the role of Fragment in JSX?

React **Fragments** allow you to group multiple elements without adding an extra node to the DOM.

- This can be useful when rendering multiple child elements or components in a single parent component.
- Fragments are represented by an empty JSX tag `<>...</>` or `<React.Fragment>...</React.Fragment>`. You can also use key prop with `<React.Fragment>`.

### Why are Fragments better than container div?

**Fragments** are better than container divs because they don't add an extra node to the DOM.

- We can write cleaner, more readable code with React Fragments.
- It takes up less memory and renders components faster. Each component is rendered as expected.

### What is Spread Operator in JSX?

### What are the types of Conditional Rendering in JSX?

### How do you iterate over a list in JSX? What is map() method?

### Can a brower read a JSX File?

Browsers can't read JSX files directly. They must be transpiled or converted to JavaScript before they can be interpreted by the browser.

### What is Transpiler? What is the difference between Compiler & Transpiler?

### Is it possible to use JSX without React?

### What is the difference between cloneElement and createElement?

## 🎨Components

### What are React Components? What are the main elements of it?

### What is the meaning of Component-Based Architecture of React?

### What are Functional Component?

### How do you pass data between Functional Components in React?

### What is Prop Drilling in React?

### Why to Avoid Prop Drilling? In how many ways can avoid Prop Drilling?

### What are Class Components in React?

### How to pass data between class components in React?

### What are Constructors in class components? When to use them?

### What is the role of super keyword in constructor?

### Why are props passed to the super() function in React?

### How the State can be maintained in a class components?

### What are the differences between Functional & Class components in React?

### What are Controlled Components in React?

### What are Uncontrolled Components in React?

### What are the difference between Controlled and UnControlled Components?

### What are Characteristics of Controlled component?

### What are the Advantages of using Controlled Components in React forms?

### What are Pure Components in React and what is their purpose?

### Why should we use functional components over the class component?

## 🧱State

### What are the State in React?

### What are State, Stateless, Stateful and State Management terms?

### What are Stateful components in React?

### What is the Stateless component in React?

### Can you Update the React State directly?

### What is the Purpose of Callback Function as an argument of setState()?

### What will happen if you use setState() in constructor?

## 🎸Props

### What are the Props in React?

### What is the difference between Props and State?

### What is Prop Drilling in React?

### What are PropTypes in React?

### What are predefined PropTypes in React?

### Why should you Validate Props in React?

### What is a Children Prop?

### Why can't you Update Props in React?

## 🎉Hooks

### What are React Hooks? What are the Top React Hooks?

### Why should we Use Hooks in React?

### What is useState() hook and how it works?

### What is the role of useEffect() hook. How it works?

### What is use of useEffect hook?

### What is Dependency Array in useEffect() hook?

### What is the meaning of the empty array [] in the useEffect hook?

### What is the puppose of the useEffect cleanup function?

### What is useContext() hook?

### What is createContext() method? What are Provider & Consumer properties?

### When to use useContext() hook instead of props in real application?

### What is useReducer() hook? When to use it?

### What are the similarities between useState() and useReducer() hook?

### What are the difference between useState() and useReducer hook?

### What are dispatch & reducer function in useReducer Hook?

### What is the purpose of passing initial states as an object in useReducer Hook?

### What is useCallback () hook?

### What parameters does the useCallback hook accept & what does it returns?

### What is useMemo() hook and why use it?

### What is difference between useCallback() & useMemo() Hook?

### What is useRef() Hook?

### What is useLayoutEffect Hook? Compare it with useEffect() hook?

### When to use useLayoutEffect() hook?

### What is the useImperativeHandle() hook?

### What is the useDebugValue() hook?

### What are the Rules or Best Practices for hooks implementation?

### What are Custom Hooks?

### What do you need to keep in mind while creating Custom React Hooks?

### What are the uses of all the Hooks in React?

### When were the React Hooks introduced first?

## 🚴Routing

### What is Routing and Router in React?

### How to implement Routing in React?

### What are the roles of <Routes> & <Route> component in React Routing?

### What are Route Parameters in React Routing?

### What is the role of Switch Component in React Routing?

### What is the role of exact prop in React Routing?

### What is Key prop in React Router?

### How Routing is different from Conventional Routing in React?

## ✈️Component LifeCycle Methods

### What are Component LifeCycle methods?

### What are the different Phases of Component life cycle?

### What is the role of render() method in component life cycle?

### What is the role of componentDisMount() method in component life cycle?

### What is the role of componentDidUpdate() method in component life cycle?

### What is the role of componentWillUnmount() method in component life cycle?

### What is the shouldComponentUpdate lifecycle method?

### What are the Lifecycle of Functional Components?

## ⛹️Rendering & DOM Elements

### How does Rendering work in React?

- Rendering in ReactJS refers to transforming the virtual DOM into the actual DOM that can be displayed in the browser.
- It means taking the React components and converting them into real HTML, CSS, and JavaScript that can be rendered on a web page.

### What is the use of dangerouslySetInnerHTML property in React?

### What are Lists?

### What are Keys in React?

### What is the impact of indexes as key?

### What is the Memo function in React?

### What are Refs in React?

### How to Create Refs?

### What are Rorward Refs and can you give me a code example for it?

### What is Strict Mode in React?

### What will you do if your react application is Rendering Slow?

### How to use CSS in React?

### What are the 5 ways to Style React Components? Explain Inline Styles?

### Why does React use className over class attribute?

### What is the difference between Client side and Server side Rendering?

### How do you implement Server Side Rendering or SSR in React?

### How to focus an input element on page load?

### Difference between React memo and PureComponents?

## 📅Events

### What is an Event in React?

### How to Handle Events in React (for both functional and class components)?

### How to pass parameters to an event handler?

### What is the difference between HTML and React Event Handling?

### What is the meaning of Synthetic Events in React?

## 🍠Code Splitting

### What is Code Splitting in React and why do we use it?

### How to Implement Code Splitting in React?

### What is the Lazy Loading in React?

### What is Suspense component in React?

### What is the role of Lazy and Suspense methods in React?

### What are the Pros and Cons of Code Splitting in React?

### What is Router Based Code Splitting & Lazy Loading with react router?

## 🌐State Management

### How many Types of States in React?

### How to Update State in functional component?

### How to Update State in class components in React?

### What is Lifting State Up in React?

### What is the difference between Local State & Global State in React?

### How many ways to Manage Global State?

### What is the Context API in React?

### Explain the concept of Context in React.

### What is the difference between Context API and Redux?

### Ways to achive state management? When to use in React?

## 📡API Data Fetching

### How to Fetch API in React?

### How to handle Api Error in React?

### What is difference between Fetch and Axios for api call in React?

### What is React Query Library & its advantages?

### How to manage API Cache in React?

### Can Ajax be used in React?

## 🐜Testing, Debugging & Deployment

### What is Unit Testing & why its useful?

### What are the popular Testing Libraries for React?

### What is Jest Library?

### How to debug react application?

### What is React Developer tool?

### What is the Environment File & its benifit?

### How to use Environment Files (.env) in React App?

### What is Bundling in React and why do we use it?

### How to set React to Production Build?

## 💪Advanced

### What is Higher Order Components (HOC) in React?

### How to create props proxy for HOC component?

### How does React handle the Forms?

### Explain the concept of Error Boundaries in React?

### What is the difference between React & ReactDOM?

### Why is ReactDOM separated from React?

### What are React Portals?

### What is Fiber in React?

### What is the main goal of React Fiber?

### What is Reconcillation in React?

### Is it possible to use React without rendering HTML?

### What are the difference between React & React Native?

- React is used to build the user interface for web applications, whereas React Native is used for developing mobile applications for Android & iOS.
- React utilizes HTML, CSS, and JavaScript to create interactive user interfaces, whereas React Native utilizes APIs and native UI components to build mobile applications.
- React used a virtual DOM to render browser code, whereas React Native uses Native API to render components for mobile applications.

### What is GraphQL?

### How to use GraphQL in React?

### How can you implement Authentication in a React application?

### What is the use of React Profiler?

### How can you Optimize Performance in a React application?

### Explain Reactive Programming with example?

### In how many ways can we implement Reactive Programming in React?

### How to Fix Memory Leaks in ReactJS?

### How to the Secure React App?

### How to pass data from child component to parent component in React?

## ⚡Redux

### What is Redux?

### What is the role of Redux in React & why is it use?

### How many ways to use Redux in React?

### When to use Hooks and when to use Redux in React application?

### What is the Flow of data in React while using Redux?

### How to install Redux for React application?

### What are Action Creators in React Redux?

### Difference between Action Creators, Action Object & Action Type?

### Explain React Component Structure while using Redux?

### What is the role of Store in React Redux?

### What is the role of Reducer in Redux?

### Explain the Core Principles of Redux?

### List 5 benifits of using Redux in React?

### What are the challenges or disadvantages while using Redux?

### What is Provider Component in Redux?

### What is the role of Connect function in React-Redux?

### What are the 4 important files in React-Redux project?

### How to structure the project and maintain state in multiple components?

### Explain the concept of immutability in the context of Redux?

### Typical properties of an Action object in React-Redux project?

### Difference between mapDispatchToProps & mapStateTpProps in the connect?

### What is the meaning of Unidirectional Data Flow in Redux?

### How does Redux handle communication between components?

### What is the difference between Redux Core & Redux Toolkit?

### Explain the concept of Middleware in React-Redux?

### What is Redux Thunk?

### Why do we use Redux Thunk and Saga?

### Difference between Regular Action creator & Thunk action creator?

### How can you handle Asynchronous Operations & side-effect in React-Redux?

### How does Error Handling work in Redux?

### What is the difference between Flux & Redux?

## 💡TypeScript

### What is TypeScript?
