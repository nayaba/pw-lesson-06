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

- **Equal (`==`)** and **Strictly Equal (`===`)**: Is this the same as that?

  ```javascript
  let a = '5';
  let b = 5;
  
  console.log(a == b); // true, because it's 'loose' and only checks value
  console.log(a === b); // false, because it's 'strict' and checks value and type
  ```

- **Not Equal (`!=`)** and **Strictly Not Equal (`!==`)**: This is the opposite of equal.

  ```javascript
  let c = 10;
  let d = '10';
  
  console.log(c != d); // false, because c and d have the same value
  console.log(c !== d); // true, because they are of different types
  ```

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
  
  console.log(isWeekend || isVacation); //
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
