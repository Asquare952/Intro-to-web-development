# HTML Introduction

HTML is the standard markup language for creating Web pages.

## What is HTML?

- HTML stands for **Hyper Text Markup Language**
- HTML is the standard markup **language** for creating **Web pages**
- HTML describes the **structure** of a **Web page**
- HTML consists of a series of **elements**
- HTML elements tell the **browser** how to display the content
- HTML elements label pieces of content such as **"this is a heading"**, **"this is a paragraph"**, **"this is a link"**, etc.

![html boiler plate](https://www.webfx.com/blog/wp-content/uploads/2014/07/ie9-support.png)

### Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document.
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<a>` element defines as a anchore tag .

### What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

`<tagname>` Content goes here... `</tagname>`
The HTML element is everything from the start tag to the end tag:

`<h1>`My First Heading`</h1>`

`<p>`My first paragraph.`</p>`

# Web Browsers

The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

![web browser](https://www.w3schools.com/html/img_chrome.png)

### HTML History

Since the early days of the World Wide Web, there have been many versions of HTML:

| Year      | Version                                                                                                                                                                    |                                      |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| 1989 | Tim Berners-Lee invented www |  
| 1991 | Tim Berners-Lee invented HTML |
| 1993 | Dave Raggett drafted HTML+ |
| 1995 | HTML Working Group defined HTML 2.0 |
| 1997 | W3C Recommendation: HTML 3.2 |
| 1999 | W3C Recommendation: HTML 4.01 |
| 2000 | W3C Recommendation: XHTML 1.0 |
| 2008 | WHATWG HTML5 First Public Draft |
| 2012 | WHATWG HTML5 Living Standard |
| 2014 | W3C Recommendation: HTML5 |
| 2016 | W3C Candidate Recommendation: HTML 5.1 |
| 2017 | W3C Recommendation: HTML5.1 2nd Edition |
| 2017 | W3C Recommendation: HTML5.2 |

# HTML Elements

**An HTML element is defined by a start tag, some content, and an end tag.**

The HTML **element** is everything from the start tag to the end tag:

`<tagname>`Content goes here...`</tagname>`
Examples of some HTML elements:

`<h1>` My First Heading `</h1>`

`<p>`My first paragraph.`</p>`


| Start tag     | Element content                                                                                                                                                                    |     End Tag                                 |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| `<h1>` | My First Heading |  `</h1>` |
| `<p>` | Tim Berners-Lee invented HTML | `</p>` |
| `<br>` | none | none |

**Note:** Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

## HTML is Not Case Sensitive

HTML tags are not case sensitive: `<P>` means the same as `<p>`.

## HTML Tag Reference

Tag reference contains additional information about these tags and their attributes.

| Tag     | Description                                                                                                                                                                    |                                     |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| `<html>` | Defines the root of an HTML document |
| `<body>` | Defines the document's body |
| `<h1>`to `<h6>` | Defines HTML headings |

## HTML Headings

HTML headings are titles or subtitles that you want to display on a webpage.

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

## Headings Are Important

Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

## HTML Lists

HTML lists allow web developers to group a set of related items in lists.

There are two types of lists:

- Unordered HTML List
- Ordered HTML List

### Unordered HTML List

An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

The list items will be marked with bullets (small black circles) by default

### Ordered HTML List

An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

The list items will be marked with numbers by default:

### HTML Description Lists

HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term:

### HTML List Tags

| Tag      | Description                                                                                                                                                                    |                                      |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| `<ul>` | Defines an unordered list |  
| `<ol>` | Defines an ordered list |
| `<li>` | Defines a list item |
| `<dl>` | Defines a description list |
| `<dt>` | Defines a term in a description list |
| `<dd>` | Describes the term in a description list |

# HTML Tables

HTML tables allow web developers to arrange data into rows and columns.

### Define an HTML Table

A table in HTML consists of table cells inside rows and columns.

### Example

A simple HTML table:

``` html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

#### Table Cells

Each table cell is defined by a `<td>` and a `</td>` tag.

**`td` stands for table data.**

Everything between `<td>` and `</td>` are the content of the table cell.

### Example

``` html
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
```

**Note:** A table cell can contain all sorts of HTML elements: text, images, lists, links, other tables, etc.

### Table Rows

Each table row starts with a `<tr>` and ends with a `</tr>` tag.

### Example

``` html
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```

You can have as many rows as you like in a table; just make sure that the number of cells are the same in each row.

**Note:** There are times when a row can have less or more cells than another. You will learn about that in a later chapter.

### Table Headers

Sometimes you want your cells to be table header cells. In those cases use the `<th>` tag instead of the `<td>` tag:

**`th` stands for table header.**

### Example

Let the first row be table header cells:

``` html
<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```

By default, the text in `<th>` elements are bold and centered, but you can change that with CSS.

### HTML Table Tags

| Tag      | Description                                                                                                                                                                    |                                      |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| `<table>` | Defines a table |  
| `<th>` | Defines a header cell in a table |
| `<tr>` | Defines a row in a table |
| `<td>` | Defines a cell in a table |
| `<caption>` | Defines a table caption |
| `<colgroup>` | Specifies a group of one or more columns in a table for formatting |
| `<col>` | Specifies column properties for each column within a `<colgroup>` element |
| `<thead>` | Groups the header content in a table |
| `<tbody>` | 	Groups the body content in a table |
| `<tfoot>` | 	Groups the footer content in a table |

## HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

### The `<form>` Element

The HTML `<form>` element is used to create an HTML form for user input:

``` html
<form>
.
form elements
.
</form>
```

The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc

### The `<input>` Element

The HTML `<input>` element is the most used form element.

An `<input>` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

| Type      | Description                                                                                                                                                                    |                                      |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| `<input type="text">` | Displays a single-line text input field |  
| `<input type="radio">` | Displays a radio button (for selecting one of many choices) |
| `<input type="checkbox">` | Displays a checkbox (for selecting zero or more of many choices) |
| `<input type="submit">` | 	Displays a submit button (for submitting the form) |
| `<input type="button">` | Displays a clickable button |

### Text Fields

The `<input type="text">` defines a single-line input field for text input.

### Example

A form with input fields for text:

``` html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

**Note:** The form itself is not visible. Also note that the default width of an input field is 20 characters.

### The `<label>` Element

Notice the use of the `<label>` element in the example above.

The `<label>` tag defines a label for many form elements.

The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.

The `<label>` element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.

The for attribute of the `<label>` tag should be equal to the id attribute of the `<input>` element to bind them together.

### Radio Buttons

The `<input type="radio">` defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.

### Example

A form with radio buttons:

``` html
<p>Choose your favorite Web language:</p>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```

### Checkboxes

The `<input type="checkbox">` defines a **checkbox**.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.

### Example

A form with checkboxes:

``` html
<p>Choose your favorite Web language:</p>

<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```

### The Submit Button

The `<input type="submit">` defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's **action** attribute.

### Example

A form with a submit button:

``` html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

### The Name Attribute for `<input>`

Notice that each input field must have a **name** attribute to be submitted.

If the **name** attribute is omitted, the value of the input field will not be sent at all.

### Example

This example will not submit the value of the "First name" input field: 

``` html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" value="John"><br><br>
  <input type="submit" value="Submit">
</form>
```
