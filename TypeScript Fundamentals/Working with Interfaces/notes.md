//Interfaces

Interfaces in TypeScript provide a way to define the structure of objects, enforce a contract, and enable type checking. They are a fundamental feature for writing type-safe, maintainable code, especially when dealing with complex data and object relationships.

1. Uses the interface key word.

  interface Person {
  name: string;
  age: number;
}

2. Implements an interface
You can use an interface to describe the shape of an object. When a class or object literal adheres to the structure defined by an interface, you say that it "implements" the interface.

  class Student implements Person {
    constructor(public name: string, public age: number) {}
  }
  const john: Person = new Student("John", 25);

3. Type Checking
Interfaces provide type checking at compile time. If an object or class doesn't have all the properties specified in the interface, TypeScript will generate a compilation error.

  const jane: Person = { name: "Jane" }; // Error: Property 'age' is missing.

4. Optional properties:

You can make properties optional in an interface by using a ? after the property name.

  interface Car {
    make: string;
    model?: string; // Model is optional
  }




