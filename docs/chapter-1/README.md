# React coding conventions
...

## React / JSX / JS

* React and JSX style guide https://github.com/airbnb/javascript/tree/master/react

* Use 'react-require' plugin which helps to include React automatically, below example
```js
import { Component } from 'react';
export default class SomeComponent extends Component { ... }
```

* Declaration let and const (see JS conventions https://tracker.moneypark.ch/projects/mmp/wiki/Coding_conventions).
There should be just one variable declaration for all variables in the function.
That declaration typically appears at the top of the function. 
```js
// correct code
function foo() {
    let qux,
        norf;
    const bar = true,
        baz = false;
}
```

...
