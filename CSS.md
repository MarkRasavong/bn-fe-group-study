# CSS
1. What are the main differences between external, internal, and inline CSS?
* external: within the ``head`` tag of the HTML document. You can 'import' your CSS file by using the ``<link rel="stylesheet" href="abs or rel .css file link"/>``
* internal: within the ``head`` include a style tag ``<style> </style>`` and you can input CSS rules in the same HTML document.
* inline: within the ``body`` tag, target a specfic HTML element and add the attribute ``style=""`` from there you can manipulate a style of that specific element.
2. What is the syntax for class and ID selectors?
* class: ``.className`` ``class="className"``
* id: ``#idName`` ``id="idName"``
3. How would you apply a single rule to two different selectors?
* ``p, h1 {
            color: #324F34
           }`` 
4. Given an element that has an id of title and a class of primary, how would you use both
attributes for a single rule?
* ``<p id="idName" class="className">{some content}</p>``
* ``#idName { font-size: 2rem }``
5. What does the descendant combinator do?
* ``.ancestor .child`` => if there is a relation between the two in a sense that it is nested, than the child will have the style manipulate
6. Between a rule that uses one class selector and a rule that uses three type selectors,
which rule has the higher specificity?
* the class selector => using the specificity calculator it comes to this ``class = 0,1,0`` v. ``3 type selectors = 0,0,3``
7. From inside to outside, what is the order of box-model properties?
* In this order from in to our: ``content, padding, border, && margin``
8. What does the box-sizing CSS property do?
* ``box-sizing`` is a css property that sets how the width and height is calculated
* ``border-box`` takes account of the border and padding for it's height and width but will shrink the content area.
* ``content-box`` establish the content area width and height and then adds the padding border of an element
9. What is the difference between the standard and alternative box model?
* ``standard`` => ``content-box``
* ``alternative`` => ``border-box``
10. Would you use margin or padding to create more space between 2 elements?
* You would use margin to create space between 2 elements.
11. Would you use margin or padding to create more space between the contents of an
element and its border?
* You would use padding to create more space between the element's content and its border
12. Would you use margin or padding if you wanted two elements to overlap each other?
* If you want two element to overlap eache other you will need to use margin => most likely in negative values
13. What is the difference between a block element and an inline element?
* ```block`` = takes up the entire width of a document
* ``inline`` = only occupies enough width to display the content
14. What is the difference between an inline element and an inline-block element?
* Compared to display: inline, the major difference is that inline-block allows to set a width and height on the element. Also, with display: inline, top and bottom margins & paddings are not respected, and with display: inline-block they are.
15. Is an h1 block or inline?
* Yes, the h1 element is a block-level element in HTML.
16. Is button block or inline?
* The button element in HTML is a block-level element by default.
17. Is div block or inline?
* The div element in HTML is a block-level element by default.
18. Is span block or inline?
* The span element in HTML is an inline element by default. This means that it takes up only as much width as necessary to display its content, and other elements will appear to the side of it.

19. What’s the difference between a flex container and a flex item?
* The main difference between a flex container and a flex item is that the flex container is the parent element that controls the layout of the flex items and the flex items are the child elements that are laid out according to the properties set on the flex container. Flex container has properties like justify-content, align-items, flex-wrap, and flex-direction that help to control the layout of the flex items. Flex items have properties like flex-grow, flex-shrink, flex-basis, align-self that help to control the individual layout of the item inside the container.

20. How do you create a flex item?
* ```.flex-container {
  display: flex; /* Creates a flex container */
}```
* ```<div class="flex-container">
  <div class="flex-item">Item 1</div>
  <div class="flex-item">Item 2</div>
  <div class="flex-item">Item 3</div>
</div>```
* ```
.flex-item {
  display: flex; /* Creates a flex item */
}
```
* ```
.flex-item {
  flex-basis: 200px; /* set the base size of flex item*/
  flex-grow: 1; /* allow the flex item to grow */
  flex-shrink: 1; /* allow the flex item to shrink */
  align-self: center; /* align the flex item vertically */
}
```
21. What are the 3 values defined in the shorthand flex property?
* grow, shrink, & basis
22. How do you make flex items arrange themselves vertically instead of horizontally?
* ``flex-direction``: ``column`` || ``column-reverse``
23. What is the difference between justify-content and align-items?
* ``justify-content`` is the main axis of the ``flex-direction`` and ``align-items``the opposite direction
24. How do you use flexbox to completely center a div inside a flex container?
* ```.parent-container { 
display: flex;
align-items: center;
justify-content: center;
}
```
25. What’s the difference between justify-content: space-between and justify-content:
space-around?
* The justify-content property in CSS is used to align flex items along the horizontal (main) axis of a flex container. It has several possible values, including space-between and space-around. The main difference between these two values is how they distribute the remaining space within a flex container.
* justify-content: space-between: It distributes the remaining space evenly between the first and last flex items in the container. The first item will be aligned to the start of the container, and the last item will be aligned to the end of the container. All the other items will be distributed evenly between them, with equal amounts of space between each item.
* justify-content: space-around: This value will distribute the remaining space evenly around all the flex items, with half the space on the left and right of the first item, and half on the left and right of the last item. This means that there will be more space around the items than between them.
* Therefore, justify-content: space-between is useful when you want to distribute the space evenly between the items while justify-content: space-around is useful when you want to distribute the space around all the items.
