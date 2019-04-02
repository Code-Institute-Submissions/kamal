# Kamal

The websites is a quick way to know who Kamal is, his music and contact him for concerts. 

## UX

Kamal is a friend of mine that few months ago decided to improve his position on the web .So far he just had [this blog]( http://www.kamalikus.it/).
He asked me to develop a brand new website in order to have more concerts around Europe.
The typical user of this website would be a person that does not know Kamal, but is curious about his music (maybe he has just heard about him or listened at some song).
The website should work like a quick calling card that gives a quick presentation of the artist and give the possibility to get in touch with him for future concerts or events.
It has been designed to catch the attention of the user with very essential information and an eye to  readability on all devices.
The idea of connecting the website to the blog, initially considered, was afterwards rejected. The blog is addressed to different users : fans and friends.  
Original mockups of the project can be found in mockups folder.

## Features

The project is based on 5 pages that have some common features

* Navbar: a Bootstrap based Navbar that is completely responsive (Hamburger button for small devices)
* Social Footer:users  can access the Youtube channel, Facebook or send an email
* Theme color meta-tag: on small devices  the url bar change color, adapting to the website pattern.(cross-browser compatible

All pages have different features:

* Index.html: the user is welcomed by a muted video in loop. 
* Kamal.html: it consists of a Navbar taking 25 - 20 % height of the page and a content area taking 75 - 80 % height of the page (depending on the device).
Scrolling down, there is Bootstrap grid with 6 pictures, that are displayed in 3, 2 or 6 rows (depending on the device)
Hovering over with the mouse or tapping on (mobile), pictures slightly change aspect (saturation). Info about the pictures appear with a special transiction  (scale).
* Music.html:this page shares exactly the same structure of the previous. Instead of pictures the grid is composed by 6 embedded Youtube videos. 
* Tour.html: After a brief description the user can view the dates of future concerts. Readability has been improved for different devices (media query).
* Contact.html: the form allows the user to contact Kamal (hopefully to propose a new concert). 

### Features Left to Implement

* Colors are displayed slightly different on different browser. Consistency should be improved
* Contact form should be developed. It is not working as it is outside the scope of this project
* The intro Youtube video has created many problems. It should be replaced by the original video loaded in the website folder.
* A website favicon should be implemented

## Technologies Used

* Html & CSS
* Bootstrap 3.3.7: Bootstrap classes are used all over the project
* Jquery: used for the navbar
* Youtube: used to embed videos
* Google Fonts
* Font Awesome: for the footer
 
## Testing

All the project has been tested with Google Chrome Dev Tool in order to ensure the site looks great on different devices.
Many problems arose during testing. Here some of them:

* Specificity: this was a big problem I had during all the project. Initially I used !important in order to override more specific properties. Finally I deleted !important and I managed increase my classes specificity.
* I had many problems with the position of elements on the page on different devices: I solved the problem setting several media queries.
* Index.html: the intro video looked great on desktop (16:9) but not so great on mobile standard resolution. I finally decided to use media query and to sacrifice the width when resolution was lower than 16:9 
* Index.html: The top bar with channel info and " Watch later" cannot be hidden due to a change in youtube api policy. I then decided to cover that info making the navbar 100% wide and setting a background color.

## Deployment

The project has been developed on C9.io and regularly updated through commits on GitHub.

[GitHub code](https://github.com/belli29/kamal/)
[GitHub Pages](https://belli29.github.io/kamal/)

## Credits

### Acknowledgements

I received inspiration for this project from mini projects explained during the module. 
In addition I received inspiration from the following websites:

* [Zac Brown Band](https://zacbrownband.com/pages/music) : for the grid system
* [Borno Ski Area](http://bornoskiarea.it/) : for the Index page