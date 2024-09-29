# Operators

## Assignment Operators

### Assign `=`

>     age = 25;

Assign number 25 to variable `age`.

### Add and assign `+=`

>     age += 5;
>
>     // same as above
>     age = age + 5;

Add 5 to the value of variable `age` and assign the result back to variable `age`.

### Substract and assign `-=`

>     age -= 10;
>
>     // same as above
>     age = age - 10;

Substract 10 from the value of variable `age` and assign the result back to variable `age`.

### Multiply and assign `*=`

>     age *= 2;
>
>     // same as above
>     age = age * 2;

Multiply the value of variable `age` by 2 and assign the result back to variable `age`.

### Divide and assign `/=`

>     age /= 2;
>
>     // same as above
>     age = age / 2;

Divide the value of variable `age` by 2 and assign the result back to variable `age`.

### Increment `++`

>       age++;
>
>       // same as above
>       age = age + 1;
>       age += 1;

Increment the value of variable `age` by 1.

### Decrement `--`

>       age--;
>
>       // same as above
>       age = age - 1;
>       age -= 1;

Decrement the value of variable `age` by 1.

# Functions

## Named functions

Named functions are defined with `function` keyword and function name.

>     function sum(a, b) {
>       return a + b;
>     }
>
>     sum(2, 3); // 5

In the definition above we have:
* `function` keyword
* function name `sum`
* function parameters between parantheses `(a, b)`
* function body between curly braces `{ ... }`

## Anonymous functions

Anonymous functions are defined with `function` keyword but without a function name.
Anonymous functions are usually assigned to a variable and can be invoked like a named function.

>     var sum = function(a, b) {
>       return a + b;
>     }
>
>     sum(2, 3); // 5

In the definition above we have:
* `function` keyword
* function parameters between parantheses `(a, b)`
* function body between curly braces `{ ... }`

## Arrow functions

Arrow functions are anonymous functions defined without the `function` keyword but with an arrow operator `=>` between arguments and function body.

>     var sum = (a, b) => {
>       return a + b;
>     }
>
>     sum(2, 3); // 5

In the definition above we have:
* function parameters between parantheses `(a, b)`
* arrow operator `=>`
* function body between curly braces `{ ... }`

### Arrow functions with concise body
If the arrow function body has only one instruction, `return`, then the curly braces and the `return` keyword can be ommited.

>     var sum = (a, b) => a + b;
>
>     sum(2, 3); // 5

In the definition above we have:
* function parameters between parantheses `(a, b)`
* arrow operator `=>`
* return expression `a + b`