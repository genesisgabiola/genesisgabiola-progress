# The 10 Days of JavaScript: The Language Itself

## Day 1: Getting Started

- JavaScript is bigger than the web browser.
- **String** is a text like name, word, sentence or even paragraph wrap in a single (`'`) or double (`"`) quotes.
- **Variable** is a technical name where we store the value.

For now, focus on the equal sign, quotes, periods, and mathematical symbols because those are the skeleton in the core of the javaScript language itself.

It's the aspect that never changes regardless of environment.


## Day 2: Functions

### What is a function?

- **Function** is an action words, in English a function would be a verb.
- To call a function you simple type the name of the action/function including a bit of data inside the pair of parentheses.
- **Argument** is a technical name for a piece of data that we pass along.
- To create a function, we can start with function word then a space and then our own function name with a parentheses after that we include a pair of curly brackets.
- **Parameter** is a variable name inside the function definition.


## Day 3: Objects

### Why we would use objects?

- We would use objects to write a code to see that there is a relationship between the variables/functions.

### What is an object?

- **Object** is a container so we can store whatever we want inside it. It contains properties and methods.
- **Property** is a variable inside the object.
- To add another property we need to separate them with a comma (`,`).
- To access the property value of an object, we call the object name then dot (`.`) then the name of the property.
- **Method** is the technical name we use for a function inside an object.
- Browsers `document` object is one of the most useful objects.
- `document` object represents the webpage as a whole meaning it contains all sorts of properties and methods.
- `document` object has a method named `addEventListener` that accepts two (2) arguments, an event keyword and a function that we want to run everytime this event happens.

**Note**: Don't include a pair of parentheses right after the function name inside the `addEventListener` so we won't run, call or execute the function right away. Instead we are just passing along the name/reference to the function and it's up to the web browsers `addEventListener` method to know when to call this function.


## Day 4: Arrays

### What is an array?

- **Array** is a collection made up of multiple items.
- A pair of square brackets (`[]`) is how you create an array, inside the brackets we can include multiple values.
- An **array** is actually just a special type of object that has access to its own abilities or methods.
- **Arrays** in JavaScript are zero based, we start counting at zero (0) instead of one (1).
- `push` is a one of the method to add an item at the end of an array.
- `console.log` and anything we include inside parentheses will get output or logged to the console of the browser.
- `toUpperCase` method to capitalized all the letters.
- `toFixed` method is to round the numbers to the nearest whole number.
- Different types of data have access to different abilities or methods.
- `splice` method lets us remove a particular item from an array, accepts two (2) arguments, first the index of the item you want to remove, then how many items you want to remove starting from that index.

### Why arrays are so important?

- In addition to adding and removing items from an array, it's also very easy to sort an array alphabetically, quality or the most important of all.


## Day 5: Making Decisions

Computer programming uses `if` statements or similar conditional logic everywhere.

- `else` statements are optional it's just a fall back, if the first condition is not true then the `else` will happen.
- the area inside the parentheses is called a condition, which result to a value of either `true` or `false`.
- greater than (`>`), less than (`<`), less than or equal to (`<=`), greater than or equal to (`>=`), equal to `==`, not equal to (`!=`)
- Any number larger than zero, `true`, string with any content will be interpreted as `true`.
- `while` loop will repeat itself as long as the conditional value is true.


## Day 6: Higher-Order Functions

### What is a higher order function?

A higher-order functions is a function that either:

- Accepts a function as an argument
- Return a function

Learn about the useful higher-order functions that are part of the language itself (and not just web browser jargon).

- `addEventListener` method is a higher-order function because the second argument it expects to receive is a function.
- some programming languages are _not_ allowed to pass a function as an argument
- `forEach` method that accepts a function as an argument, and will run that function once for each item in the collection.


## Day 7: Returning vs Mutating

- Mutating just means changing or modifying the original array
- `map` method is a higher-order function that accepts a function as an argument
  - it will call the selected function once for each item in the array
  - it does not mutate or change the array that you call it from, it simply returns a new array
- `filter` method is very similar to `map` method a higher-order function
  - it doesn't change or mutate the array we call it from, it simply returns a brand new array
  - it call the function once for each item in the array
  - difference with map, is doesn't specify exactly what should get added to the new array, instead we simply return `true` or `false`


## Day 8: Scope & Context

**Scope** is the biggest source of confusion regarding **variables**.

- `let` statement creates a variable within the current local scope, and it doesn't matter if that identifier or label name has been used in outer scope
- remove the `let` keyword to update, mutate or change the value of the global scoped variable
- scope moves in one direction, one way street inside code can reach outwards for variables but outside cannot reach inside for variables
- biggest difference between `var` and `let` is _block_ and _function_ scope
- `let` uses _block_ scope, whereas `var` uses _function_ scope
- almost all other programming languages use _block_ scope instead of _function_ scope to less confusing code and problems overall

**Context** is the biggest source of confusion regarding **object**.

- `this` keyword points towards the _object_ that is _executing_ the current function
  - keyword changes depending on the context
- `Window` in the web browser is that root or global object, which contains all of the web browsers other objects
- `call` method can be access from functions, to make the `this` keyword point towards the selected object


## Day 9: Misc. Must Know Info

### Anonymous functions

- can be use when you know that you will only use it once, because it has no name and you have no way of referencing/calling it in your code

### Arrow function

- is a special type of function that uses alternate, cleaner or more minimalistic syntax
- first feature is that when the body of a function sits on a single line, it will automatically return whatever we include in it
- if you more than one parameters or you dont have parameter leave a parantheses, but if you only have one parameter remove the parentheses
- second feature is that they do not have their own new `this` keyword the way that a regular function does, and arrow function use the same variable lookup strategy
- do not change the value of the `this` keyword, whatever the `this` keyword was point in your current context that's still what is going to be pointing towards even inside of your function

### Function hoisting

- **function declaration** is where we use the keyword function with a name, this can be hoisted meaning ordering doesn't matter
- unless you create a function with the actual keyword function and then a name, your function is not going to get hoisted
- **Anonymous function** ordering matters, make sure to create the function first before calling it

### Template literals

- uses backticks (`) to wrap the string of text instead of regular quotes
- to add an expressions or get the value of a variable in a template literal use a dollar sign (`$`) then curly braces (`{}`), put the expressions or variables inside the braces, e.g, `${myVar}`

### Semicolons

- Semicolons is like a period to end a javaScript sentence
- JavaScript language has automatic semicolon insertion, meaning it will automatically add semicolons
- as long as keep organized with line breaks and whitespace we don't need to add semicolon manually


## Day 10: Web Browser Practice

Building To-Do App...
