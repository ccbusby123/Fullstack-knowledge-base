//Arrays and Object Types

Array of Strings
  let hobbies: string[];
  hobbies = ['Sports', 'Cooking']

A type defining an object
  let person: {
    name: string;
    age: number;
  }  

  the above defines this object:
  person = {
    name: 'Max',
    age: 32
  }

  the below does not match the defining object above:
    person = {
      isEmployee: true
    }

  An combination of string and array of objects
    let person: {
    name: string;
    age: number;
  }[];
