#  Class Inheritance and Prototypal 
`class inheritance` is a discription of the object to be created classes from classes and create subclass relationship hierarchical class taxonomies.
In javascript class inheritance is built on the top of ptorotypical inheritance.

`Prototypical` every javascrit object has a internal property called  prototype, some js implementations allows directy access to prototype. In js first you create an object and then you can argument your object and create new object from it. 
Example.
```
    var person = function(name){
        this.name=name;
    };
    person.prototype.getname = function(){
        return this.name; 
    };
    var newperson = new person('abhi');
    newperson.getname(); // will return 'abhi'
```
    


