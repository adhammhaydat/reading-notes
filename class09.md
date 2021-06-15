# Forms and JS Events

1. Chapter 7: “Forms” (p.144-175) 
2. Chapter 14: “Lists, Tables & Forms” (pp.330-357)
3. Chapter 6: “Events” (pp.243-292)

-------------------------------------------------------
## Chapter 7: “Forms” (p.144-175)

Traditionally, the term 'form' has referred 
to a printed document that contains 
spaces for you to fill in information.

HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to 
your site.

**Why Forms?**

In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms.

**Form Controls**

There are several types of form controls that 
you can use to collect information from visitors 
to your site.

![forms](https://cdn.educba.com/academy/wp-content/uploads/2019/07/HTML-Form-Controls.png)


### How Forms Work:

![how work](https://howto.caspio.com/wp-content/uploads/2016/12/How_to_convert_existing_html_forms_to_work_with_caspio.png)


### Form Structure

![form structure](https://images.slideplayer.com/30/9546496/slides/slide_13.jpg)

`<form>`

Form controls live inside a 
`<form>` element. This element 
should always carry the action
attribute and will usually have a 
method and id attribute too.

`action`

Every `<form>` element requires 
an action attribute. Its value
is the URL for the page on the 
server that will receive the 
information in the form when it 
is submitted.

`method`

Forms can be sent using one of 
two methods: get or post.

### Grouping Form Elements

`<fieldset>`

You can group related form 
controls together inside the 
`<fieldset>` element. This is 
particularly helpful for longer 
forms.
Most browsers will show the 
fieldset with a line around 
the edge to show how they are 
related. The appearance of these 
lines can be adjusted using CSS.

`<legend>`

The `<legend>` element can 
come directly after the opening 
`<fieldset>` tag and contains a 
caption which helps identify the 
purpose of that group of form 
controls.

### HTML5: Form Validation

You have probably seen forms on the web that give users messages if the form control has 
not been filled in correctly; this is 
known as form `validation`.

![for validation](https://static.raymondcamden.com/images/ScreenClip45.png)

`<input type="text" name="username"
 required="required" /></title><br />` 

 by using required proparoty in code input 


 ### HTML5: Search Input

 `<input>`
If you want to create a single 
line text box for search queries, 
HTML5 provides a special type 
of input for that purpose.

`type="search"`

If you want to create a single 
line text box for search queries, 
HTML5 provides a special 
search input.

To create the HTML5 search box 
the `<input>` element should 
have a type attribute whose 
`value is search`. Older browsers 
will simply treat it like a single 
line text box.

Recent browsers add some 
features that improve usability. 
For example, Safari on a Mac 
adds a cross to clear the search 
box when you have started to 
enter information. Safari also 
automatically rounds the corners 
on the search input field.

`placeholder`

On any text input, you can 
also use an attribute called 
placeholder whose value is 
text that will be shown in the 
text box until the user clicks in 
that area. Older browsers simply 
ignore this attribute.


-------------------------------------------------------

## Chapter 14: “Lists, Tables & Forms” 

### Bullet Point Styles

**list-style-type**

![lest](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/7db7b396-48da-4e19-9df5-ed21d9de5d39/list-markers.jpg)

**list-style-image**
by adding this code to css file

`ul {`

`list-style-image: url("images/star.png");}`

**list-style-position**

Lists are indented into the page 
by default and the list-styleposition property indicates whether the marker should 
appear on the inside or the 
outside of the box containing the 
main points. 

This property can take one of 
two values:

`outside`

The marker sits to the left of the 
block of text. (This is the default 
behaviour if this property is not 
used.)

`inside`

The marker sits inside the box of 
text (which is indented).

### List Shorthand

As with several of the other CSS 
properties, there is a property 
that acts as a shorthand for list 
styles. It is called list-style, 
and it allows you to express 
the markers' style, image and 
position properties in any order.



-------------------------------------------------------

## Chapter 6: “Events”

W hen you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. 

![](https://www.heelpbook.net/wp-content/uploads/2014/12/overviewhtml4.png)

**HOW EVENTS TRIGGER JAVASCRIPT CODE**

When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling. 

1. Select t he element node(s) you want the 
script to respond to. 
2. Indicate which event on the selected node(s) will 
trigger the response. 
3. State the code you want to run when the event 
occurs.


