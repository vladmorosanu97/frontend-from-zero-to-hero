## Test 2 - HTML && CSS

### 1. CSS questions and answers

1. What is CSS?

   * Cascading Style Sheets, fondly referred to as CSS, is a simply **design language** intended to simplyfi the process of making web pages    presentable.
   
2. What are all the ways to apply CSS rules to a web page?

   * **Inline** - It is by adding style attribute in the HTML element and then adds the rules. Though it is easy, it is not a best practice.
   * **Inline/Internal** - Adding the ``<style>`` element in the document, preferably in the head, and then place our rules.
   * **External/Linked** - CSS rules are placed in .css file and then using ``<link>`` element link the CSS files in the document.

3. What are the components of a CSS Style for an element?

   * A style rule is made of **three** parts: 
   
        * selector - A selector is an HTML tag at which a style will be applied
        * property - A proprety is a type of attribute of HTML tag.
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

12. What is ``float`` proprety in CSS?

    * In float, CSS allow an element to be positioned horizondally, allowing elements below the floated element to flow around it
    * Floats can only accept a ``left`` and ``right`` value.

13. What is CSS Box model and its used?  

    * CSS Box model is a made up of margins, borders, padding and content. Box model provides a **structured way** to space elements in     a relationship to each other.

14. Is there a way to restore the default proprety value using CSS?

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

18. Which proprety is used to set the background color of an element?

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
    
20. Which proprety is used to controll the scrolling of an image in the background?

    * The ``background-attachement`` property is used to control the scrolling of an image in the background.

21. Explain de difference between ``visibility: hidden`` and ``display: none``?

    * ``visibility: hidden`` simply hides the element, while it will still take up space and affect the layout of the document.
    * ``display: none`` also hides the element, but will not take up space and the page will appear as if the element is not present
    
11. How can you apply a CSS rule to all elements?

12. How can you center a ``div`` element in a page?

13. What are all the values of position attribute in CSS? What is the diffference between all the positions?

14. What is Flexbox in CSS3? 

15. What are all the units we can use in CSS3?

16. What is the difference between em and rem?

17.  What would be the difference between ``width: auto`` and ``width: 100%`` in  CSS?

18. What is ``@import`` rule in CSS3? Why is ``@import`` only at the top?


20. What is difference between ``nth-of-type`` and ``nth-child``?


