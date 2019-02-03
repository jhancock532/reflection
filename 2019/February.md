[Go back to the home page.](https://jhancock532.github.io/reflection/)

# February 2019

## 3/2/2019 - Learning JavaScript 9

Today I continued to learn the basics of JavaScript by following the tutorials at [javascript.info](https://javascript.info/).

A lot of reading, not much not taking of notes.
- [JavaScript Specials](https://javascript.info/javascript-specials)
  * Seven types in JavaScript - Number, String, Boolean, Object, Symbol, Undefined, Null
  * Null means that it doesn't exist, while undefined implies that it isn't yet assigned to.
  * `prompt(question, defaultAnswer); confirm(statement); alert(statement);`
  * This section is a pretty good summary of all the previous sections.
- [Debugging Chrome](https://javascript.info/debugging-chrome)
  * Chrome debugger has some super cool features, I should use it while developing JS.
  * I'm relying too much on console.log statements, when I could be using breakpoints.
- [Coding Style](https://javascript.info/coding-style)
  * I almost totally agree with the coding style specified in this post. Some interesting points include...
  * Don't nest too deep, it descreases code readability - use `return;` or `continue;` if necessary.
  * Use whitespace lines to organise code into logical blocks. I was kind of doing this, good to bring it to my awareness.
  * **Write your code first, then write the functions that make up the code.** This is so that the person reading the code understands the high level purpose and direction of the code before getting lost in the detail.
  * Use a linter. Just use a linter, it will save you so much effort.
  * It's kinda weird, but I've developed an eye for what good code looks like syntactically on my own, and it's essentially the same as what is advised in this guide. When considering the high level (ordering of functions, creating many functions, high level functions) I haven't developed this skill yet, and it's something that I'll have to work on personally...
  * What is good code? 
    - It is easy to read and understand. 
    - It is written in such a way that errors are avoided. 
- [Comments](https://javascript.info/comments)
  * The amount of comments in your code should be minimal, as the code should be understandable without them.
  * If the code is so unclear it requires a comment, then maybe it should be rewritten instead.
  * Good comments...
    - Explain the high level design or architecture of your code.
    - Explain the reasoning behind your solution strategy. Why this way?
    - Explain subtle features or counter intuitive code.
    - Follow JSDoc convention for commenting functions.
- [Ninja Code](https://javascript.info/ninja-code)
  * Please be sensible while coding. 
  * Stop using data or value when creating variable names. Think before you name!

[My notes](https://codepen.io/jhancock532/pen/yZXJKB?editors=0012) are there, but all items of interest are summerised above.

## 2/2/2019 - Learning JavaScript 8

Today I continued to learn the basics of JavaScript by following the tutorials at [javascript.info](https://javascript.info/).

The tutorials I read and made notes of include:
- [Function Basics](https://javascript.info/function-basics)
- [Function Expressions & Arrow Functions](https://javascript.info/function-expressions-arrows)

My notes can be found on [CodePen](https://codepen.io/jhancock532/pen/bzWjzP).

### Key Learning Points
- Parameters are in the function definition, arguements are the actual values that are passed.
- You can switch tabs in FireFox with the keyboard shortcut CTRL TAB.
- Variable shadowing - covering variables outside of your function by creating local varaibles with the same name.
- If a parameter is not provided on a function call, then it is automatically assigned the value of undefined.
- `function defaultParameterIfNoneGiven(text = "defaultValueForText") ...`
- A function with an empty return; or no return statement will return undefined.
- Use the return; statement to exit a function early.
- Start your function names with verbs, then a few words that concisely explains what it does.
- Self describing code, where functions are like comments. Function names start with verbs, and the function completes only one action.
- Alongside function declarations, there are also function expressions. Function declarations are hoisted, while expressions are only accessible after definition.
- Callback functions, or callbacks, are passed as arguments into functions.
- An anonymous functions has no name. 
- Arrow functions, or lambda functions, are basically function expressions, but only the parameters and the return expression is defined. 
- You can extend an arrow function with {}, for example `let sum = (a, b) => {return a+b};`
- Just for fun: `console.log((() => (0))());` Outputs 0.

## 1/2/2019 - bars.js on GitHub

I've updated the [bars.js](https://github.com/jhancock532/bars.js) GitHub repository!

It includes full documentation of the functions / attributes of the library in its GitHub wiki.

![A screenshot of bars.js documentation.](https://raw.githubusercontent.com/jhancock532/reflection/master/2019/february-images/1%20-%20bars.js%20documentation.PNG)
