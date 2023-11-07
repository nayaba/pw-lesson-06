<img src="https://github.com/nayaba/pw-lesson-06/assets/9198401/0ddc0dd3-e790-4458-b566-0a8e57bbdbb4" height="300 px" width="auto" />

Alright, let's roll up our sleeves and get our hands dirty with JavaScript operators. Operators are like the verbs of the language—they get things done. So, whether you're just starting or looking to refresh your memory, let's break it down as if we were learning to cook a new recipe.

### 1. Assignment Operators: Who Gets the Pie?

Assignment operators are all about giving values to variables. The most common one is the equals sign (`=`), which you've probably met already:

```javascript
let myLunch = "pizza"; // "=" assigns the value "pizza" to the variable myLunch
```

But there are others, like `+=` and `-=`, which do a bit more. They change the variable's value by adding or subtracting from it:

```javascript
let slicesOfPizza = 8;
slicesOfPizza -= 2; // You just ate 2 slices, 6 are left now.
```

There are also `*=`, `/=`, and `%=` for multiplication, division, and remainder operations.

### 2. Arithmetic Operators: Let's Do Some Math

Now, if assignment operators are about giving, arithmetic operators are all about math:

- **Addition (`+`)**: Adds two numbers or concatenates strings.
  
  ```javascript
  let dough = 5;
  let toppings = 2;
  let pizza = dough + toppings; // pizza now equals 7
  ```

- **Subtraction (`-`)**: Finds the difference between numbers.
  
  ```javascript
  let fullPizza = 8;
  let eatenSlices = 3;
  let remainingPizza = fullPizza - eatenSlices; // remainingPizza equals 5
  ```

- **Multiplication (`*`)** and **Division (`/`)**: They do exactly what you think they do.
  
  ```javascript
  let doubleBatch = dough * 2; // doubleBatch equals 10
  let halfBatch = dough / 2; // halfBatch equals 2.5
  ```

- **Modulus (`%`)**: This one might be new. It gives you the remainder of a division.
  
  ```javascript
  let unevenSlices = 14;
  let people = 3;
  let leftoverSlices = unevenSlices % people; // leftoverSlices equals 2
  ```

- **Increment (`++`)** and **Decrement (`--`)**: These add or subtract 1 from the number.

  ```javascript
  let likes = 0;
  likes++; // likes is now 1
  likes--; // back to 0
  ```

### 3. Comparison Operators: Picking Favorites

Comparison operators are the judgmental part of JavaScript. They compare two values and return a boolean (`true` or `false`):

- **Comparing Numbers with Strict Equality**

When you're dealing with numbers in JavaScript and you want to check for equality, `===` is your go-to operator:

```javascript
let num1 = 10;
let num2 = 10;

console.log(num1 === num2);  // Outputs: true, because the values and types are the same

let num3 = 10;
let num4 = 20;

console.log(num3 === num4);  // Outputs: false, because the values are different
```

And when you want to ensure that two numbers are not the same, `!==` steps in:

```javascript
let num5 = 15;
let num6 = 20;

console.log(num5 !== num6);  // Outputs: true, because the numbers are not the same
```

- **Comparing Strings with Strict Equality**

Comparing strings strictly is similar to comparing numbers—you're checking both the value and the type:

```javascript
let greeting1 = 'Hello';
let greeting2 = 'Hello';

console.log(greeting1 === greeting2);  // Outputs: true, because the strings are identical

let greeting3 = 'Hello';
let greeting4 = 'hello';  // Note the lowercase 'h'

console.log(greeting3 === greeting4);  // Outputs: false, because the strings are not identical (case-sensitive)
```

For strict non-equality, we use `!==` to determine if two strings are not identical, which includes any differences in characters or case:

```javascript
let food1 = 'Apple';
let food2 = 'apple';  // Notice the uppercase 'A' and lowercase 'a'

console.log(food1 !== food2);  // Outputs: true, because the case of the first letters is different

let food3 = 'Apple';
let food4 = 'Banana';

console.log(food3 !== food4);  // Outputs: true, because the strings are not the same
```

- **Strict Comparisons with Type-Checking**

Strict comparison takes the type of variable into account.

```javascript
let a = '5';
let b = 5;

console.log(a === b); // Outputs: false, because STRING '5' is not the same type as NUMBER 5
```

In this case, `a` is a string and `b` is a number. Even though they look similar, they are different types to JavaScript.

The opposite, strictly not equal `!==`, confirms non-identity:

```javascript
let c = 10;
let d = '10';

console.log(c !== d); // Outputs: true, because a NUMBER is not the same type as a STRING
```

Here `c` and `d` have the same value if you squint, but one's in quotes (a string) and one's not (a number). This means they're not the same in the eyes of JavaScript.

Understanding comparison operators with both numbers and strings, as well as strict type comparisons, is key to writing precise and bug-free conditions in your code.

- **Greater than (`>`)**, **Less than (`<`)**, **Greater than or equal to (`>=`)**, **Less than or equal to (`<=`)**: These are your classic greater and less than signs from math class.

  ```javascript
  let highScore = 50;
  let myScore = 30;
  
  console.log(myScore > highScore); // false
  console.log(myScore < highScore); // true
  console.log(myScore >= 30); // true
  console.log(myScore <= 29); // false
  ```

### 4. Logical Operators: Making Choices

Logical operators are how you make decisions in your code. You have three main ones:

- **AND (`&&`)**: Are both conditions true?
  
  ```javascript
  let isHungry = true;
  let isLunchTime = true;
  
  console.log(isHungry && isLunchTime); // true, time to eat!
  ```

- **OR (`||`)**: Is at least one condition true?
  
  ```javascript
  let isWeekend = false;
  let isVacation = true;
  
  console.log(isWeekend || isVacation); // true, because isVacation is true
  ```


### 5. String Operators

The plus operator (`+`) is _also_ used to concatenate strings:

```javascript
let firstName = "John";
let lastName = "Doe";
let fullName = firstName + " " + lastName; // equals "John Doe"
```


### Wrap-Up and Practice Task

That's a lot, I know! But these operators are the building blocks for making decisions and calculations in your code. Now for a quick practice task: using CodePen create a simple program that uses different operators to calculate the result of a math problem, compare two values, and concatenate some strings. Here's an example to get you started:

```javascript
let num1 = 10;
let num2 = 5;
let mathResult = num1 * num2;

let areEqual = num1 == num2;
let joinedWords = "Hello, " + "World!";

console.log("The result is: " + mathResult);
console.log("Are the numbers equal? " + areEqual);
console.log(joinedWords);
```

Play around with these concepts and see what you can come up with. Remember, the more you use them, the more intuitive they'll become. Happy coding!

[Back to the Wiki](https://github.com/nayaba/pw-wiki)
