# HTML Notes
This repo is mainly consistent of the information I am putting together on my journey to learn web development.

I plan to have a "Notes.md" file for each directory, and each directory will be a section of my learning journey. It will consist of the information I learned within the correlating topic. 

To start off, as this is the introduction to my repo, I'll discuss the concepts and terms I've learned about HTML on a basic level.

## HTML & CSS (HTML first)
Generally, these two *languages* are the fundamental building blocks of the web. HTML is the raw data that stands as the foundation of a webpage. CSS works closely with HTML because it gives HTML the styling it needs to make it look good. I emphasize language, because technically speaking, HTML and CSS are not *programming* languages. Rather than having to program logical functions, they work to present information. However, the third language I'll be learning about is JavaScript, which is indeed a programming language. 

### Elements & Tags
HTML consists of elements that are enclosed in these: <..> These are called HTML elements. 
*Most* elements have an opening and a closing tag which look something like this:
`<h1>...</h1>`
A closing tag is denoted by the forward slash '/' that precedes the element type.
A few examples that do not follow this notion are the img and meta tags. They simply hold the content without a closing tag like so:
`<img src="./images/dog.jpg">`

### HTML Boilerplate
An HTML Boilerplate is simply the basic groundwork needed to have a functional environment to write HTML. There are some prerequisites required to create an HTML file. Initially speaking, the HTML file has to end, or have, the .html extension. 

We then have to define the doctype through doctype declaration. This sets the version of HTML we'll be utilizing to render the document. This can be done with `<!DOCTYPE html>`.
Next, we provide the root element, which will be the `<html>` element: `<html lang="en"></html>`

> There are HTML attributes, which are supplemental information provided to HTML elements. the lang attribute shown above specifies the language of the content in the element.

After the root element, we implement the `<head>` element. This is an important necessity of any HTML document, as this is where we put important meta data about our webpage. It is important to note that there should not be any content in this element.

One of the tags that should alwasy be included in the head element is the `<meta>` tag: `<meta charset="utf-8">`
This defines the encoding of the webpage, which ensures that the characters and symbols will be displayed correctly.

The `<title>` element can also be included in the `<head>` element. This gives the webpage a readable name which is displayed in the tab header.

After this, we can now exit our head element with `</head>` and move onto the meat of the webpage, which is the `<body>` element. This is where most of the display information will be located. Tags such as `<p></p>` (paragraph), `<ul></ul>` (unordered list), and `<h1></h1>` (headers) are located here.
