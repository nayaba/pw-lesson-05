![js-love](https://github.com/nayaba/pw-lesson-05/assets/9198401/b870887c-15d3-40e4-a14d-65aacf0ae7f7)

Alright, let's talk about one of the building blocks of JavaScript (and really, any programming language): data types. You can think of data types like the different kinds of ingredients in a kitchen. Each one has its own purpose and use in recipes—or in our case, in code. So, let's get comfy and dive into the JavaScript pantry to see what we've got!

### 1. The Basics: Primitive Data Types

In JavaScript, we have a few basic (primitive) data types. These are the simplest forms of data.

#### String
Strings are the words of the language. Anything you want to treat as text needs to be a string. You make a string by wrapping some text up in quotes:

```javascript
let name = "Chewbacca";
console.log(name); // Outputs: Chewbacca
```

Strings can be anything: letters, numbers, spaces, symbols, you name it. If it's in quotes, it's a string.

#### Number
Numbers are your integers and decimals, no quotes needed. They're the math whizzes of data types:

```javascript
let age = 200; // No quotes means it's a number
let price = 19.99; // Yep, decimals are cool too
```

In JavaScript, there's no difference between integers and floats—they're all just 'number' types.

#### Boolean
Booleans are the yes-or-no, true-or-false, on-or-off of the data types. There are only two possible values:

```javascript
let isJedi = true;
let isSith = false;
```

They're super useful when you need to check if something should happen or not.

#### Undefined
`undefined` is a bit like the empty space in your cupboard. It means a variable has been declared but hasn't been given a value yet:

```javascript
let creature;
console.log(creature); // Outputs: undefined
```

#### Null
`null` is like intentionally placing an empty container in the cupboard. You know it's there, but it's deliberately empty:

```javascript
let theseArentTheDroids = null;
```

It represents "no value" and is used to intentionally signify "nothing."

#### Symbol
Symbols are unique and immutable data types, often used for object properties to give them a unique identifier, but they're a bit more advanced and not used as frequently as the others.

```javascript
let symbol = Symbol('unique');
```

### 2. A Bit More Complex: Non-Primitive Data Types

These are the data types that can store collections of values or more complex entities.

#### Object
Objects are like backpacks; they can store a bunch of different things at once. Each item in an object is stored as a key-value pair:

```javascript
let spaceship = {
  name: "Millennium Falcon",
  speed: "Fast",
  isFunctional: true
};

console.log(spaceship.name); // Outputs: Millennium Falcon
```

You can store different primitive data types in an object and access them with either dot notation or bracket notation.

#### Array
Arrays are lists, plain and simple. They can hold any data type, including other arrays. They're ordered, meaning the position of each item is important, and you can access them by an index:

```javascript
let jedi = ["Luke", "Obi-Wan", "Yoda"];
console.log(jedi[1]); // Outputs: Obi-Wan
```

Arrays in JavaScript are zero-indexed, which means counting starts at zero, not one.

### 3. Special Guests: Dynamic Typing

JavaScript is a dynamically typed language, which means variables can be reassigned to different data types:

```javascript
let mystery = "I'm a string";
mystery = 42; // Now I'm a number
```

This can be super flexible, but watch out—it can also lead to unexpected bugs if you're not careful.

### Practice Time!

Alright, now that you've met all the data types, let's play with them a bit. Go on, open up your text editor or a CodePen, and try creating variables with different data types. Play around with combining them, changing them, and see what happens. Here's a fun one to try:

```javascript
let force = "strong";
let midichlorianCount = 20000;
let isForceSensitive = midichlorianCount > 15000;

console.log("Is the force strong with this one? " + (isForceSensitive ? "Yes" : "No"));
```

See what happens when you change the values. What if `midichlorianCount` was `14000`?

Remember, the best way to learn is to code, make mistakes, debug, and code some more. Have fun with it, and may the data types be with you!

[Back to the Wiki](https://github.com/nayaba/pw-wiki)
