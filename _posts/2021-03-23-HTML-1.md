---
layout:     post
title:      HTML Start from Zero (1)
subtitle:   HTML for Beginner
date:       2021-03-23
author:     Tingting
header-img: img/post-HTML.png
catalog: true
tags:
    - Web Dev
    - HTML
---

# What is HTML?
HTML is an abstraction of Hyper Text Markup Language. It is the standard markup language for creating Web pages. It tells the browser how to display the content as you like! If you want to create your own website, make it the way you like, HTML is the tool you need.


Here's an example of a very simple HTML document.

```
<!DOCTYPE html>
<html>
<head>
<title> This is is my Page Title </title>
</head>
<body>

<h1> First Heading! </h1>
<p> Hello, there~ This is my paragraph. </p>

</body>
</html>
```

- The <!DOCTYPE html> declaration defines that this document is an HTML5 document


# Element of an HTML
- Usually, an HTML element if consist of three part: a start tag, some content and an end tag.
$$\text{<tag-name> Contents </tag-name>}$$

    - The <html> element is the root element and it defines the whole HTML document.

    - Inside the <html> element there is a <body> element.

    - Headings: \<h1> - \<h6>
    - Paragraphs: \<p>
    - Links: \<a>
        - example: \<a href="http://zkdxtt21.github.io/">This is a link\</a>. 
        - It looks like: <a href="http://zkdxtt21.github.io/">This is a link</a>.
    - Images: \<img>
        - \<img src="yourphoto.jpg" alt="any-text-for-your-self" width="100" height="120">

- We also have empty HTML Elements. HTML elements with no content are called empty elements.
    - For example, the \<br> tag defines a line break. It is an empty element without a closing tag.

## Something to mention
- HTML is not case sensitive, but lowercase are recommended. (Some stricter document types requires lowercase, like XHTML)
- View any HTML source code as you like!  
Just right-click an HTML page and click "View Page Source", you can find the source code the website use. You can also choose "Inspect" to check one specific element.


# Editors for HTML
We can just use simple text editor (Notepad or TextEdit) to learn HTML :) 

Easily, you can edit the content we want. When you are finished, you can save the file with '.htm' as the suffix name and set the encoding to UTF-8. Then, you are ready to open it in your browser!


