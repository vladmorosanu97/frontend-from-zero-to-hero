## Test 2 - HTML5 && CSS3

### 1. CSS3 questions and answers

1. What is CSS?

   * Cascading Style Sheets, fondly referred to as CSS, is a simply **design language** intended to simplyfi the process of making web pages    presentable.
   
2. What are all the ways to apply CSS rules to a web page?

   * **Inline** - It is by adding style attribute in the HTML element and then adds the rules. Though it is easy, it is not a best practice.
   * **Inline/Internal** - Adding the ``<style>`` element in the document, preferably in the head, and then place our rules.
   * **External/Linked** - CSS rules are placed in .css file and then using ``<link>`` element link the CSS files in the document.

3. What are the components of a CSS Style for an element?

   * A style rule is made of **three** parts: 
   
        * selector - A selector is an HTML tag at which a style will be applied
        * property - A property is a type of attribute of HTML tag.
        * value - Values are assigned to properties
   
4. Explain the CSS selectors.

   * There are classes, id, type-selectors, attributes, pseudo-classes and pseudo-elements in CSS. The most common is class and id        selectors.

5. What is type selector?

   * Type selector quite simply matches the name of an element type. For example, if you want to give a color to all level 1 headings      you need to type like this:
   ```
   h1 {
      color: #36CFFF;
   }
   ```
   
6. What is class selector?
  
   * The ``.class`` selector selects elements with a specific class attribute. Class selectors are called by adding a ``.`` and 
  then insert a class name.
  
7. What is id selector? 

   * You can define style rules based on the id attribute of the elements. Example:
   ```
   #black {
      color: #000000;
   }
   ```
 
8. What is pseudo-selectors? What are they used for?

   * There is two type of pseudo-selectors: **pseudo-elements** and **pseudo-classes**.
   * A pseudo-element is a keyword added to a selector that lets you style **a specific part** of the selected element(s).
    ```
    p::first-line {
      color: blue;
      text-transform: uppercase;
    }
    ```
   
   * A pseudo-class is used to add **additional efects** to selected HTML. For example to style an element when a user mouses over it, to       style visited and unvisited links differently or style an element when it gets focus
  
    ```
    a:hover {
      color: #FF0000;
    }
    ```
9. What is a Child selector?

   * Child selectors are another way to group and style a set of elements that **descend from a parent** element
   * Child selectors contains ``>`` between the parent and child.

10. What is an attribute selector?

    * You can also apply styles to HTML elements with particular attributes.
    * The style rule below will match all the input elements having a type attribute with a value of text.
     ```
     input[type="text"] {
          color: #000000;
     }
     ```

11. How to select all paragraph elements with a lang attribute?

    * The selector ``p[lang]`` selects all paragraph elements with a lang attribute

12. What is ``float`` property in CSS?

    * In float, CSS allow an element to be positioned horizondally, allowing elements below the floated element to flow around it
    * Floats can only accept a ``left`` and ``right`` value.

13. What is CSS Box model and its used?  

    * CSS Box model is a made up of margins, borders, padding and content. Box model provides a **structured way** to space elements in     a relationship to each other.

14. Is there a way to restore the default property value using CSS?

    * This is not an easy way to restore the default property. But we can use ``inherit`` value, which will restore it to the default.

15. What is ``inline``, ``inline-block`` and ``block``? How they are different from each other?

    * A **block** element is an element that takes up the full width available and has a line break before and after it. 
    ``<h1>``, ``<p>``, ``<li>`` are examples of block elements.
    * An **inline** element only takes up as much width as necessary, cannot accept width and height values and does not force line   breaks. ``<a>`` and ``<span>`` are examples of inline elements.
    * **Inline-block** is similar to inline, but it can take height, width or margin values.

16. What is the purpose of the ``z-index`` and how is it used?

    * The ``z-index`` helps specify the stack order of positioned elements that may overlap one another.
    * The ``z-index`` default value is zero and can take on either a positive or negative number.
    * An element with a higher ``z-index`` is allways stacked above one with a lower index.
    
17. What is ``vh``, ``vw``and ``vmin`` measurement unit?
    
    * CSS3 has some new values for sizing things relative to the current viewport size: vw, vh, and vmin.
    * Any of the three values is 1% of the viewport axis. "Viewport" == browser window size == window object. If the viewport is 40cm   wide, 1vw == 0.4cm.
    * 1vw = 1% of viewport width.
    * 1vh = 1% of viewport height.
    * 1vmin = 1vw or 1vh, whichever is smaller.
    * 1vmax = 1vw or 1vh, whichever is larger.

18. Which property is used to set the background color of an element?

    * ``background-color`` set a specific backgroud color to an element. Like this: 
    ```
    body {
        background-color: #000000;
    }
    ```

19. Is there any possible to add multiple background images?

    * Yes, it is possible in CSS3.
    * These are layered atop one another with the first background you provide on top and the last background listed in the back.
    * Only the last background can include a background color.
    
20. Which property is used to controll the scrolling of an image in the background?

    * The ``background-attachement`` property is used to control the scrolling of an image in the background.

21. Explain de difference between ``visibility: hidden`` and ``display: none``?

    * ``visibility: hidden`` simply hides the element, while it will still take up space and affect the layout of the document.
    * ``display: none`` also hides the element, but will not take up space and the page will appear as if the element is not present
    
22. How can you apply a CSS rule to all elements?

    * We can use ``*`` selector to apply a rule globally for all elements. Though it is not a good idea, we can use it for resetting margin and padding.

23. How can you center a ``div`` element in a page?

    * We can center an element by applying ``margin-left`` and ``margin-right`` to auto.

24. What are all the values of position attribute in CSS? What is the diffference between all the positions?

    * Possible position values are ``static``, ``relative``, ``absolute``, ``fixed``, ``inherit``, ``initial``.
    * **Static possition**: The element is positioned according to the normal flow of the document. The top, right, bottom, left, and z-index properties have no effect. This is the default value.
    * **Relative possition** is possitioning the element to the normal flow of the document, and then offset relative to itself based on the values of top, right, bottom, and left.
    * **Absolute possition** remove the element from the document flow. That means they have no effect at all on their parent element. An absolutely positioned  element will therefore overlap other content unless you take action to prevent it.
    * **Fixed possition**: The element is removed from the normal document flow, and no space is created for the element in the page layout. This value always creates a new stacking context. In printed documents, the element is placed in the same position on every page.
    * **Inherit possition** inherits their possition property from its parent element.
    * **Initial possition** sets this property to its default value.
    
25. What is Flexbox in CSS3? 

    * Flex layout is superficially similar to block layout.
    * It is simple and powerful tool for distributing space and aligning content in ways that web apps and complex web pages often need.
    * With flex, we can easily arrange the elements in rows or columns.

26. What are all the units we can use in CSS3?
  
    * We can use ``px``, ``pt``, ``cm``, ``em``, ``rem``, ``in``, ``vim`` and ``vmax``.

27. What is the difference between em and rem?

    * ``em`` unit is relative to the font-size of its direct or nearest parent. What it means is: ``1em = 20px`` if a selector has a ``font-size of 20px``. 
    * ``rem`` unit is only relative to the html (root) font-size.

28. What would be the difference between ``width: auto`` and ``width: 100%`` in  CSS?
    
    * ``width: auto`` reaches to the full width and it will subtract borders, paddings and margins from available space. 
    * ``width: 100%`` will force the element to be as wide as its parent element and will add additional spacing which can cause some       problems. 

29. What is ``@import`` rule in CSS3?

    * The ``@import`` CSS **at-rule** is used to import style rules from other style sheets. These rules must precede all other types of rule.

30. What is difference between ``nth-of-type`` and ``nth-child``?

    * ``:nth-child()`` and ``:nth-of-type()`` pseudo-classes allow you to select elements with a formula.
    * The ``:nth-child(n)`` select _n_ th child of the parent.
    * The ``:nth-of-type()`` considers element of the given type.
    
    
------------------------------------------------------------------------------------------------------------------------------------

Resources: 

* UI Developer Interview Q&A mobile APP
* Interview Question and Answers mobile APP
* [CSS Tutorial W3schools](https://www.w3schools.com/css/default.asp)

