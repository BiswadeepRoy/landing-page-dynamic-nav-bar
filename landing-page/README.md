# Landing Page Project

## Table of Contents:

#Overview
#Functionalities
#Javascript functions
#Organization



##Overview

Simple Landing page web application which is responsive and will dynamically update the background color of the section which is direclty
on the viewport(user's screen) and will also change the navigation bar element accordingly.



## Functionalities : 

1. The navigation bar will dynamically add any new section elements added inside the page.

2. Which ever section the page is scrolled to will be set as "active-class-section" and highlighted in red with high opacity. 

3. Which ever section is in the viewport the appropriate nav-element will also get higlighted.

4. Furthermore clicking on the navigation bar the page will scroll down to the appropriate section.

5. There will always be one section available on the viewport and that will be the "active-class-section".



##	Javascript functions : 

#buildMenuOnDOMLoad() returns void

Main function which is called which will load all the DOM elements which are dynamic. i.e, the nav bar elements which will dynamically be 
loaded on the basis of number of sections available in the page.

#buildNavBarMenu() returns void

Function to load the dynamic nav bar elements and set the active nav bar element.

#setSectionAsActive() returns void

Function to set the active section on the basis of which section is getting veiwed by the viewport.

#scrollToSection() returns void

Function to scroll smoothly to the section selected on the nav bar.

#resetAllActiveSections() returns void

Helper function to reset all active sections when the viewport is changed or the user has started scrolling manually.

#setActiveNavElements() returns void

Helper function to set the active nav element and reset the previous active nav element inside the nav bar.




## Organization

Udacity Classroom Programme.