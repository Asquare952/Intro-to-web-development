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

#   I n t r o - t o - w e b - d e v e l o p m e n t  
 