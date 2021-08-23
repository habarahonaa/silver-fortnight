# silver-fortnight

## What Is React?

React is a declarative, efficient, and flexible **JavaScript library** for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

We use **components to tell React what we want to see on the screen.** When our data changes, React will efficiently update and re-render our components.

A component takes in **parameters**, called **props (short for “properties”)**, and returns a hierarchy of views to display via the render method.

The render method returns a description of what you want to see on the screen. **React takes the description and displays the result. In particular, render returns a React element, which is a lightweight description of what to render.** Most React developers use a special syntax called “JSX” which makes these structures easier to write. The `<div />` syntax is transformed at *build time* to `React.createElement('div')`.

JSX comes with the full power of JavaScript. You can put any JavaScript expressions within braces inside JSX. Each React element is a JavaScript object that you can store in a variable or pass around in your program.
