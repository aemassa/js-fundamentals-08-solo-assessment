![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Assessment for JavaScript Fundamentals

You have 20 minutes

## Instructions

Fork, clone, and npm install.

Follow the prompts below and complete each question.  You may use any resource, other than someone else in the classroom, to help you complete this assessment.

You should save your answers in this README.md file.

# Question 1

```js
var a = 2;
var b = 3;
a = b;
```

After this code executes, what are the values of a and b? Please explain your answer.

The value of a is 3 and the value of b is 3. We set b = 3, and when we ran a = b, the value of a changed to 3.

## Question 2

```js
var c = 5;
var d = 2;
c = c + d;
```

After this code executes, what is the value of c?  Please explain what the last line of this program `c = c + d;` means.

c = 7.  c = c + d adds c and d (5 and 2) and assigns that value to c.

## Question 3

```js
var x = 4;
var y = 3;
x = y;
y = 10;
```

After this code executes, what are the values of x and y?  Please explain your answer.

x = 3 and y = 10. When we ran x = y, the value of x was set to 3. When we ran y = 10, the value of y was set to 10.

## Question 4

```js
var weather;
weather = "sunny";
weather === "sunny";
```

What are the values of these expressions?  Explain your answers.

var weather evaluates to 'undefined'.
weather = sunny evaluates to 'sunny'.
weather === "sunny" evaluates to 'true'.

## Question 5

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi >= 3) {
  console.log("sushi is delicious");
}

if (x > 0) {
  console.log("sushi is tasty");
}
```

Imagine that you take the code from this question, save it to a file called `food.js`, and run `node food.js` in your Terminal.

What would be the output? Explain your answer.

I ran this as-is as a test and received an error that x is not defined. This is what I was expecting, as we did not define the variable 'x'. If we define x and set a value to it (for example x =2 or x = howMuchILikeSushi), the output would be "sushi is tasty".

## Question 6

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi > 0) {
  console.log("sushi is tasty");
} else if (x >= 3) {
  console.log("sushi is delicious");
} else {
  console.log("I don't like sushi");
}
```

Imagine that you take the code from this question, save it to a file called `sushi.js`, and run `node sushi.js` in your Terminal.

What would be the output? Explain your answer.

The output would be "sushi is tasty" because we set howMuchILikeSushi equal to 2, and 2 is greater than 0. x is still undefined.

## Question 7

```js
//We'll learn about require later in the course
var ask = require('./ask.js');

var answer = 'not empty';

while (answer !== '' && answer !== 'SeCrEt') {
  answer = ask("Guess my secret? ");
}
```

Imagine that you take the code from this question, save it to a file called `name.js`, and run `node name.js` in your Terminal.

What would you have to type to exit the while loop?  Explain your answer.

To exit the while loop and stop receiving the "Guess my secret?" message, I would need to either type 'SeCrEt' (capitalizing every other letter), or submit a blank message (by either hitting enter right away without typing anything, or by typing a space and then hitting enter). The loop only executes as long as my answer is not empty or my answer is 'SeCrEt'.

---

Commit and push your changes.

Submit a pull request.
