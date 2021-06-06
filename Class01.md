# HTML & CSS 
 **Design and Build Websites *Jon Ducket* **

 ### content:

| Chapter          | content         |
| -------------    | -------------   |
| Introduction     |Introduction     |
| Chapter 1        | Structure       |
| Chapter 8        | Extra Markup    |
| Chapter 17       | HTML5 Layou     |
| Chapter 18       | Process & Design|


---------------------------------------------
### Introduction:
####  About this book:

Many books that teach HTML and CSS 
resemble dull manuals. To make it easier for 
you to learn, we threw away the traditional 
template used by publishers and redesigned 
this book from scratch.

In this book it focussed 90% on coding; how we can write it and using it.
10% you can google it.

Understanding HTML and CSS 
can help anyone who works 
with the web; designers can 
create more attractive and 
usable sites, website editors can 
create better content, marketers 
can communicate with their 
audience more effectively, and 
managers can commission 
better sites and get the best out 
of their teams.


#### How the web works:

People access websites using 
software called **a web browser**. 
Popular examples include 
Firefox, Internet Explorer, Safari, 
Chrome, and Opera.

When you ask your browser for 
a web page, the request is sent 
across the Internet to a special 
computer known as  **a web 
server** which hosts the website.

Web servers are special 
computers that are constantly 
connected to the Internet, and 
are optimized to send web pages 
out to people who request them.

**Screen readers** are programs 
that read out the contents of a 
computer screen to a user. They 
are commonly used by people 
with visual impairments.

People are accessing websites 
on an increasing range of **devices** 
including desktop computers, 
laptops, tablets, and mobile 
phones. It is important to 
remember that various devices 
have different screen sizes and 
some have faster connections to 
the web than others.

#### Learning from other pages
10% of information you can find it by google it.


---------------------------------------------
## Chapter 1: Structure

#### Understanding structure
**structure** is the arrangement of and relations between the parts or elements of something complex.

the browser window you can see a web page that features exactly 
the same content as the Word document you met on the page 18. To 
describe the structure of a web page, we add code to the words we want 
to appear on the page.

#### Tags and elements 
![HTML](https://csveda.com/wp-content/uploads/2020/02/HTML_Structure.png)

**<body>**
You met the **<body>** element 
in the first example we created. 
Everything inside this element is 
shown inside the main browser 
window.

**<head>**
Before the **<body>** element you 
will often see a **<head>** element. 
This contains information 
about the page (rather than 
information that is shown within 
the main part of the browser 
window that is highlighted in 
blue on the opposite page). 
You will usually find a **<title>**
element inside the **<head>**
element.

**<title>**
The contents of the **<title>**
element are either shown in the 
top of the browser, above where 
you usually type in the URL of 
the page you want to visit, or 
on the tab for that page (if your 
browser uses tabs to allow you 
to view multiple pages at the 
same time).
![Tags](https://mason.gmu.edu/~kshiffl4/375/HTML_Tags.jpg)
---------------------------------------------
---------------------------------------------
## Chapter 8: Extra Markup
#### Specifying different versions of HTML
Each new version was designed 
to be an improvement on the 
last (with new elements and 
attributes added and older code 
removed).

Because there have been 
several versions of HTML, each 
web page should begin with a 
DOCTYPE declaration to tell a 
browser which version of HTML 
the page is using (although 
browsers usually display the 
page even if it is not included). 
We will therefore be including 
one in each example for the rest 
of the book.

![DOCTYPE](https://i.ytimg.com/vi/ZW8qI1HvYJs/maxresdefault.jpg)



#### Comments, meta information and iframes:
##### Comments in HTML

**<!-- -->**

If you want to add a comment 
to your code that will not be 
visible in the user's browser, you 
can add the text between these 
characters:eg:

<!-- comment goes here -->

##### ID Attribute
Every HTML element can carry 
the id attribute. It is used to 
uniquely identify that element 
from other elements on the 
page. Its value should start with 
a letter or an underscore (not a 
number or any other character).
It is important that no two 
elements on the same page 
have the same value for their id
attributes (otherwise the value is 
no longer unique).
![ID](https://codebridgeplus.com/wp-content/uploads/html-links.jpg)

##### Class attributes
Every HTML element can 
also carry a class attribute. 
Sometimes, rather than uniquely 
identifying one element within 
a document, you will want a 
way to identify several elements 
as being different from the 
other elements on the page. 
For example, you might have 
some paragraphs of text that 
contain information that is more 
important than others and want 
to distinguish these elements, or 
you might want to differentiate 
between links that point to other 
pages on your own site and links 
that point to external sites.
![class](https://www.wikihow.com/images/thumb/5/53/Define-a-CSS-Class-Style-Step-4-Version-2.jpg/v4-460px-Define-a-CSS-Class-Style-Step-4-Version-2.jpg.webp)

##### Block Elements
Some elements will always 
appear to start on a new line in 
the browser window. These are 
known as block level elements. 

Examples of block elements are 
<h1>, <p>, <ul>, and <li>.

##### Inline element
Some elements will always 
appear to continue on the 
same line as their neighbouring 
elements. These are known as 
inline elements.

Examples of inline elements are 
<a>, <b>, <em>, and <img>


#### Identifying and grouping elements
##### div  --><div>
The <div> element allows you to 
group a set of elements together 
in one block-level box.

##### span
The <span> element acts like 
an inline equivalent of the <div>
element.

## Chapter 17: HTML5 Layou     
HTML5 introduces a new set of elements that allow you to divide up the 
parts of a page. The names of these elements indicate the kind of content 
you will find in them. They are still subject to change, but that has not 
stopped many web page authors using them already.

![layout](https://stuyhsdesign.files.wordpress.com/2016/05/yoko-html5.png)

##### Headers & Footers
The <header> and <footer>
elements can be used for:
* The main header or footer 
that appears at the top or 
bottom of every page on the 
site.
* A header or footer for an 
individual <article> or 
<section> within the page.

##### Navigation
The <nav> element is used to 
contain the major navigational 
blocks on the site such as the 
primary site navigation.

##### Articles
The <article> element acts as 
a container for any section of a 
page that could stand alone and 
potentially be syndicated.

##### Sections
The <section> element groups 
related content together, and 
typically each section would 
have its own heading.
<<<<<<< HEAD
* The new HTML5 elements indicate the purpose of 
different parts of a web page and help to describe 
its structure.
* The new elements provide clearer code (compared 
with using multiple <div> elements).
*  Older browsers that do not understand HTML5 
elements need to be told which elements are 
block-level elements.
* To make HTML5 elements work in Internet Explorer 8 
(and older versions of IE), extra JavaScript is needed, 
which is available free from Google
---------------------------------------------
## Chapter 18: Process & Design
It's important to understand who your target audience 
is, why they would come to your site, what information 
they want to find and when they are likely to return.
*  Site maps allow you to plan the structure of a site.
*  Wireframes allow you to organize the information that 
will need to go on each page.
* Design is about communication. Visual hierarchy helps 
visitors understand what you are trying to tell them.
*  You can differentiate between pieces of information 
using size, color, and style. 
* You can use grouping and similarity to help simplify 
the information you present
---------------------------------------------
# JavaScript

![](https://res.cloudinary.com/practicaldev/image/fetch/s--1LH1zbno--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/84jmz6dsrpggzfb6ffyr.png)
The next must-read blog post after learning this in JavaScript.

* A - apply()
* B - bind()
* c - call()

Using them, we can set what 'this' should refer to, irrespective of how or where the function gets called. Let's see what would happen in case of an object. showName method is being called through its owner object student, as shown below...

const student = {
    name: "Rahul", 
    showName: function(){
        console.log(this.name); 
    }
}

student.showName(); //Rahul

Hence, 'this' used inside the function will refer to the student object.

What if we assign the showName function to a global scoped variable greetStudent, and then call it as below...

const student = {
    name: "Rahul", 
    showName: function(){
        console.log(this.name); 
    }
}

const greetStudent = student.showName; 

greetStudent();

//Does not print Anything

// 'this' refers to global object now

// because greetStudent is global, and hence student.showName is being called globally.

The reference to 'this' changes to the global object, & this can cause unwanted and hard to spot bugs.

=======

## Chapter 18: Process & Design
>>>>>>> 7cb628fa51d8436a39a7ffa394ec440df8c22638
