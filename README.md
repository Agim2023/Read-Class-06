# Read-Class-06

## JavaScript Object Basics

#### 1. How would you describe an object to a non-technical friend you grew up with?

    ~An object is a collection of related data and/or functionality. It usually consist of several variables and functions.
    
#### 2. What are some advantages to creating object literals?

    ~convenience, flexibility in declaration, and less code during declaration.
    
#### 3. How do objects differ from arrays?

    ~Objects represent a special data type that is mutable and can be used to store a collection of data. Arrays are a special type of variable that is also mutable and      can also be used to store a list of values.
    
#### 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

    ~person["number"];
     person["name"]["first"];
     
#### 5.Evaluate the code below. What does the term this refer to and what is the advantage to using this?

    ~const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

    ~this term is called constructors, which it refers to create a code for each single object. this is a quicker way to sum up all the objects together, create a          empty object, initialize it, and return it.
    
    ## Introduction To The DOM
    
#### 1. What is the DOM?

    ~The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.
    
#### 2. Briefly describe the relationship between the DOM and JavaScript.

    ~The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and      their component parts. The DOM is more independent than JavaScript, but is written in JavaScript.
