# React Glossary
An introduction to terminology in react/react native.

**JSX** is a syntax extension to JavaScript. It is similar to a template language, but it has full power of JavaScript. JSX gets compiled to React.createElement() calls which return plain JavaScript objects called “React elements”. 

**components** React components are small, reusable pieces of code that return a React element to be rendered to the page.

**pure Component**  is similar to the familiar React.Component except that PureComponent implements a “shallow prop and state comparison in shouldComponentUpdate()”. Using “Component” expects the user to perform the shouldComponentUpdate() manually to optimize updating if and when necessary.

**functional components** Functional components are declared with a function that then returns some JSX.

**class-based components** Class-based components are declared using ES6 classes. They are also known as "stateful" components, because their state can hold values throughout the component and can be passed to child components through props.

**styled Components** is a library for writing CSS components in JavaScript, also called CSS-in-JS. This allows the use of variables, which can be passed into the ‘styled component’ as a prop or directly imported as a constant. Styled Components can be included in the same file as the React component itself

**props** are inputs to a React component. They are data passed down from a parent component to a child component.

**state** A component needs state when some data associated with it changes over time.

**lifecycle Methods** are custom functionality that gets executed during the different phases of a component. There are methods available when the component gets created and inserted into the DOM (mounting), when the component updates, and when the component gets unmounted or removed from the DOM.

**keys** A “key” is a special string attribute you need to include when creating arrays of elements. Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside an array to give the elements a stable identity.

**events** Handling events with React elements has some syntactic differences: React event handlers are named using camelCase, rather than lowercase. With JSX you pass a function as the event handler, rather than a string.

**virtual DOM** Another notable feature is the use of a virtual Document Object Model, or virtual DOM. React creates an in-memory data-structure cache, computes the resulting differences, and then updates the browser's displayed DOM efficiently. This allows the programmer to write code as if the entire page is rendered on each change, while the React libraries only render subcomponents that actually change.

**expo** is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

**hooks** are a new addition in React 16.8. They let you use state and other React features without writing a class.

**flux architecture**  represents an alternative to the popular model-view-controller architecture. Flux features actions which are sent through a central dispatcher to a store, and changes to the store are propagated back to the view. When used with React, this propagation is accomplished through component properties.

**redux** When creating a React application, it is likely that you will need to share state between components. One way to do this is to pass the state into a child component as a prop, however this gets messy quickly when introducing more states to pass and more layers of components.

**redux Saga** If you are using Redux and you need to use asynchronous actions (ie.fetching an API, chaining actions), you will want to use some type of middleware to handle this. Redux Saga is a middleware that can intercept a Redux Action and carry out logic asynchronously based on the outcome of the api call.

**bridge** In the current architecture of React Native, the communication between JavaScript and Java/ObjC happens over “the bridge”.

**javaScript Interface (JSI)** Instead of using the bridge for queuing messages, the new architecture allows us to directly “invoke” (think RPC) Java/ObjC methods.

Contributors: @luan03
