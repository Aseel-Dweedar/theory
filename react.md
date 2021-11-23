- **what is the difference between state and props?**

  e key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

  Props and state are related. The state of one component will often become the props of a child component. Props are passed to the child within the render method of the parent

- **what is HOCs?**

  " higher-order component " , a function that takes a component and returns a new component.

  `const EnhancedComponent = higherOrderComponent(WrappedComponent);`

  Whereas a component transforms props into UI, a higher-order component transforms a component into another component.

- **what is the difference between React Components, and Elements?**

  An element is a plain object describing what you want to appear on the screen. Once an element is created, it is never mutated.

  A component can be a class with a render() method. and can be defined as a function. In either case, it takes props as an input, and returns an element tree as the output.

- **what is the virtual DOM?**

  React creates a tree of custom objects representing a part of the DOM.

- **did the props changeable or not?**

  A component cannot update its own props unless they are arrays or objects (having a component update its own props even if possible is an anti-pattern), but can update its state and the props of its children.
