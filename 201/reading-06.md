# Reading 6

## How would you describe an object to a non-technical friend you grew up with?

An object stores specific information about a specific idea.

## What are some advantages to creating object literals?

Objects let us store information the way humans think about real objects/things.

## How do objects differ from arrays?

Objects use key value pairs accessed by name, not position like arrays.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

You must use bracket notation when

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

Using 'this' allows the code to be flexible and reusable.

# Introduction To The DOM

## What is the DOM?

The Document Object Model, is how JavaScript "sees" the webpage.

## Briefly describe the relationship between the DOM and JavaScript.

JavaScript uses DOM to read the HTML, update styles and respond to user actions.