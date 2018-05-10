# FrontEndFromZeroToHero - Week 2

## Test 2 - HTML && CSS

### 1. HTML Questions


1. What is HTML?

    * HTML stands for Hyper Text Markup Language. It is a language of World Wide Web. It is a **standard text formatting language** which is used to create and display pages on the Web
    
2. What are Tags?

    * Tags are a set of characters that provide the directions or recipes for the visual content that one sees on the Web.
    * HTML tags are composed of two things: **opening tag** and **ending tag**. Some tags are unclosed tags. 
    Examples: ``<p></p>``, ``<div></div>``, ``<h1></h1>``, ``<span>``.
    
3. Do all HTML tags have end tag?
  
    * No. There are some HTML tags that don't need a closing tag. For example: ``<image>`` tag, ``<br>`` tag, ``<hr> tag``.
    
4. What is the difference between HTML elements and tags?

    * HTML elements communicate to the browser to render text. When the elements are surrounded by brackets <>, they form HTML tags. Most of the time, tags come in pair and surround content.

5. What is Semantic HTML?
  
    * Semantic HTML is an element which **express its meaning**. In Semantic HTML, tags like ``<b></b>`` for bold and ``<i></i>`` for italic
    should not be used, reson being they just represent formatting, and provide no indication of meaning or structure.
    
    * The semantically correct thing to do is use ``<strong></strong>`` and ``<em></em>`` and will have the same bold and italic effects, while demmonstrating
    meaning and structure. Some of the semantic tags are: ``<footer>``, ``<header>``, ``<nav>``, ``<section>``, ``<article>``, ``<aside>``, 
    ``<figure>`` and ``<figcaption>``
    
6. What is SVG?

    * SVG is the abbreviation for Scalable Vector Graphics and is recommended by W3C for creating vector graphics wich support for interactivity
    and animation. SVG graphics **do not lose its quality** when they are zoomed or resized
    
7. What is ``<!DOCTYPE>``? Is it mandatory?

    * Yes, ``<!DOCTYPE>`` is mandatory. It is used to instruct the browser about the version of our HTML document. In older versions we must include the version of the HTML we are using.
    In HTML 5, it is very much simplified which is just ``<!DOCTYPE>``. 
    
8. What is the difference between ``<section>``, ``<div>`` and ``<article>``?

    * The ``<section>`` element represents a generic section of a document or application. A section in this context, is a thematic grouping af content typically with a heading.
    
    * The ``<div>>`` element has no special meaning at all. It represents its children. It can be used with the calss, lang, and title attributes to
    mark up semantics common to a group of consecutive elements.
    
    * The ``<article>`` represents a complete, or self-contained, composition in a document, page or site and that is, in principle, 
    independently distributable or reusable. This could be a forum post, a magazine or newspaper article, a comment or any other independent item of content

9. How can we link an Email address in a web page?

    * We can use **mailto:** in the href for email, like ``<a href="mailto:mail@email.com">Email me"</a>``.
     
10. What is Application cache?

    * It is used to provide offline browsing of our app to the user.
     
11. What is the difference between ``<div>`` and ``<frame>``?

   
    * A ``<div>`` is a generic container element for grouping and styling, whereas a ``<frame>`` creates divisions within a web 
    page and should be used within the ``<frameset>``.
    
12. What is the use of span tag? Give one example.

    * The span tag is used for adding color on text, adding background on text or highlight any color text etc.
    
    * Example:
    ``` 
       <p>  
         <span style="color:#ffffff;"> In this page we use span. </span>  
       </p>
    ```
    
13. What is the difference between ``<iframe>``, ``<embed>`` and ``<object>``?

    * The HTML Inline Element ``<iframe>`` represents a nested browsing context, effectively embedding anther HTML page in the current       page.
    
    * The HTML ``<embed>`` element represents an integration point for an expternal application or interactive context (in other words,     a plug-in).
    
    * The HTML ``<object>`` element represents an externall resource, which can be treated as an image or nested browsing context.
    
14. What is the difference between ``alt=" "`` text and ``title=" "`` text in HTML image element?

    * The required **alt** attribute specifies an alternate text for an image, if the image cannot be displayed.
    * The **title** attribute specifies extra information about an element. The information is the most often show as a tooltip text when the mouse moves over the element. 
    
15. Are HTML tags case sensitive? 

   * No. :D
   
   This code ...
   ```
     <!DOCTYPE html>
     <html>
       <head>
         <meta charset="utf-8" />
         <title>Page Title</title>
         <meta name="viewport" content="width=device-width, initial-scale=1">
         <link rel="stylesheet" type="text/css" media="screen" href="main.css" />
         <script src="main.js"></script>
       </head>
       <body>
         <h1>Title page</h1>
       </body>
     </html>
  ```
  or 
  ```
     <!DOCTYPE html>
     <HTML>
       <HEAD>
         <META charset="utf-8" />
         <TITLEe>Page Title</TITLE>
         <META name="viewport" content="width=device-width, initial-scale=1">
         <LINK rel="stylesheet" type="text/css" media="screen" href="main.css" />
         <SCRIPT src="main.js"></SCRIPT>
       </HEAD>
       <BODY>
         <H1>Title page</H1>
       </BODY>
     </HTML>
  ```
  will works perfectly in the both cases.
  
16. How to insert a copyright symbol on a browser page? 

   * You can insert a copyright symbol by using &copy; or &#169; in an HTML file.
   
17. Does a hyperlink only apply to text?
    
    * No. You can use hyperlinks on text and images both.
    
18. What are empty elements?

    * HTML elements with no content are called empty elements. For example: ``<br>``, ``<hr>`` etc.
    
19. Which of the following HTML elements are non-semantic?

    * Sematic refers to the meaning of a piece of code. For example, the ``<h1>`` element is semantic because the text wrapped aroung its tags indicates > a top-level heading of the page. 
    * Elements ``<div>`` and ``<span>`` don't have any semantic meaning.
    
20. Chose block elements: 

    * A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
    * The block elements from that list are: ``<div>``,  ``<h3>``, ``<p>`` and ``<table>``. 
