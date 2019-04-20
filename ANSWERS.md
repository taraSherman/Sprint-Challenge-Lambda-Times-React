- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes are a form of data validation. Without some form of type checking, we run into the risk of passing in a wrong data type to a component, which could cause a crash or some unexpected behavior in the application. Using PropTypes, the props and types required by a component are defined so that any incorrect datatype passed to the component would throw an error on the console, so that it is caught during development.

- [ ] Describe a life-cycle event in React?

Lifecycle events are the methods used on components that allow you to update the UI and application states. There are three phases:
Mounting: Creation of a component and insertion of it into the DOM.

Updating: Re-rendering of a component any time it is updated or state changes.

Unmounting: the end of the lifecycle, when the component is being removed from the DOM.

- [ ] Explain the details of a Higher Order Component?

A Higher Order Component is a function that accepts a component as an argument and returns a component, allowing for sharing of the same functionality across multipple components.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

Inline styling: Good for just adding a few very simple style properties

Style-component: For re-using the style properties in the same file

CSS stylesheets: For more complex applications