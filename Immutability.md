# Immutability 

In object-oriented and functional programming an object whose state is created can, not be change again or modified. A much more useful explanation is to say that immutability is not about forbidding change at all. Instead immutability is more on how to handle change. Immutability is not about forbidding some kind of operations. You still can add an element to an array, the difference is that you just do it differently.
Example
In data
````
let x = 5
let y = 10
let z = x + y // 15
````
In String
````
let a = "foo"
let b = "bar"
let c = a + b // "foobar"

let foo1 = "foo1"
let foo2 = foo1.Replace('1', '2')
let foo  = foo2.Remove(3,1)
````