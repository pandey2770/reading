# ES6 Features

## Fat arrow function

Prior to ES6 we wrote functions in js as below:
```
var hello = function() {
    return 'Hello World'
}
```
Now in ES6 we write functions in js as below:
```
const hello = () => 'Hello World';
```
For functione with single statement there is no need to use curly brackets `{}` and no need to use brackets `()` if function has only one parameter. In case we do not use brackets `{}` value of the single statement is the return value of the function.

Very importantly `this` for fat arrow functions is lexically bind thus there is no need to explicitly binding of `this`.