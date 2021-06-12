# Problem Domain, Objects, and the DOM

1. Understanding the problem domain is the hardest part of programming
2. Chapter 3: “Object Literals” (pp.100-105)
3. Chapter 5: “Document Object Model” (pp.183-242)

--------------------------------------------------

## Understanding the problem domain is the hardest part of programming

**What is the hardest thing about writing code?**

There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

**A familiar problem**

I am often asked why I keep demonstrating how to build the same simple application over and over again?.

The answer is **“familiarity.”**

By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

**Programming is easy if you understand the problem domain**

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain

`You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.`

for more information visit this site [simpleprogrammer.com](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)


--------------------------------------------------

## Chapter 3: “Object Literals” (pp.100-105)

WHAT IS AN OBJECT? 

Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names.

**IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES**

If a variable is part of an object, it is called a 
`property`. Properties tell us about the object, such as 
the name of a hotel or the number of rooms it has. 
Each individual hotel might have a different name 
and a different number of rooms.

**IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS**

If a function is part of an object, it is called a `method`. 
Methods represent tasks that are associated with 
the object. For example, you can check how many 
rooms are available by subtracting the number of 
booked rooms from the total number of rooms. 

![objects](https://appdividend.com/wp-content/uploads/2019/03/Javascript-Objects-Tutorial-Example-Working-With-Objects-in-JS.png)

CREATING· OBJECTS USING  LITERAL NOTATION 

![](https://miro.medium.com/max/4096/1*GA7toY-Y3a3l0nlewOxIAw.png)


--------------------------------------------------


## Chapter 5: “Document Object Model”

The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

**MAKING A MODEL OF THE HTM L PAGE**

When the browser loads a web page, it 
creates a model of the page in memory. 

The DOM specifies the way in which the 
browser should structure this model using 
a DOM tree. 

The DOM is called an object model 
because the model (the DOM tree) is 
made of objects. 

Each object represents a different part of 
the page loaded in the browser window. 

**ACCESSING AND CHANGING THE HTML PAGE**

The DOM also defines methods and 
properties to access and update each 
object in this model, which in turn updates 
what the user sees in the browser. 

You will hear people call the DOM an 
`Application Programming Interface (API)`. 
User interfaces let humans interact with 
programs; APls let programs (and scripts) 
talk to each other. The DOM states what 
your script can "ask the browser about the 
current page, and how to tell the browser 
to update what is being shown to the user.

![dom](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)


### WORKING WITH THE DOM TREE

Accessing and updating the DOM tree involves two steps:

1. Locate the node that represents the element you want to work with. 
2. Use its text content, child elements, and attributes.

### **STEP 1: ACCESS THE ELEMENTS**

**SELECT AN INDIVIDUAL ELEMENT NODE**

* `get El ement Byld ()` Uses the value of an element's id attribute
* `querySe 1 ector ()` Uses a CSS selector, and returns the first matching element.  

**SELECT MULTIPLE ELEMENTS (NODELISTS)**

* getElementsByClassName() Selects all elements that have a specific value for their cl ass 
attribute.

* getElementsByTagName() Selects all elements that have the specified tag name ..

* querySelectorAll() Uses a CSS selector to select all matching elements.

**TRAVERSING BETWEEN ELEMENT NODES**

* parentNode Selects the parent of the current 
element node (which will return just one element).

* previousSibl ing / nextSibl ing Selects the previous or next sibling from the DOM tree.

* firstChild / lastChild Select the first or last child of the current element. 

### **STEP 2: WORK W ITH THOSE ELEMENTS**

**ACCESS/ UPDATE TEXT NODES**
The text inside any element is 
stored inside a text node. To 
access the text node above:
1. Select the <l i >element 
2. Use the fi rstChi l d property 
to get the text node 
3. Use the text node's only 
property (nodeVa l ue) to get 
the text from the element  

`nodeValue` This property lets you access or 
update contents of a text node.

**WORK W ITH HTML CONTENT**

One property allows access to 
child elements and text content: `innerHTML`

Another just the text content: . `textContent`

Several methods let you create 
new nodes, add nodes to a tree, 
and remove nodes from a tree: 
`create Element() createTextNode() appendChi l d() / removeChi l d ()` 
This is called DOM manipulation. 

**ACCESS OR UPDATE ATTRIBUTE VALUES**

Here are some of the properties 
and methods you can use to work with attributes: `className /id` Lets you get or update the value 
of the cl ass and id attributes.

`hasAttr i bute()` 

`getAttribute()`

`setAttri bute()`

`removeAttribute()` 
The first checks if an attribute 
exists. The second gets its value. 
The third updates the value. 
The fourth removes an attribute. 

