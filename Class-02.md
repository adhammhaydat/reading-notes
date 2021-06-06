# HTML
## Chapter 2: Text
### Headings and paragraphs
#### Headings
HTML has six "levels" of 
headings:

<h1> is used for main headings.


<h2> is used for subheadings
If there are further sections 
under the subheadings then the 
<h3> element is used, and so 
on..


#### Paragraphs
To create a paragraph, surround 
the words that make up the 
paragraph with an opening <p>
tag and closing </p> tag.

#### Bold & Italic
By enclosing words in the tags 
<b> and </b> we can make 
characters appear bold.

The <b> element also represents 
a section of text that would be 
presented in a visually different 
way (for example key words in a 
paragraph) although the use of 
the <b> element does not imply 
any additional meaning.

By enclosing words in the tags 
<i> and </i> we can make 
characters appear italic.

#### Superscript & Subscrip
The <sup> element is used 
to contain characters that 
should be superscript such 
as the suffixes of dates or 
mathematical concepts like 
raising a number to a power such 
as 2^2.

The <sub> element is used to 
contain characters that should 
be subscript. It is commonly 
used with foot notes or chemical 
formulas such as H20.

#### Line Breaks & Horizontal Rules
As you have already seen, the 
browser will automatically show 
each new paragraph or heading 
on a new line. But if you wanted 
to add a line break inside the 
middle of a paragraph you can 
use the line break tag <br />.

To create a break between 
themes — such as a change of 
topic in a book or a new scene 
in a play — you can add a 
horizontal rule between sections 
using the <hr /> tag.

#### Strong & Emphasis
The use of the <strong>
element indicates that its 
content has strong importance. 
For example, the words 
contained in this element might 
be said with strong emphasis.

The <em> element indicates 
emphasis that subtly changes 
the meaning of a sentence.

#### Quotations
The <blockquote> element is 
used for longer quotes that take 
up an entire paragraph. Note 
how the <p> element is still 
used inside the <blockquote>
element.

#### Abbreviations & Acronyms
If you use an abbreviation or 
an acronym, then the <abbr>
element can be used. A title
attribute on the opening tag is 
used to specify the full term.


## Chapter 10: Introducing CSS
CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.

**How does CSS actually work?**

When a browser displays a document, it must combine the document's content with its style information. It processes the document in a number of stages, which we've listed below. Bear in mind that this is a very simplified version of what happens when a browser loads a webpage, and that different browsers will handle the process in different ways. But this is roughly what happens.

The browser loads the HTML (e.g. receives it from the network).
It converts the HTML into a DOM (Document Object Model). The DOM represents the document in the computer's memory. The DOM is explained in a bit more detail in the next section.
The browser then fetches most of the resources that are linked to by the HTML document, such as embedded images and videos ... and linked CSS! JavaScript is handled a bit later on in the process, and we won't talk about it here to keep things simpler.
The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on. Based on the selectors it finds, it works out which rules should be applied to which nodes in the DOM, and attaches style to them as required (this intermediate step is called a render tree).
The render tree is laid out in the structure it should appear in after the rules have been applied to it.
The visual display of the page is shown on the screen (this stage is called painting).

The following diagram also offers a simple view of the process.
![css](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works/rendering.svg)
=============================================

# Javascript
**How to enable JavaScript in your browser??**

Nowadays almost all web pages contain JavaScript, a scripting programming language that runs on visitor's web browser. It makes web pages functional for specific purposes and if disabled for some reason, the content or the functionality of the web page can be limited or unavailable. Here you can find instructions on how to enable (activate) JavaScript in five most commonly used browsers.

**Instructions for web developers**

You may want to consider linking to this site, to educate any script-disabled users on how to enable JavaScript in five most commonly used browsers. You are free to use the code below and modify it according to your needs.

On enable-javascript.com we optimize the script-disabled user experience as much as we can:
* The instructions for your browser are put at the top of the page
* All the images are inlined, full-size, for easy perusing
* This developer-centric message is out of the way.

We want your visitors to have JavaScript enabled just as much as you do!