Prompt:
What is a class in Java Script

In JavaScript, a class is a blueprint for creating objects with predefined properties and methods. It provides a way to define the structure and behavior of objects in a more organized and reusable manner.

Here's a basic example of how a class is defined in JavaScript:
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  greet() {
    console.log(`Hello, my name is ${this.name} and I'm ${this.age} years old.`);
  }
}

// Creating an instance of the Person class
const person1 = new Person('John', 30);
person1.greet(); // Output: Hello, my name is John and I'm 30 years old.
In this example:

Person is the class name.
constructor is a special method used for initializing objects created with the class. It gets called automatically when a new object is instantiated.
greet is a method defined within the class, which can be called on instances of the class.
Classes in JavaScript follow prototypal inheritance, which means that classes can inherit properties and methods from other classes, providing a way to create a hierarchy of objects with shared functionality.