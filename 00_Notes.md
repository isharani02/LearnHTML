# HTML Notes

## Introduction

```HTML
<p>HTML stands for Hyper Text Markup Language.It is a standard language used to creat and give structure to the web page.</p>
<p>It tells the web browser how to display text, links, images, and other forms of multimedia on a webpage</p>
<p>This is my first program.</p>
<h3>Hello World!</h3>
```

## Basic HTML Structure

```html

```

## Headings

```html
<!-- The HTML heading tags are used to create headings for the content of a webpage. 
These tags are typically placed inside the body tag.  -->
Syntax:
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>

<!--Heading tags-->
<p>
  There are six levels of heading tags h1 to h6,each serving different puropse
  in structuring your content.
</p>
<p>h1 consider as a main heading and rest of all consider as subheadings.</p>
<h1>This is the Main Heading</h1>
<h2>This is a Subheading</h2>
<h3>This is a Smaller Subheading</h3>
<h4>This is a Sub-Subheading</h4>
<h5>This is a Minor Subheading</h5>
<h6>This is the Smallest Heading</h6>
```

## Paragraph

```html
<!-- Paragraph tags -->

<!-- A paragraph in HTML is simply a block of text enclosed within the <p> tag. -->
Syntax:
<p>Some Content...</p>

<p>This is a paragraph tag.</p>
<p>
  The paragraph tag helps divide content into manageable, readable sections. .
</p>
```

## Break

```html
<!-- Break tag -->

<!-- The HTML <br> tag element creates a line break, giving you a new line without starting a new paragraph. 
Use <br> when you want to move to the next line without beginning a whole new paragraph. -->

Syntax:
<br />

<p>
  This paragraph has multiple
  <br />lines. But HTML reduces them <br />to a single line, omitting <br />the
  carriage return we have used.
</p>
```

## Image

```html
Syntax:
<img src="url" alt="alternatetext">

<!-- The HTML <img> tag is used to embed an image in a web page. -->

<h2>HTML Image</h2>
<p>Adding an image in a HTML page.</p>

<!-- Image tag has two attributes src and alt, and does not have a closing tag -->
<img
  src="https://www.w3schools.com/tags/img_girl.jpg"
  alt="Girl in a jacket."
>
```

## Hyperlink
````html
Syntax:
      <a href=""></a>

<!-- In HTML, anchor tag creats a Hyperlink to web pages,files,emails,addresses etc.-->

    <h2>HTML Links</h2>
    <p>We are adding a hyperlink to a webpage using anchor tag.</p>
    <a href="https://wwww.google.com">google.com</a>
````
## Lists
````html
    <!-- In HTML we can creat list using <li></li>tag.
     Each tag starts with a <li> and ends with a </li> tag. -->

    <!-- There are two types of list: Order list and Unorder list. -->
    <h2>An order list</h2>
    <ol>
      <li>Mango</li>
      <li>Orange</li>
      <li>Guava</li>
    </ol>

    <h2>An unorderd list</h2>
    <ul>
      <li>Milk</li>
      <li>Tea</li>
      <li>Sugar</li>
    </ul>
````
## Table

```html
<p>Creating a table.</p>
<!-- A table in HTML consist of table cells inside rows and columns. -->
<table>
  <!-- tr stands for table row.Each table row start with a <tr>and ends with a </tr>tag. -->
  <tr>
    <!-- td stands for table data.Each table cell is defined by a <td>and ends with a </td> tag. -->
    <td>Column1</td>
    <td>Column2</td>
    <td>Column3</td>
  </tr>
</table>
<table>
  <tr>
    <!-- th stands for table head.Each table head starts with a <th> and ends with a </th> tag. -->
    <th>Name</th>
    <th>Email</th>
    <th>DOB</th>
  </tr>
</table>
<table>
  <tr>
    <td>Isha</td>
    <td>isharani01@gmail.com</td>
    <td>02/09/2005</td>
  </tr>
</table>
<table>
  <tr>
    <td>Manasvi</td>
    <td>Manasvi01@gmail.com</td>
    <td>02/10/2005</td>
  </tr>
</table>
```
