# exercicio-css

CSS Selectors

Exercise 1:

Set the text color to red, for all <p> elements.

<style>
p { 
color:red;
}
</style>

Exercise 2:

Set the text color to red, for the element with id="para1".

<style>
#para1{
color:red;
}
</style>
<body>
  <h1>This is a heading</h1>
  <p id="para1">This is a paragraph</p>
</body>

Exercise 3:

Set the text color to red, for elements with class="colortext".

<style>
.colortext{
color:red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p class="colortext">This is a paragraph</p>
  <p class="colortext">This is a paragraph</p>
</body>

Exercise 4:

Set the text color to red, for all <p> and <h1> elements. Group the selectors to minimize code.

<style>
h1, p{
  
color:red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <h2>This is a smaller heading</h2>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
--------------------------------------------------------------------
CSS How To...

Exercise 1:

Add an external style sheet with the URL: "mystyle.css".

<head>
<link rel="stylesheet" href="mystyle.css">
</head>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2:

Set the page's background color to red.

<style>
body
 {
  
background-color:
 red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3:

Set the page's background color to red, by using an inline style.

<body 
style="background-color: red">
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4:

Insert the missing parts to make the CSS code correct.

<style>
p {
color:red;
}

</style>
----------------------------------------------------------------
CSS Background

Exercise 1:

Set the background color of the <h1> element to "lightblue".

<style>
h1 {
background-color: lightblue;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2:

Set "paper.gif" as the background image of the page.

<style>
body {
  
background-image: url("paper.gif");
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3:

Make the background image repeat only vertically.

<style>
body {
  background-image: url("img_tree.png");
  
background-repeat: repeat-y;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4:

Specify that the background image should be shown once, in the top right corner.

<style>
body {
  background-image: url("img_tree.png");
  
background-repeat: no-repeat;
  
background-position: top right;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 5:

Use the correct background property to make the background image NOT scroll with the rest of the page.

<style>
body {
  background-image: url("img_tree.png");
  
background-attachment: fixed;
}
</style>
-------------------------------------------------------------------------------------------------------------------
CSS Border

Exercise 1:

Use the border shorthand property to set a "4px", "dotted", "red" border for the <p> elements.
<style>
p {
  
border: 4px dotted red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2:

Use the correct border property to set the border color to "red".

<style>
p {
  border-style: dotted;
  border-width: 4px;
  
border-color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3:

Use the correct border property to set the LEFT border to "dotted".

<style>
p {
  
border-left-style: dotted;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4:

Use the correct border property to add ROUNDED borders to the <p> elements.

<style>
p {
  border: 2px solid red;
  
border-radius: 5px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
--------------------------------------------------------------------------------------------------------------------------------
CSS Margin

Add a 20 pixels left margin to the <h1> element.

<style>
h1 {
  
margin-left: 20px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2:

Use the shorthand margin property to add 20 pixels top and bottom margins, and 40 pixels left and right margins, on the <h1> element.

<style>
h1 {
  margin: 20px 40px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3:

For the <h1> element, use the shorthand margin property to add these margins:
left: 10px
right: 15px
top: 20px
bottom: 25px

<style>
h1 {
  margin: 
20
px 
15
px 
25
px 
10
px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4:

Use the margin property to center align the <h1> element.

<style>
h1 {
  margin: 
auto
;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
-------------------------------------------------------------------------------------------------------------------------------------
CSS Padding

Exercise 1:

Set the top padding of the <h1> element to 30 pixels.

<style>
h1 {
  
padding-top
: 30px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2:

Set the padding of all sides of the <h1> element to 30 pixels.

<style>
h1 {
  
padding
: 30px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3:

Use the shorthand padding property to add 10 pixels left and right padding, and 40 pixels top and bottom padding, on the <h1> element.

<style>
h1 {
  padding: 
40
px 
10
px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

CSS Height/width

Exercise 1
<style>
h1 {
  
height: 100px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2

<style>
h1 {
  
width:50%;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
------------------------------------------------------------------------------------------
CSS Box Model

Exercise 1
<style>
div{
width: 200px;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>

Exercise 2

<style>
div{
  width: 200px;
  
border: 2px solid red;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>

Exercise 3
<style>
div {
  width: 200px;
  border: 2px solid red;  
  padding: 25px;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>

Exercise 4
<style>
div {
  width: 200px;
  border: 2px solid red;  
  padding: 25px;
  margin-left: 25px;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>
-----------------------------------------------------------------------------------------------
CSS Outline

Exercise 1
<style>
div {
outline-style: solid;
outline-width: 5px;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>

Exercise 2
<style>
div {
  outline-style: solid;
  outline-width: 5px;
  
outline-color: red;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>

Exercise 3
<style>
div {
  
outline: 4px dotted red;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>
---------------------------------------------------------------------------
CSS Text

Exercise 1
<style>
p {
  
color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2

<style>
p {
  
text-align: center;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
a {
  
text-decoration: none;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <a href="http://w3schools.com">This is a link</a>
</body>

Exercise 4

<style>
h1 { 
text-transform: uppercase;
}
p {
text-transform: capitalize;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
</body>

Exercise 5
<style>
p {
text-indent: 20px;
}
</style>

<p>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</p>
------------------------------------------------------------------------------------------------------------------
CSS Font

Exercise 1
<style>
h1 { font-family: Verdana;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
</body>

Exercise 2
<style>
h1 {  
font-style: italic;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
h1 {
  
font-size: 50px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
</body>

Exercise 4
<style>
p {font-weight: bold;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>  
</body>

Exercise 5
<style>
p {
  
font-variant: small-caps;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>  
</body>
------------------------------------------------------------------------------------
CSS Links

Exercise 1

<style>
a{
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <a href="http://w3schools.com">This is a link</a>
</body>

Exercise 2
<style>
a:hover{
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <a href="http://w3schools.com">This is a link</a>
</body>

Exercise 3
<style>
a:visited{
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <a href="http://w3schools.com">This is a link</a>
</body>

Exercise 4
<style>
/* unvisited link */
a:link{text-decoration: none;}

/* visited link */
a:visited{text-decoration: none;}

/* mouse over link */
a:hover{text-decoration: underline;}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <a href="http://w3schools.com">This is a link</a>
</body>
----------------------------------------------------------------------------------------------------
CSS Lists

Exercise 1
<style>
ul {
list-style-type: square;
}
</style>

<body>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>
</body>

Exercise 2
<style>
ul {
  list-style-image: url("bling.jpg");
}
</style>

<body>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>
</body>

Exercise 3
<style>
ul {
  
list-style-type: none;
}
</style>

<body>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>
</body>

Exercise 4
<style>
ol {
  
list-style-type: upper-roman;
}
</style>

<body>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ol>
</body>
----------------------------------------------------------------------------------------
CSS Tables

Exercise 1
<style>
table, th, td{
  border: 2px solid green;
}
</style>

<body>
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>
</body>

Exercise 2

<style>
table {
  
border-collapse: collapse;
}

table, th, td {
  border: 1px solid green;
}
</style>

<body>
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>
</body>

Exercise 3
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>

Exercise 4

<style>
table, th, td {
  border: 1px solid green;
}

td{
  text-align: right;
}
</style>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>

Exercise 5
<style>
table, th, td {
  border: 1px solid green;
}

th{  
padding: 15px;
}
</style>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>

Exercise 6
<style>
table, th, td {
  border: 1px solid green;
}

th {
background-color: lightblue;
}
</style>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>
--------------------------------------------------------------------------
CSS Display/Visibility

Exercise 1
<style>
h1 {
  
visibility: hidden;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2
<style>
h1 {
  
display: none;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
li{
display: inline;
}
</style>

<body>
<ul>
  <li>Apple</li>
  <li>Orange</li>
  <li>Pear</li>
</ul>
</body>

Exercise 4

<style>
strong{display: block;
}
</style>

<body>
<h1>This is a Heading</h1>
<p>This is a <strong>paragraph</strong></p>
</body>
----------------------------------------------------------------------
CSS Positioning

Exercise 1
<style>
h1 {
position: fixed;
  
top: 50px;  
right: 10px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2 
<style>
h1 {
  
position: relative;
  top: 50px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
h1 {
  
position: absolute;
  top: 50px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4
<style>
.myheader{
  
position: relative;
  top: 50px;
}
</style>

<body>
  <h1 class="myheader">This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
----------------------------------------------------------------------------------------
CSS Z-index

Exercise 1
<style>
#mytitle{
  position: absolute;
  top: 0;
  z-index: 1;  
}
#myintro{
  position: absolute;
  top: 0;
  z-index: 0;
}
</style>

<body>
  <h1 id="mytitle">This is a heading</h1>
  <p id="myintro">This is a paragraph</p>
</body>
---------------------------------------------------------------
CSS Overflow

Exercise 1
<style>
.intro {
  width: 200px;
  height: 70px;
  overflow: scroll;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>

Exercise 2
<style>
.intro {
  width: 200px;
  height: 70px;
  overflow: hidden;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>

Exercise 3
<style>
.intro {
  width: 200px;
  height: 70px;
  overflow-x: scroll;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>
-----------------------------------------------------------------------------
CSS align

Exercise 1
<style>
.intro {
  width: 200px;
  margin: auto;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>

Exercise 2
<style>
.intro {
  width: 200px;
  margin: auto;
  position: absolute;
  right: 0px;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>
-----------------------------------------------------------------------------------------------------------------------------------
CSS Combinators

Exercise 1

<style>
div p{
  color: red;
}
</style>

<body>

<div>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</div>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>

Exercise 2
<style>
div > p{
  color: red;
}
</style>

<body>

<div>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</div>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>

Exercise 3
<style>
div + p{
  color: red;
}
</style>

<body>

<div>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</div>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>

Exercise 4
<style>
div ~ p{
  color: red;
}
</style>

<body>

<div>
  <p>This is a paragraph.</p>
  <p>This is a paragraph.</p>
</div>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
---------------------------------------------------------------------------------------
CSS Pseudo-classes

Exercise 1
<style>
a:hover{
  background-color: red;
}
</style>

<body>

<h1>This is a header.</h1>
<p>This is a paragraph.</p>
<a href="https://w3schools.com">This is a link.</a>

</body>

Exercise 2
<style>
.master:hover{
  background-color: red;
}
</style>

<body>

<h1 class="master">This is a header.</h1>
<p class="master">This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>

Exercise 3
<style>
p:first-child{
  background-color: red;
}
</style>

<body>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>

Exercise 4
<style>
input:focus{
  background-color: red;
}
</style>

<body>

<form>
  Name:
  <input type="text" name="fname">
  Age:
  <input type="text" name="age">
</form>

</body>
-----------------------------------------------------------------
CSS Pseudo-elements

Exercise 1
<style>
.intro::first-line{
  background-color: red;
}
</style>

<body>

<p class="intro">
In my younger and more vulnerable years
my father gave me some advice that I've
been turning over in my mind ever since.
'Whenever you feel like criticizing anyone,' he told me,
'just remember that all the people in this world
haven't had the advantages that you've had.'
</p>

</body>

Exercise 2
<style>
.intro::first-letter{
  background-color: red;
}
</style>

<body>

<p class="intro">
In my younger and more vulnerable years
my father gave me some advice that I've
been turning over in my mind ever since.
'Whenever you feel like criticizing anyone,' he told me,
'just remember that all the people in this world
haven't had the advantages that you've had.'
</p>

</body>

Exercise 3
<style>
p::before {
content: url('smiley.gif');
}
p::after {  
content: url('smiley.gif');
}
</style>

<body>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
----------------------------------------------------------------------------------------------
CSS Opacity

Exercise 1
<style>
img {
  opacity: 0.5;
}
</style>

<body>
  <img src="klematis.jpg" width="150" height="113">
</body>

Exercise 2
<style>
img {
  opacity: 0.4;
}
img:hover {
  opacity: 1.0;
}
</style>

<body>
  <img src="klematis.jpg" width="150" height="113">
</body>
----------------------------------------------------------------------------------------------------------
CSS Attribute Selectors

Exercise 1
<style>
a[target]{
  background-color: red;
}
</style>

<body>
  <a href="https://w3schools.com">w3schools.com</a>
  <a href="http://disney.com" target="_blank">Disney.com</a>
  <a href="http://wikipedia.org" target="_top">wikipedia.org</a>
</body>

Exercise 2
<style>
a[target="_blank"]{
  background-color: red;
}
</style>

<body>
  <a href="https://w3schools.com">w3schools.com</a>
  <a href="http://disney.com" target="_blank">Disney.com</a>
  <a href="http://wikipedia.org" target="_top">wikipedia.org</a>
</body>

Exercise 3
<style>
img[title~="blue"]{
  border: 5px solid red;
}
</style>

<body>
  <img src="klematis.jpg" title="blue flower">
  <img src="klematis2.jpg" title="purple flowers">
  <img src="klematis3.jpg" title="two blue flowers">  
</body>

Exercise 4
<style>
img[title^="blue"]{
  border: 5px solid red;
}
</style>

<body>
  <img src="klematis.jpg" title="blue flower">
  <img src="klematis2.jpg" title="purple flowers">
  <img src="klematis3.jpg" title="two blue flowers">  
</body>

Exercise 5
<style>
img[title$="flower"]{
  border: 5px solid red;
}
</style>

<body>
  <img src="klematis.jpg" title="blue flower">
  <img src="klematis2.jpg" title="purple flowers">
  <img src="klematis3.jpg" title="two blue flowers">  
</body>

Exercise 6
<style>
img
[title*="flower"] {
border: 5px solid red;
}
</style>

<body>
  <img src="klematis.jpg" title="blue flower">
  <img src="klematis2.jpg" title="purple flowers">
  <img src="klematis3.jpg" title="two blue flowers">  
</body>
--------------------------------------------------------------------------------------------
CSS Rounded Corners

Exercise 1
<style>
div {
  background: red;
  border-radius: 10px;  
}
</style>

<body>
  <div>This is a div element. It has some text.</div>
</body>

Exercise 2
<style>
div {
  background: red;
  border-bottom-left-radius: 10px;  
}
</style>

<body>
  <div>This is a div element. It has some text.</div>
</body>
------------------------------------------------------------------------------------------------------------
CSS Border Images

Exercise 1
<style>
div {
  border: 10px solid transparent;
  border-image: url(border.png) 30 round;
}
</style>

<body>
  <div>This is a div element. It has some text.</div>
</body>

Exercise 2
<style>
div {
  border-image-source: url(border.png);
  border-image-repeat: stretch;  
  border-image-slice: 30;
}
</style>

<body>
  <div>This is a div element. It has some text.</div>
</body>
-------------------------------------------------------------------------------------------------------------------
CSS Backgrounds

Exercise 1
<style>
body {
  background-image: url('img2.gif'), url('img1.gif');
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2
<style>
body {
  background-image: url('img1.gif');
  
background-size: 100px 80px;
  background-repeat: no-repeat;  
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
body {
  background-image: url('img1.gif'), url('img2.gif');
  background-repeat: no-repeat, no-repeat;
  background-position: left top, right top;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4

<style>
#example1 {
  padding: 20px;
  background-image: url('img1.gif');
  background-repeat: no-repeat;
  background-origin: content-box;
}
</style>

Exercise 5
<style>
#example1 {
  border: 10px dotted red;
  padding: 20px;
  background-color: yellow;
  background-clip: padding-box;
}
</style>
--------------------------------------------------------------------------------------------------------------------
CSS Colors

Exercise 1
<style>
h1 {
  background-color: rgba(255, 0, 0, 1.0);
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 2

<style>
h1 {
  background-color: hsl(0, 100%, 50%);
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 3
<style>
h1 {
  background-color: hsla(0, 100%, 50%, 0.3);
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

Exercise 4
<style>
h1 {
  background-color: rgb(255, 0, 0);
  opacity: 0.3;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
