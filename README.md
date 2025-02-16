


Scroll Animation Project

Description

This project demonstrates a simple scroll animation effect using HTML, CSS, and JavaScript. As the user scrolls down the page, elements appear with a smooth transition effect.


![Image](https://github.com/user-attachments/assets/383b1a0d-794c-4caa-b5ac-93e882096ca5)

Features

Dynamically adds a class to elements when they enter the viewport.

Smooth transition effect on scroll.

Uses JavaScript's getBoundingClientRect() method to detect element positions.

Technologies Used

HTML5: Structure of the page.

CSS3: Styling and animations.

JavaScript (Vanilla JS): Scroll event handling and dynamic class manipulation.

Installation & Setup

Clone the repository:

git clone https://github.com/your-username/scroll-animation.git

Navigate to the project folder:

cd scroll-animation

Open index.html in a browser:

open index.html

Or, you can use Live Server in VS Code to see changes dynamically.

Usage

Scroll down the page.

Watch the .box elements appear smoothly as they enter the viewport.

Scroll back up to see them disappear.

Code Overview

HTML (index.html)

Contains a series of .box elements inside a <div>.

Links to style.css and script.js.

CSS (style.css)

Adds styling for .box elements.

Includes the .show class for the transition effect.

JavaScript (script.js)

Uses querySelectorAll() to select all .box elements.

Listens for the scroll event.

Determines when an element should become visible using getBoundingClientRect().
