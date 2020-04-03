# lab04a

## Feature #1: Responsive design

## Overview
In lab today, you will be building a single responsive web page based off of the provided design comp assets. Your document must be designed in a mobile-first approach and must be responsive when the screen size changes and the page is refreshed. The details of the media query specifications are up to you, but your breakpoint must be at 768 pixels.

## Instructions
- Use good HTML structure to scaffold this site, using semantic elements where possible.
- Container elements (a box outside of your content box that might contain multiple content boxes) are very useful in managing layout. You will need to think about the relationship between parent and child / descendant elements as well as the order in which you place them in the HTML. Be thoughtful about your layout strategy.
- Add a reset.css file to your project, like this one. Use SMACSS-style modularity to organize your CSS.
- For the desktop view, the content should be inside of a channel that is a maximum of 960 pixels wide and is centered on wider screen sizes.
- Each box should have a unique background color in mobile view and in desktop view. We are not working with jQuery events yet, so these changes should be observed when the screen size changes and the page is refreshed.

**Why are we implementing this feature?**

- As a user, I want the dimensions and colors of the application to change so that I can have a unique view in desktop, mobile, and tablet viewports.

**What are we going to implement?**

- Given that a user opens the application in the browser, on a tablet, or on a mobile device
  - When the user changes the size of the viewport the boxes should scale proportionally and change colors

**How are we implementing it?**

- Use Flexbox or CSS grids for styling this application.
- Use relative units so the elements scale proportionally when the viewport dimensions change.
- Use at least two breakpoints and change the background colors of each box. There should be three possible views: desktop, tablet, and mobile device. You may choose the exact pixel values for each breakpoint.

# Author 
- Chuck Li Villalobos

# License
- This project is licensed under the MIT License. 