# Object-Oriented Programming, HTML Tables

1. Domain Modeling
2. Chapter 6: “Tables” 
3. Chapter 3: “Functions, Methods, and Objects” 

--------------------------------------------------
## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Domain_model.png/320px-Domain_model.png)


you can find all informatin about domain modling in this site [domain modling](https://github.com/codefellows/domain_modeling#domain-modeling)

--------------------------------------------------

## Chapter 6: “Tables”

**What's a Table?** 

A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results.

**Basic Table Structure**

![table](https://vertex-academy.com/tutorials/wp-content/uploads/2016/08/table.png)

`<table>`

The `<table>` element is used 
to create a table. The contents 
of the table are written out row 
by row

`<tr>`

You indicate the start of each 
row using the opening `<tr>` tag. 
(The tr stands for table row.) 
It is followed by one or more 

`<td>` elements (one for each cell 
in that row). 
At the end of the row you use a 
closing `</tr>` tag.
`<td>`
Each cell of a table is 
represented using a `<td>`
element. (The td stands for 
table data.)
At the end of each cell you use a 
closing `</td>` tag

`<th>`

The `<th>` element is used just 
like the `<td>` element but its 
purpose is to represent the 
heading for either a column or 
a row. (The th stands for table 
heading.) 

**Spanning Columns&Rows**

![Spanning ColumnS](https://flylib.com/books/2/631/1/html/2/images/08fig19.jpg)

The colspan attribute can be 
used on a `<th>` or `<td>` element 
and indicates how many columns 
that cell should run across.

**Long Tables**


There are three elements that 
help distinguish between the 
main content of the table and 
the first and last rows (which can 
contain different content).
These elements help people 
who use screen readers and also 
allow you to style these sections 
in a different manner than the 
rest of the table (as you will see 
when you learn about CSS).

`<thead>`

The headings of the table should 
sit inside the `<thead>` element. 

`<tbody>`

The body should sit inside the 
`<tbody>` element. 



`<tfoot>`

The footer belongs inside the 
`<tfoot>` element.
By default, browsers rarely treat 
the content of these elements 
any differently than other 
elements however designers 
often use CSS styles to change 
their appearance

--------------------------------------------------

## Chapter 3: “Functions, Methods, and Objects”


**What's the difference between a method and a function?**

A function is a piece of code that is called by name. It can be passed data to operate on (i.e. the parameters) and can optionally return data (the return value). All data that is passed to a function is explicitly passed.

A method is a piece of code that is called by a name that is associated with an object. In most respects it is identical to a function except for two key differences:

1. A method is implicitly passed the object on which it was called.
2. A method is able to operate on data that is contained within the class (remembering that an object is an instance of a class - the class is the definition, the object is an instance of that data).

### Functions:

Self-contained bits of JS code that allow us to 
* Organize code 
* Reuse the same code any number of times, from different 

parts of the script JS supports several types of function. Commonly used types are:
* Named function declaration
* Anonymous functions

## JavaScript Objects

JavaScript is an object-based language
* It supports for object-oriented programming but not at the same level as 
other languages (ES6: introduced class – still lacks private property)

Objects are represented as property-value pair
* The property values can be data or functions (methods)

A property is something that can be modified :
* Data properties : primitive values or references to objects
* Method properties : can be executed

Objects can be created and their properties can be changed dynamically
* JS is not really typed .. If it doesn’t care between a number and a string, why 
care between two kinds of objects? 

**creating object**

![creating](https://th.bing.com/th/id/R6ee17df57934073b9c848b4d8009ce66?rik=O0d%2fA%2bIxyE5N2w&pid=ImgRaw)

**Accessing Objects**

Access properties or methods of an object using dot notation:
`let hotelName = hotel.name;`

Access properties or methods using square brackets:

`let hotelName = hotel['name'];`

**Updating Properties:**

 `hotel.name='adham';`

**Adding Properties:**

Add a property using a dot notation

`hotel.sute =true;`

**Deleting Properties**

Delete a property using the delete keyword

`delete hotel.name;`