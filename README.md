# react-live-templates
React Live Templates for WebStorm(IntelliJ)

## rcls
React Component (ES6)

```javascript
import React, { Component, PropTypes } from 'react';

class $COMPONENT$ extends Component {
  render() {
    return (
      <div>$END$</div>
    );
  }
}

$COMPONENT$.propTypes = {};
$COMPONENT$.defaultProps = {};

export default $COMPONENT$;
```

## exp
Export the defaultly exported file with specific name

```javascript
export const $COMPONENT$ = require('./$COMPONENT$').default;
$END$
```

## reducer
Simple code that contains Redux action/reducer

```javascript
export const actions = {$END$};

export const defaultState = {};

export default (state = defaultState, action) => {
  switch (action.type) {
    default:
      return state;
  }
}
```

## act
Define key-value on Object literal

```javascript
$COMPONENT$: '$COMPONENT$',$END$
```

