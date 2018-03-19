### Component Lifecycle

#### What is the lifecycle methods and why do we need them you ask?

Lifecycle methods help repeat our actions in a specfic order.

#### Lifecycle Methods

##### Mounting

(initialization)
.._ componentWillMount
.._ render
..\* componentDidMount

```javascript
componenWillMount();
```

```javascript
render();
```

```javascript
componenDidMount();
```

##### Updating

.._ componentWillReceiveProps
.._ shouldComponentUpdate
.._ componentWillUpdate
.._ render
..\* componentDidUpdate

```javascript
componentWillReceiveProps();
```

```javascript
shouldComponentUpdate();
```

```javascript
componentWillUpdate();
```

```javascript
render();
```

```javascript
componentDidUpdate();
```

##### Unmounting

..\* componentWillUnmount

```javascript
componenWillUnmount();
```
