# My Journey with React Hooks

When I first started working with React, everything revolved around class components and lifecycle methods. But then came **Hooks**, and everything changed.

---

## Introduction

React Hooks were introduced in version 16.8 and they completely changed how we write React code.

Instead of using class components for state and lifecycle methods, we can now use functions, making code easier to read and maintain.

---

## useState Example

Here’s how we used to manage state in class components:

```jsx
class Counter extends React.Component {
  state = { count: 0 };

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    return (
      <button onClick={this.increment}>
        Count: {this.state.count}
      </button>
    );
  }
}
```
