# How to use React

## Components

Components help split up the sections of UI independently, allowing the code for each section to be reused without typing long codes.

Ex:
Each box is a component, the colors represent the same components.

![component](https://i.stack.imgur.com/SrjVR.png "Component")

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

### Reusable Components

Back to the image for Components we have the components that are boxed with the same color.

That means we can use the same code without typing A LOT!
