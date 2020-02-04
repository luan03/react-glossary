# React Glossary
An introduction to terminology in react/react native.

**JSX** is a syntax extension to JavaScript. It is similar to a template language, but it has full power of JavaScript. JSX gets compiled to React.createElement() calls which return plain JavaScript objects called “React elements”. 

**Components** React components are small, reusable pieces of code that return a React element to be rendered to the page.

**props** are inputs to a React component. They are data passed down from a parent component to a child component.

**state** A component needs state when some data associated with it changes over time.

**Lifecycle Methods** are custom functionality that gets executed during the different phases of a component. There are methods available when the component gets created and inserted into the DOM (mounting), when the component updates, and when the component gets unmounted or removed from the DOM.

**Keys** A “key” is a special string attribute you need to include when creating arrays of elements. Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside an array to give the elements a stable identity.

**Events** Handling events with React elements has some syntactic differences: React event handlers are named using camelCase, rather than lowercase. With JSX you pass a function as the event handler, rather than a string.

**Expo** is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

**Hooks** are a new addition in React 16.8. They let you use state and other React features without writing a class.



Contributors: @luan03
