## State & Props

### What is State?

State is local to the component, and is mutable.

### What is Props?

Props is short for "properties". Props is passed into the component and is immutable.

### State vs Props

#### State

How State is being used..

```javascript
import React, { Component } from "react"

class Hello extends Component {
  constructor() {
    super();
    this.state = {
      name: "", //name is from state
      age: "" //age is from state
    };
  }
  render() {
    return(
      <div>
        <p>Hello my name is: {this.state.name}</p>
        <p>This year I am: {this.state.age}</p>
      </div>
    )
  }
}

export default Hello;
...
```

#### Props

How Props is being used..

```javascript
import React, { Component } from "react";

class App extends Component {
  constructor(props) {
    super(props);
    this.state = {
      title: "", //Title is from props
      author: "" //Author is from props
    };
  }
  render() {
    return (
      <div>
        <Hello authorProps={this.state.name} />
      </div>
    );
  }
}

export default App;
```
