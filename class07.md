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



