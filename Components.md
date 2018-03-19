## Components

Components help split up the sections of UI independently, allowing the code for each section to be reused without typing long codes.

Ex:
Each box is a component, the colors represent the same components.

![component](https://i.stack.imgur.com/SrjVR.png "Component")

Code Example of a Component:

```javascript
import React, { Component } from "react";

class Hello extends Component {
  render() {
    return <div />;
  }
}

export default Hello;
```
