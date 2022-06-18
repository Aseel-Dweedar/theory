# React

- **React is Single Page Application, What dose it mean?** (YouApply interview)

  only load the application code (HTML, CSS, JavaScript) once. so when we move between pages it doesn't reload.

  [Single Web page](https://www.youtube.com/watch?v=Kg0Q_YaQ3Gk&t=318s)

- **what is the difference between state and props?**

  e key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

  Props and state are related. The state of one component will often become the props of a child component. Props are passed to the child within the render method of the parent

- **Is react a two way or one way data binding? if one how to pass props from child to parents component?** (YouApply interview)

  One way data binding, we can pass a data to parent by creating a method in the parent component and pass it to the child, and pass the data as a params to that method.

- **what is the difference between React Components, and Elements?**

  An element is a plain object describing what you want to appear on the screen. Once an element is created, it is never mutated.

  A component can be a class with a render() method. and can be defined as a function. In either case, it takes props as an input, and returns an element tree as the output.

- **Who is faster react or Angular? and why?**

  React is faster, because it depends on virtual Dom. not the real dom as Angular.

- **what is the virtual DOM?**

  React creates a tree of custom objects representing a part of the DOM.

- **did the props changeable or not?**

  A component cannot update its own props unless they are arrays or objects (having a component update its own props even if possible is an anti-pattern), but can update its state and the props of its children.

- **What happens when you make a setState ?**

  tells React that this component and its children need to be re-rendered with the updated state.

- **What is React Lifecycle?**

  https://www.w3schools.com/react/react_lifecycle.asp

- **What is React Hooks?**

  [React Hooks md](/img/react%20hooks/React-Hooks.md)

  https://reactjs.org/docs/hooks-intro.html

  - **what is HOCs?**

  " higher-order component " , a function that takes a component and returns a new component.

  `const EnhancedComponent = higherOrderComponent(WrappedComponent);`

  Whereas a component transforms props into UI, a higher-order component transforms a component into another component.

# React Native

- **what is the key difference between react and react native?**

  React is an open-source JS library for building the UIs for web applications; besides, React Native is used to build rich mobile UI from declarative components using only JavaScript.

- **What is the different ways to debug a react native app?** (Alwaseet interview)

  [Debugging](https://reactnative.dev/docs/debugging#:~:text=Select%20Tools%20%E2%86%92%20Developer%20Tools,for%20a%20better%20debugging%20experience)

- **how to optimize a flatlist in react native?** (Alwaseet interview)

  1. Avoid inline functions.
  2. Provide height value for every item.
  3. Keep component that renders the list item as light as possible.
  4. Use Pure Component or Memo.
  5. Use cached optimized images.

- **Give a way to dismiss the key board when touch the screen**

  We can use `<touchablewithoutfeedback>`