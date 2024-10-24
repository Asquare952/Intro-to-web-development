# CSS Introduction

CSS is the language we use to style a Web page.

### What is CSS?

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files.

### Why Use CSS?

CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

### CSS Example

``` css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```

### CSS Solved a Big Problem
HTML was NEVER intended to contain tags for formatting a web page!

HTML was created to describe the content of a web page, like:

`<h1>` This is a heading `</h1>`

`<p>` This is a paragraph. `</p>`

When tags like `<font>`, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.

To solve this problem, the World Wide Web Consortium (W3C) created CSS.

CSS removed the style formatting from the HTML page!

### CSS Saves a Lot of Work!

The style definitions are normally saved in external .css files.

With an external stylesheet file, you can change the look of an entire website by changing just one file!

# CSS Syntax

### CSS Syntax

A CSS rule consists of a selector and a declaration block.

![css](https://www.w3schools.com/css/img_selector.gif)

The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

# HTML Table Borders

### How To Add a Border

To add a border, use the `border` property on `table`, `th`, and `td` elements:

### Example

``` css
table, th, td {
  border: 1px solid black;
}
```

### Collapsed Table Borders

To avoid having double borders like in the example above, set the CSS `border-collapse` property to `collapse`.

This will make the borders collapse into a single border

### Example

``` css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
```

### Dotted Table Borders

With the `border-style` property, you can set the appearance of the border.

The following values are allowed:

- dotted
- dashed
- solid
- double
- groove
- ridge
- inset
- outset
- none
- hidden

### Example

``` css
 th, td {
  border-style: dotted;
}
```

### Border Color

With the `border-color` property, you can set the color of the border.

### Example

``` css
  th, td {
  border-color: #96D4D4;
}
```

### HTML Table - Cell Padding

Cell padding is the space between the cell edges and the cell content.

By default the padding is set to 0.

To add padding on table cells, use the CSS `padding` property:

### Example

``` css
  th, td {
  padding: 15px;
}
```

To add padding only above the content, use the `padding-top` property.

And the others sides with the `padding-bottom`, `padding-left`, and `padding-right` properties:

### Example

``` css
  th, td {
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 30px;
  padding-right: 40px;
}
```

### HTML Table - Cell Spacing

Cell spacing is the space between each cell.

By default the space is set to 2 pixels.

To change the space between table cells, use the CSS `border-spacing` property on the table element:

### Example

``` css
  table {
  border-spacing: 30px;
}
```

## HTML Table Styling

### HTML Table - Zebra Stripes

If you add a background color on every other table row, you will get a nice zebra stripes effect.

To style every other table row element, use the `:nth-child(even)` selector like this:

### Example

``` css
tr:nth-child(even) {
  background-color: #D6EEEE;
}
```

**Note:** If you use `(odd)` instead of `(even)`, the styling will occur on row 1,3,5 etc. instead of 2,4,6 etc.

### HTML Table - Vertical Zebra Stripes

To make vertical zebra stripes, style every other column, instead of every other row.

Set the `:nth-child(even)` for table data elements like this:

### Example

``` css
td:nth-child(even), th:nth-child(even) {
  background-color: #D6EEEE;
}
```

**Note:** Put the :nth-child() selector on both th and td elements if you want to have the styling on both headers and regular table cells.


### Combine Vertical and Horizontal Zebra Stripes

You can combine the styling from the two examples above and you will have stripes on every other row and every other column.

If you use a transparent color you will get an overlapping effect.

Use an `rgba()` color to specify the transparency of the color:

### Example

``` css
tr:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}

th:nth-child(even),td:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
```

### Horizontal Dividers

If you specify borders only at the bottom of each table row, you will have a table with horizontal dividers.

Add the `border-bottom` property to all `tr` elements to get horizontal dividers:

### Example

``` css
tr {
  border-bottom: 1px solid #ddd;
}
```

### Hoverable Table

Use the :hover selector on tr to highlight table rows on mouse over:

### Example

``` css
tr:hover {background-color: #D6EEEE;}
```

# CSS Selector Reference

### CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

| Selector      | Example                                                                                                                                                                   |                   Example description                   |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| #id | #firstname |  Selects the element with id="firstname" |
| * | * | Selects all elements |
| element | p | Selects all `<p>` elements |


### CSS Class Selectors

The class selector selects HTML elements based on the value of their class attribute.

| Selector      | Example                                                                                                                                                                   |                   Example description                   |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| #id | #firstname |  Selects the element with id="firstname" |
| * | * | Selects all elements |
| element | p | Selects all `<p>` elements |