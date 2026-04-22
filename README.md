# 2026WebReview
hahaha BEANS

HTML Review

What does HTML stand for?
HyperText Markup Language

What is the difference between <head> and <body>?
    <head> --> Metadate - read by the browser
    <body> --> This content displayed in the browser

Name THREE semantic HTML elements.
<header></header>
<footer></footer>
<main></main>
<nav></nav>
<article></article>
<aside></aside>
<section></section>

What attribute does an <a> tag need to create a link?
    href --> <a href="https://www.google.com">

What is a self-closing HTML tag? Give an example
Are tags that do not have closing tags also known as void elements
<br>
<img>
<link>
<meta>

What does <!DOCTYPE html> do?
This tells the browser that the file is an HTML file.

Every HTML file has the same SKELETON (Boilerplate, Template) structure:

<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", initial-scale="1.0">
        - Makes the page Responsive
</head>
<body>
    <header>
        <nav>Contains any Navigation Bar elements</nav>
    </header>
    <h1>Largest Heading/most important heading Only once per page</h1>
    <!-- All visible elements go in body -->
</body>
</html>

PART 2: Core HTML Elements
Headings 1 - 6 
<h1> --> There should be only 1
<h2> --> section titles, subtitles
<h3> --> sub-sections
<h4>
<h5> --> Fine Print (Copyright statements, etc.)
<h6> --> Even Finer Print (Copyright statements, etc.)

Text Elements
<p> --> paragraph tag
<strong> --> bold/important text - semantic weight
<em> --> italic/emphasized text - semantic weight
<br> --> line break (void element)
<u> --> underline
<hr> --> horizontal row ---------------------------------------------------------------> visual line divider (void element)
<span> --> inline element, does not create a line break
<mark> -- highlights text

HTML Lists

Unordered list --> bulleted list
- Used for: items with no ranking order
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

Ordered List --> numbered/alphabetized list
- used for steps, rankings, sequences, etc.
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

Links

How do I create a link to sllboces.org?
<a href="https://sllboces.org" target="_blank">SLL BOCES</a>

How do I create a link about.html - relative path (page in same directory)?
<a href="about.html">About</a>

Link to a file in the content folder?
<a href="content/page.html">Page</a>

A link to another section of the page?
<a href="#about"> Jump to the About Section</a>

A link to send an email?
<a href="mailto:student@sllboces.org">EMAIL ME NOW</a>

Images
What are the two required attributes for <img> tags?
alt - accessibility text
src - file path to the image

<img src="images/hero.jpg" alt="Adirondack Mountains in fall">
<img src="images/logo.png" alt="SLL BOCES Logo">

What is hot-linking an image?
- linking to an image somewhere on the internet
- Placeholder images for design purposes
- replace hotlinks before publishing the site
- If the hotlinked image gets moved, it will break your design

<img src="https://google.com/2/abc/files/images/myGoogleImage.png" alt="my hotlinked image">



Part 3
What is a semantic HTML element?
semantic elements describe the meaning of the content inside of the element, not just the way it looks

Reasons why we use semantic elements?
organization(teamwork) - allows other developers to more easily read and understand your code

Effects the Document Object Model - how the browser reads or understands the content

Accessibility - Allows screen readers to understand the structure and meaning behind content.

SEO - search engine optimization - how search engines rank well-structured pages - moves them higher in the search results

Semantic tags replaced the use opf <div> tags:
    <div> class="header" vs <header>

Layout Semantic Elements: header, nav, main, section, aside, footer

Content Semantic Elements:
<figure></figure> - image with caption
<figcaption> - caption for figure image
<time> - a date or time value
<address> - contact address info
<mark> -highlighted text
<details> / <summary> - expand and collapse more details
<div> - non-semantic container