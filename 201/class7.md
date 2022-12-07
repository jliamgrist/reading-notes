# Object-Oriented Programming, HTML Tables

## Domain Modeling

[Code Fellows domain-modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

Domain modeling is essential for object-oriented programing. I should start by identifying precisely what kind of problem I'm trying to solve and creating an abstract model that represents this problem. Once that is done, small self-contained objects with the same attributes and behaviors can be built to model single entities which may have many instances. The attributes should be modeled with a constructor function defining and initializing the properties while the behaviors can be modeled with accepted methods. This allows for the creation of new object instances via use of ‘new’ keyword followed by a call to a constructor function; subsequent storage of this newly created object in a variable will also enable access to its properties and methods from outside. 

## Tables

Tables should be used for tabular data, not for representing the entire website. We now have CSS to make a website pretty, accessible, mobile-responsive, and easily managed using tags. 

Table semantics are:

`<th>` = table header
`<tr>` = table row
`<td>` = table cell

## Constructors

Using an object literal is easy to create one object, but if we want to create several objects, we want to use a constructor. A constructor is a function with the "new" keyword, which allows us to crete new objects, using the shape (properties) of the object we want. 

We can use "this" to refer to "this" in our constructor code, instead of the single object. 


## Object Prototypes Using A Constructor

Prototypes are a way to attach to a constructor methods that are inherited. They are objects that get attached to a constructor.
Prototype === "inherits".
We can use prototypes to share methods across objects. 
If I was a barista at a cafe, each latte I create is an object. I can use a prototype to calculate, based on for example how hot it is outside, how much coffee i should use for each grind. 

We can add methods to the constructor function's prototype, which allows us to share methods across all instances of a function.

## Things I want to learn more about

I am excited to see how to use a form to fill and object's properties and instantiate a new object.