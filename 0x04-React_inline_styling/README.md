# React inline styling
React inline styling refers to the practice of applying CSS styles directly to React elements using the style attribute. Instead of using external stylesheets or CSS modules, you define your styles as a JavaScript object and pass it to the style attribute of a React component. This method allows for dynamic styling based on component state or props. Here's a basic example:
```
function MyComponent() {
  const style = {
    color: 'blue',
    backgroundColor: 'lightgray',
  };

  return <div style={style}>Hello, World!</div>;
}
```
In this example, style is a JavaScript object with CSS properties as keys (in camelCase instead of kebab-case) and their values as the object's values. This object is then passed to the style attribute of a div element.