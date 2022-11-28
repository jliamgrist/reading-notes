# Read: Class 01

Understanding how websites work is important, because without an understanding you would have a hard time debugging why certain parts or functionalities of a website may not be working. 

[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

## Poem:

Like a good coffee shop
The web gives it to you while it's hot
Your device is the client
The server provides without a drop. 
There's no 25% tip to use TCP/IP,
Just give that IP address a ping,
and the CSS will com back squeeky clean.

## How files are parsed:

The browser parses the HTML file first, and looks for links to CSS and Javascript. It sends requests back to the server for any CSS files it has found, and any Javascript. It generates a DOM tree from the HTML, the structure of the CSS, and compiles any Javascript. As the DOM tree is built, the CSS styles are applied, and the Javascript is executed. A visual representation of the page is painted to the screen which allows the user to see and interact with the website.

## Design

Finding assets and images is easiliy done by copying the link to the image/asset.

## Javascript

A sting is created using quotation marks. A number can be declared using the number without quotes. 

A variable stores the placement of some data or value so that it can be referenced in your code. 

[Javascript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## Introduction to HTML

### Elements to Form a Webpage:

```
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

### HTML attributes:
Go inside the element
> `href="https://www.mozilla.org/"`

### HTML elements:
Have an opening and closing tag
> `<a></a>`

_Together they make up use code_
> `<a> href="https://www.mozilla.org/" </a>`

An `<article>` encloses a block of related content that makes sense on it's own (a blog post).

A `<section>` is for grouping together a part of a page that consittues one single piece of functionality, and should have a heading.

A typicle website will use semantic tags:
```
header: <header>.
navigation bar: <nav>.
main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
sidebar: <aside>; often placed inside <main>.
footer: <footer>.
```

Search engines will use HTML tags to generate metadata so that a search engine knows what a page is about and can display approprate results to a user.

Metadata can be "officially" added to a website using the <meta> HTML tag. Metadata is used to describe additional information about a website and is good for optimoizing for SEO, adding a favicon, reading language correctly, etc. 

## How to Design a Website

+ What do you want to accomplish? What is the vision? The goal? Define this clearly before you start.
+ Next, break the vision down into smaller actionable steps/tasks

## Semantics

Use the appropriate semantic element so that your website is readable and accessible to all

## Javascript

Add javascript to an HTML document by inserting the <script></script> tag. 

Use javascript for things like:

+ Showing or hiding information with the clieck of a button
+ Playing audio/video on a page
+ Displaying an animation


## Things I want to know more about
I'm so excited to begin to understand how APIs work and how I can send a request, and recieve a response from another server. 
