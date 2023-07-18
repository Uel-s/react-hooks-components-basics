# React Components Basics

Components are the heart of React.

> Components - let you split the UI into independent, reusable pieces, and think about each piece in isolation.

> Components -contain a snippet of code that describes what they should render to the DOM.

## React Application Idea

1. `npm install` command to install all the
dependencies 

 2. `npm start` command to run the app.

 ## Naming Components

 Name of the component always starts with a Capital letter.

 - It helps React developers to easily differentiate between regular JavaScriptfunctions and React components.
 
- More importantly, it's a [rule that we must follow][component capitalization]in order for React to render our components correctly.

## A Note on Classes

In components we use the syntax **function** components and **class**
components.

1. functions

```jsx
function Comment() {
  return <div>Naturally, I agree with this article.</div>;
}
```

Or using the arrow function syntax:

```jsx
const Comment = () => <div>Naturally, I agree with this article.</div>;
```

2. Class

```jsx
class Comment extends React.Component {
  render() {
    return <div>Naturally, I agree with this article.</div>;
  }
}
```

