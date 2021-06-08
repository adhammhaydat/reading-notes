# HTML Lists, Control Flow with JS, and the CSS Box Model

#### About HTML
1. Chapter 3: “Lists”
2. Chapter 13: “Boxes”

#### About Javascript
1. Chapter 2: “Basic JavaScript Instructions”
2. Chapter 4: “Decisions and Loops”

--------------------------------------------------
## chapter 3: "lists":

**Ordered lists** are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section number.

**Unordered lists** are lists that begin with a bullet point (rather than characters that indicate order).

**Definition lists** are made up of a set of terms along with the 
definitions for each of those terms.

**who we can make *orderer list* in html page**

this image showing us who we can do it

![ol](https://img1.wsimg.com/isteam/ip/265009b3-5e91-4c5c-b3a6-be62c43a8a5c/Ordered%20and%20Unordered%20list%20html.PNG)

**who we can make *unorderer list* in html page**

this image showing us who we can do it
![ul](https://www.wikitechy.com/step-by-step-html-tutorials/img/html-images/code-explanation-unordered-tag-in-html.png)

**who we can make *unorderer list* in html page**

this image showing us who we can do it

![def list](https://www.wikitechy.com/step-by-step-html-tutorials/img/html-images/code-explanation-definition-list-dl-tag-in-html.png)

--------------------------------------------------
## Chapter 13: “Boxes”
You can set several properties that affect the appearance of 
these boxes. In this chapter you will see how to:
* Control the dimensions of your boxes
* Create borders around boxes
* Set margins and padding for boxes
* Show and hide boxes.

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
![boxes](https://assets.codepen.io/839027/internal/screenshots/pens/yVaNrx.default.png?fit=cover&format=auto&ha=false&height=540&quality=75&v=2&version=1479326298&width=960)

Explanation of the different parts and who make boxes :

* **Content** - The content of the box, where text and images appear

* **Padding** - Clears an area around the content. The padding is transparent

* **Border** - A border that goes around the padding and content

* **Margin** - Clears an area outside the border. The margin is transparent.

The box model allows us to add a border around elements, and to define space between elements.

----------------------------------------------------------------------------------------------------

## Chapter 2: “Basic JavaScript Instructions”

A computer program is a list of "instructions" to be "executed" by a computer.

In a programming language, these programming instructions are called statements.

A JavaScript program is a list of programming statements.

**JavaScript statements are composed of:**

Values, Operators, Expressions, Keywords, and Comments.

### topics today
**USING QUOTES INSIDE A STRING** 

You can use a technique 
called escaping the quotation 
characters. This is done by 
using a backwards slash (or 
"backslash") before any type of 
quote mark that appears within 
a string.

**USING A VARIABLE TO STORE A BOOLEAN**

eg:

let a=true;

let b=false;

**SHORTHAND FOR CREATING VARIABLES**
Variables are declared and 
values assigned in the same 
statement

**CHANGING THE VALUE OF A VARIABLE**

if we have variabel it have any value and give it new value, that is mean change value

## Chapter 4: “Decisions and Loops”

### Loop

Loops are handy, if you want to run the same code over and over again, each time with a different value.

![loop](https://www.javascripttutorial.net/wp-content/uploads/2020/01/JavaScript-for-Loop.png)

**Different Kinds of Loops**

JavaScript supports different kinds of loops:

**for** - loops through a block of code a number of times

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

**for/in** - loops through the properties of an object

for (key in object) {
  // code block to be executed
}

**for/of** - loops through the values of an iterable object

for (variable of iterable) {
  // code block to be executed
}

**while** - loops through a block of code while a specified condition is true

while (condition) {
  // code block to be executed
}

**do/while** - also loops through a block of code while a specified condition is true

do {
  // code block to be executed
}
while (condition);


for more information click on [w3school](https://www.w3schools.com/)

