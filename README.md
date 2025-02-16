


Scroll Animation Project
<hr>
<hr>

Description
<hr>

This project demonstrates a simple scroll animation effect using HTML, CSS, and JavaScript. As the user scrolls down the page, elements appear with a smooth transition effect.


![Image](https://github.com/user-attachments/assets/383b1a0d-794c-4caa-b5ac-93e882096ca5)

Features 
<hr>

--Dynamically adds a class to elements when they enter the viewport.

--Smooth transition effect on scroll.

--Uses JavaScript's getBoundingClientRect() method to detect element positions.

Technologies Used
<hr>

--HTML5: Structure of the page.

--CSS3: Styling and animations.

--JavaScript (Vanilla JS): Scroll event handling and dynamic class manipulation.


Usage
<hr>

--Scroll down the page.

--Watch the .box elements appear smoothly as they enter the viewport.

--Scroll back up to see them disappear.







Element: getBoundingClientRect() method
The Element.getBoundingClientRect() method returns a DOMRect object providing information about the size of an element and its position relative to the viewport.
Parameters
None.

Return value
The returned value is a DOMRect object which is the smallest rectangle which contains the entire element, including its padding and border-width. The left, top, right, bottom, x, y, width, and height properties describe the position and size of the overall rectangle in pixels. Properties other than width and height are relative to the top-left of the viewport.

The width and height properties of the DOMRect object returned by the method include the padding and border-width, not only the content width/height. In the standard box model, this would be equal to the width or height property of the element + padding + border-width. But if box-sizing: border-box is set for the element this would be directly equal to its width or height.

The returned value can be thought of as the union of the rectangles returned by getClientRects() for the element, i.e., the CSS border-boxes associated with the element.

Empty border-boxes are completely ignored. If all the element's border-boxes are empty, then a rectangle is returned with a width and height of zero and where the top and left are the top-left of the border-box for the first CSS box (in content order) for the element.

The amount of scrolling that has been done of the viewport area (or any other scrollable element) is taken into account when computing the bounding rectangle. This means that the rectangle's boundary edges (top, right, bottom, left) change their values every time the scrolling position changes (because their values are relative to the viewport and not absolute).

If you need the bounding rectangle relative to the top-left corner of the document, just add the current scrolling position to the top and left properties (these can be obtained using window.scrollY and window.scrollX) to get a bounding rectangle which is independent from the current scrolling position.

Examples
Basic
This simple example retrieves the DOMRect object representing the bounding client rect of a simple <div> element, and prints out its properties below it.


