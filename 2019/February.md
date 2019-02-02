# February 2019

## 2/2/2019

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

## 1/2/2019

I've updated the [bars.js](https://github.com/jhancock532/bars.js) GitHub repository!

It includes full documentation of the functions / attributes of the library in its GitHub wiki.
