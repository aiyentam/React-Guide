## Components

Components help split up the sections of UI independently, allowing the code for each section to be reused without typing long codes.

### Ex:

Each box is a component, the colors represent the one component.
Like these components:

```javascript
<DepartureBoard>
<Train />
```

![component](https://i.stack.imgur.com/SrjVR.png "Component")

### Code Example of a Component:

```javascript
import React, { Component } from "react";

class Hello extends Component {
  render() {
    return <div />;
  }
}

export default Hello;
```

### Using Multiple Components:

To use mulitple components, make sure each component file has react imported

```javascript
import React, { Component } from "react";
```

As well as export default.

```javascript
export default ComponetName;
```
