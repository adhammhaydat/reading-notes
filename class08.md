
## Chapter 15: “Layout”

Websites often display content in multiple columns (like a magazine or a newspaper).

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/HTML-Layout-df.jpg)

**HTML Layout Techniques**
There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

* CSS framework
* CSS float property
* CSS flexbox
* CSS grid

**Key Concepts in Positioning Elements**
1. Building Blocks
2. Block-level elements
3. Inline elements
4. Containing Elements :

If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

**Controlling the Position of Elements**

CSS has the `following positioning schemes` that allow you to control the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

1. Normal flow

The paragraphs appear one 
after the other, vertically down 
the page.

2. Relative Positioning

The  paragraph has been 
pushed down and right from 
where it would otherwise have 
been in normal flow.

3. Relative Positioning

The heading is positioned to the 
top right, and the paragraphs 
start at the top of the screen (as 
if the heading were not there).

4. Fixed Positioning 

The heading has been placed in 
the center of the page and 25% 
from the top of the screen. (The 
rest appears in normal flow.)

5. Floating Elements

The heading has been floated to 
the left, allowing the paragraphs 
of text to flow around it.

When you move any element from 
normal flow, boxes can overlap. The 
z-index property allows you to control 
which box appears on top.

**Floating Elements**

The float property allows you 
to take an element in normal 
flow and place it as far to the 
left or right of the containing 
element as possible.

**Clearing floats**

`clear`

The `clear` property allows you 
to say that no element (within 
the same containing element) 
should touch the left or righthand sides of a box. It can take the following values:

`left`

The `left-hand` side of the box 
should not touch any other 
elements appearing in the same 
containing element.

`right`

The `right-hand` side of the 
box will not touch elements 
appearing in the same containing 
element.

`both`

Neither the left nor right-hand 
sides of the box will touch 
elements appearing in the same 
containing element.

`none`

Elements can touch either side.


**Screen Sizes**

Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to work on a range of different sized screens.

**Screen Resolution**

Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

**Page Sizes**

Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

**Fixed Width Layouts**

Fixed width layout designs do not 
change size as the user increases 
or decreases the size of their 
browser window. Measurements tend 
to be given in pixels.

**Liquid Layouts**

Liquid layout designs stretch and contract 
as the user increases or decreases the 
size of their browser window. They tend to 
use percentages.

**Layout Grids**

![grids](https://i.stack.imgur.com/gAlk3.png)

Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements — how they are 
organized on a page. Many designers use a grid structure to help them position items on a page, and the same is true for web designers.
