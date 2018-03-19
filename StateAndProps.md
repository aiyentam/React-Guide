## State & Props

### What is State?

State is local to the component, and is mutable.

### What is Props?

Props is short for "properties". Props is passed into the component and is immutable.

### State vs Props

#### State

```javascript
class Hello extends React.Component {
  constructor() {
    super();
    this.state = {
      name: "",
      age: ""
    };
  }
...
```

#### Props

```javascript
class Hello extends React.Component {
  constructor(props) {
    super(props);
  }
...
```
