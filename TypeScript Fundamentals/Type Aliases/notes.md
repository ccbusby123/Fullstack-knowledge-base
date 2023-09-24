Using an alias is just way to create a new name for an existing type. Kind of like giving a nickname to a type so you don't have to use the full name every time you want to use it in code.

Use the type keyword. This is a TS keyword.

  This is the oringinal TS definition
  let person {
    name: string;
    age: number;
  }
  
  This is the alias definition
  type Person = (This is the type definition after the = sign){
    name: string;
    age: number;
  };

  let people: Person[]; - The alias can be used many different ways.