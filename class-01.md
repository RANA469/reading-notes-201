We come across all kinds of documents
every day of our lives.
In all kinds of documents, structure is very important in helping
readers to understand the messages you are trying to convey
and to navigate around the document., it is very important to understand how to
structure documents
*How Pages Use
Structure:
1.there will be a headline, If the article is a long
piece, there may be subheadings
that split the story into separate
sections .
( Structure helps readers
understand the stories)
( Again, the
structure is very similar online)
  in a very different
type of document often have headings for different
sections, and each section
contains a list of questions with
areas for you to fill in details or
checkboxes to tick
*Structuring Word
Documents:
1.The use of headings and
subheadings in any document
often reflects a hierarchy of
information. ( example)document start with
a large heading, followed by
an introduction or the important information.
2.When using a word
processor to create a document,
we separate out the text to give
it structure, Each topic have a new paragraph, and each
section  have a heading to
describe what it covers.
3.. If you
regularly use Word, you might
have also used the formatting
toolbar or palette to do this.
(. We use
structure in the same way when
writing web pages.)
(حطي صورة سكرين 1)
*HTML Describes
the Structure
of Pages: To
describe the structure of a web page, we add code to the words we want
to appear on the page
{. Note that the HTML code is in blue, and the text you see on screen
is in black} حطي سكرين 2
— these are called HTML elements:usually
made up of two tags:1.: an opening tag
2. a closing tag. (The closing tag
has an extra forward slash in it.) 
حطي سكرين 3
Tags act like containers. the information that
between their opening and closing tags.
 حطي سكرين 4



Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.--->  <p lang="en-us">Paragraph in English</p>
1.The attribute name indicates
what kind of extra information
you are supplying about the
element's content
2.The value is the information
or setting for the attribute. It
should be placed in double
quotes.
3. attribute called lang is
used to indicate the language
used in this element.
------
<body>
You met the <body> element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.
<head>
Before the <body> element you
will often see a <head> element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a <title>
element inside the <head>
element.
<title>
The contents of the <title>
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).
---------
-Anything written between the
<title> tags will appear in the
title bar (or tabs) at the top of
the browser window, highlighted
in orange here.
-Anything written between
the <body> tags will appear
in the main browser window,

**Creating a Web Page
on a PC
1. start up Notepad
2.Type the code
3.Go to the File menu and select
Save as
4.Go to
the File menu and select Open.
Browse to the file that you just
created, select it and click on the
Open button.

--------

**Creating a Web Page
on a Mac
1.start up TextEdit
2.Type the code 
3.Now go to the File menu and
select Save as
4.go to the File menu, and select
Open.

------

**Code in a Content
Management System
For an e-commerce store, you
might have boxes that allow you
to enter a title for the product, 
(For example, an e-commerce system might use the same
template to show all of their
products.) The information
you supply is placed into the
templates.

------

**Looking at How Other
sites are Built:When the web was first taking
off, one of the most common
ways to learn about HTML and
discover new tips,, but you can
still look at the code that a web
server sends to you,You should see a new window
appear, and it will contain the
source code that was used to
create this page,You can see this result in the
photograph on the right

------

**Summary structure:
*HTML pages are text documents.
*HTML uses tags 
*Tags are often referred to as elements.
*Tags usually come in pairs.
*Opening tags can carry attributes
*Attributes require a name and a value.
*To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

----------------------------------------------------------------

The <form> element uses the action attribute to indicate the page that
the data is being sent to. Each of the form controls sits inside the <form>
element. Different types of form control are suited to collecting different
types of data. The <fieldset> element is used to group related
questions together. The <label> element indicates the purpose of each
form control.

*Example
<html>
<head>
 <title>Forms</title>
</head>
<body>
 <form action="http://www.example.com/review.php" method="get">
 <fieldset>
 <legend>
 Your Details:
 </legend>
 <label>
 Name:
 <input type="text" name="name" size="30" maxlength="100">
 </label>
 <br />
 <label>
 Email:
 <input type="email" name="email" size="30" maxlength="100">
 </label>
 <br />
 </fieldset>
 <br />
 <fieldset>
 <legend>
 Your Review:
 </legend>
 <p>
 <label for="hear-about">
 How did you hear about us?
 </label>
 <select name="referrer" id="hear-about">
 <option value="google">Google</option>
 <option value="friend">Friend</option>
 <option value="advert">Advert</option>
 <option value="other">Other</option>
 </select>
 </p>
 <p>

-----

-The Evolution of HTML:Since the web was first created, there have
been several different versions of HTML


Each new version was designed
to be an improvement on the
last (with new elements and
attributes added and older code
removed).

-HTML 4
Released 1997:With the exception of a few
elements added in HTML5 all available in
HTML 4.
(Examples
include the <center> element
for centering content on a
page <font> for controlling
the appearance of text

-XHTML 1.0
Released 2000:In 1998, a language called XML
was published allow people to write
new markup languages
examble:
● Every element needed a
closing tag (except for empty
elements such as <img />).
● Attribute names had to be in
lowercase.
● All attributes required a value,
and all values were to be
placed in double quotes.
● Deprecated elements should
no longer be used.
● Every element that was
opened inside another
element should be closed
inside that same element

-HTML5
Released 2000: do
not need to close all tags, and
new elements and attributes will
be introduced
---------

*DOCTYPEs:

Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using
-------

<!-- --> If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters

--------

ID Attribute:Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page,If you go on to learn about
JavaScript (a language that
allows you to add interactivity to
your pages), id attributes can be
used to allow the script to work
with that particular element.
-The id attribute is known as a
global attribute because it can
be used on any element.

--------

*Class attribute :
Every HTML element can
also carry a class attribute.
Sometimes

-For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements

-Examples of block elements are
<h1>, <p>, <ul>, and <li>

------

*Inline elements:Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.
-Examples of inline elements are
<a>, <b>, <em>, and <img>.

------

*Grouping Text &
Elements In a Block:
1.<div> :The <div> element allows you to
group a set of elements together
in one block-level box.

------

*Grouping Text &
Elements Inline :<span>
-The <span> element acts like
an inline equivalent of the <div>
element. It is used to :
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements

------

*IFrames:<iframe>
An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame.

1.src
The src attribute specifies the
URL of the page to show in the
frame.
2.height
The height attribute specifies
the height of the iframe in pixels.
3.width
The width attribute specifies
the width of the iframe in pixels.
4.scrolling
 it indicates
whether the iframe should
have scrollbars or no
5.frameborder
 it indicates
whether the frame should have
a border or not.
6.seamless
can be applied
to an iframe where scrollbars
are not desired. 

--------

*Information About
Your Pages:

1.<meta>
The <meta> element lives
inside the <head> element and
contains information about that
web page.
2.description
This contains a description
of the page
3.keywords
This contains a list of commaseparated words that a user
might search on to find the page.
4.robots
This indicates whether search
engines should add this page
to their search results or not
5.author
This defines the author of the
web page
6.pragma 
This prevents the browser from
caching the page
7.expires
Because browsers often cache
the content of a page, the
expires option can be used
to indicate when the page
should expire 

---------

<
>
&
"
¢
£
¥
¤
©
®
™
‘
'
“
”
×
÷
Less-than sign
&lt;
&#60;
Greater-than sign
&gt;
&amp;
Ampersand
&amp;
&#38;
Quotation mark
&quot;
&#34;
Cent sign
&cent;
&#162;
Pound sign
&pound;
&#163;
Yen sign
&yen;
&#165;
Euro sign
&euro;
&#8364;
Copyright symbol
&copy;
&#169;
Registered trademark
&reg;
&#174;
Trademark
&trade;
&#8482;
Left single quote
&lsquo;
&#8216;
Right single quote
&rsquo;
&#8217;
Left double quotes
&ldquo;
&#8220;
Right double quotes
&rdquo;
&#8221;
Multiplication sign
&times;
&#215;
Division sign
&divide;
&#247;

--------

X DOCTYPES tell browsers which version of HTML you
are using.
X You can add comments to your code between the
<!-- and --> markers.
X The id and class attributes allow you to identify
particular elements.
X The <div> and <span> elements allow you to group
block-level and inline elements together.
X <iframes> cut windows into your web pages through
which other pages can be displayed.
X The <meta> tag allows you to supply all kinds of
information about your web page.
X Escape characters are used to include special
characters in your pages such as <, >, and ©.

-----------------------------------------------------------------


-Example
IMages

<!DOCTYPE html>
<html>
<head>
 <title>Images</title>
 <style type="text/css">
 body {
 color: #665544;
 background-color: #d4d0c6;
 background-image: url("images/backdrop.gif");
 font-family: Georgia, "Times New Roman", serif;
 text-align: center;}
 .wrapper {
 width: 720px;
 margin: 0px auto;}
 .header {
 margin: 40px 0px 20px 0px;}
 .entry {
 width: 220px;
 float: left;
 margin: 10px;
 height: 198px;
 background-image: url("images/shadow.png");
 background-repeat: no-repeat;
 background-position: bottom;}
 figure {
 display: block;
 width: 202px;
 height: 170px;
 background-color: #e7e3d8;
 padding: 9px;
 text-align: left;}
 figure img {
 width: 200px;
 height: 150px;
 border: 1px solid #d6d6d6;}
 figcaption {
 background-image: url("images/icon.png");
 padding-left: 20px;
 background-repeat: no-repeat;}
 </style>

-----------

-HTML5 is introducing a new set of
elements that help define the structure of
a page.

-Traditional HTML
Layouts
حطي سكرين 5

-HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already

-The <header> and <footer>
elements can be used for:
● The main header or footer
that appears at the top or
bottom of every page on the
site.
● A header or footer for an
individual <article> or
<section> within the page.

-Navigation
<nav>
The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.

-Articles
<article>
The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

-Article
<aside>
The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not.

-Sections
<section>
The <section> element groups
related content together, and
typically each section would
have its own heading.

-Heading Groups
<hgroup>
The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading.

-Figures
<figure> <figcaption>
 It can be used
to contain any content that is
referenced from the main flow of
an article (not just images). 

-Sectioning Elements
<div>
the <div> element
will remain an important way to
group together related elements,

-Linking Around
Block-Level Elements
HTML5 allows web page authors
to place an <a> element around
a block level element that
contains child elements

-Helping Older
Browsers Understand
You do not need to understand
JavaScript to use it. You can
just link to a copy that Google
hosts on its servers. It should
be placed inside a conditional
comment which checks if the
browser version is less than
(hence the lt) IE9.

Example
HTML5 LAYOUT
color: #ffffff;}
 nav li a:hover, nav li a.current {
 color: #000000;}
 section.courses {
 float: left;
 width: 659px;
 border-right: 1px solid #eeeeee;}
 article {
 clear: both;
 overflow: auto;
 width: 100%;}
 hgroup {
 margin-top:40px;}
 figure {
 float: left;
 width: 290px;
 height: 220px;
 padding: 5px;
 margin: 20px;
 border: 1px solid #eeeeee;}
 figcaption {
 font-size: 90%;
 text-align: left;}
 aside {
 width: 230px;
 float: left;
 padding: 0px 0px 0px 20px;}
 aside section a {
 display: block;
 padding: 10px;
 border-bottom: 1px solid #eeeeee;}
 aside section a:hover {
 color: #985d6a;
 background-color: #efefef;}
 a {
 color: #de6581;
 text-decoration: none;}
 h1, h2, h3 {
 font-weight: normal;}
 h2 { 

-------

X The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.
X The new elements provide clearer code (compared
with using multiple <div> elements).
X Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
X To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.

-------------------------------------------------------------

-Who is the Site For?Every website should be designed for the
target audience—not just for yourself or the
site owner. It is therefore very important to
understand who your target audience is.

-Why People Visit
YOUR Website:Now that you know who your visitors are, you
need to consider why they are coming. While
some people will simply chance across your
website, most will visit for a specific reason.

-What Your Visitors are
Trying to Achieve:It is unlikely that you will be able to list every
reason why someone visits your site but you
are looking for key tasks and motivations. This
information can help guide your site designs.

-What Information
Your Visitors Need:You know who is coming to your site and why
they are coming, so now you need to work out
what information they need in order to achieve
their goals quickly and effectively.

-How Often People Will
Visit Your Site:Some sites benefit from being updated more
frequently than others. Some information (such
as news) may be constantly changing, while
other content remains relatively static.

-Site Maps:Now that you know what needs to appear
on your site, you can start to organize the
information into sections or pages.

-WireFrames:A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

-Getting your message
across using design:The primary aim of any kind of visual design
is to communicate. Organizing and prioritizing
information on a page helps users understand
its importance and what order to read it in.

-Visual hierarchy:Most web users do not read entire pages. Rather, they skim to find
information. You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for.

-grouping and
Similarity:When making sense of a design, we tend to organize visual elements
into groups. Grouping related pieces of information together can make a
design easier to comprehend. Here are some ways this can be achieved.

-Designing Navigation:Site navigation not only helps people find where they want to go, but also
helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles...


X It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
X Site maps allow you to plan the structure of a site.
X Wireframes allow you to organize the information that
will need to go on each page.
X Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
X You can differentiate between pieces of information
using size, color, and style.
X You can use grouping and similarity to help simplify
the information you present 
--------------------------------------------------------------

****ducket javascript*****

*A SCRIPT IS A SERI ES OF
INSTRUCTIONS :A script is a series of instructions that a
computer can follow to achieve a goal. 

1.RECIPES 
2.HANDBOOKS
3.MANUALS

*WRITING A
SCRIPT:To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it

1: DEFINE THE GOAL
First, you need to define the task you want to
achieve. You can think of this as a puzzle for the
computer to solve.
2: DESIGN THE SCRIPT
To design a script you split the goal out into a series
of tasks that are going to be involved in solving this
puzzle. This can be represented using a flowchart.
You can then write down individual steps that the
computer needs to perform in order to complete
each individual task (and any information it needs to
perform the task), rather like writing a recipe that it
can follow.
3: CODE EACH STEP
Each of the steps needs to be written in a
programming language that the compu ter
understands. In our case, this is JavaScript. 

------

Every step for every task shown
in a flowchart needs to be written
in a language the computer can
understand and follow. 

Just like learning any new language, you need
to get to grips with the:
• Vocabulary: The words that computers
understand
• Syntax: How you put those words together to
create instructions computers can follow

You need to learn to "think" like
a computer because they solve
tasks in different ways than you or
I might approach them

-----

-DEFINING A GOAL &
DESIGNING THE SCRIPT:Consider how you might approach a different type of script.
This example calculates the cost of a name plaque.
Customers are charged by the letter. 

-SKETCHING OUT THE
TASKS IN A FLOWCHART:Often scripts will need to perform different tasks in different situations.
You can use flowcharts to work out how the tasks fit together.
The flowcharts show the paths between each step.


1.A script is a series of instructions that the computer
can follow in order to achieve a goal.
2.Each time the script runs, it might only use a subset of
all the instructions.
3.Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
4.To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 

--------

-COMPUTERS CREATE
MODELS OF THE WORLD
USING DATA 

-OBJECTS & PROPERTIES:
OBJECTS (TH INGS)
In computer programming, each physical thing in
the world can be represented as an object. There are
two different types of objects here: a hotel and a car

Each object can have its own:
• Properties
• Events
• Methods

-EVENTS :In the real world, people interact with objects. These interactions can
change the values of the properties in these objects.

WHAT IS AN EVENT?
There are common ways in which people interact
with each type of object. For example, in a car a
driver will typically use at least two pedals. The car
has been designed to respond differently when the
driver interacts with each of the different pedals:
• The accelerator makes the car go faster
• The brake slows it down

WHAT DOES AN EVENT DO?
Programmers choose which events they respond to.
When a specific event happens, that event can be
used to trigger a specific section of the code.

-METHODS :Methods represent things people need to do with objects. They can
retrieve or update the values of an object's properties.


WHAT IS A METHOD?
Methods typically represent how people (or other
things) interact with an object in the real world.
They are like questions and instructions that:
• Tell you something about that object (using
information stored in its properties)
• Change the value of one or more of that object's
properties 

WHAT DOES A METHOD DO?
The code for a method can contain lots of
instructions that together represent one task.
When you use a method, you do not always need to
know how it achieves its task; you just need to know
how to ask the question and how to interpret any
answers it gives you.


-WEB BROWSERS ARE
PROGRAMS BUILT
USING OBJECTS :
WINDOW OBJECT
On the right-hand page you can see a model of a
computer with a browser open on the screen. 

The current web page loaded into each window is
modelled using a document object. 

-THE DOCUMENT OBJECT
REPRESENTS AN HTML
PAGE:Using the document object, you can access and change what content
users see on the page and respond to how they interact with it. 

PROPERTIES
Properties describe characteristics of the current
web page (such as the title of the page).
METHODS
Methods perform tasks associated with the
document currently loaded in the browser (such
as getting information from a specified element or
adding new content).
EVENTS
You can respond to events, such as a user clicking or
tapping on an element. 

---------

-HOW A BROWSER
SEES A WEB PAGE:
1: RECEIVE A PAGE AS
HTML CODE
2: CREATE A MODEL OF
THE PAGE AND STORE
IT IN MEMORY
3: USE A RENDERING
ENGINE TO SHOW THE
PAGE ON SCREEN 
*All major browsers use a JavaScript interpreter to translate your
instructions (in JavaScript) into instructions the computer can follow. 

--------
-HOW HTML, CSS,
& JAVASCRIPT FIT
TOGETHER:
CONTENT LAYER
. html files
This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics. 

PRESENTATION LAYER
. css files
The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.)

BEHAVIOR LAYER
.js files
This is where we can change
how the page behaves, adding
interactivity. We will aim to keep
as much of our JavaScript as
possible in separate files. 
