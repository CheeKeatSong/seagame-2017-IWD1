This file has listed all the dependencies used in this project.

1. Bootstrap
Responsive Web Design Framework

<!-- Link -->
http://getbootstrap.com/docs/4.0/getting-started/download/

<!-- File -->
i)   bootstrap.css
ii)  bootstrap.js

<!-- Activation -->
Example - index.html
line 11 - includes the bootstrap style css
line 399 - includes the bootstrap javascript

<!-- Usage -->
- Flexible container
- Responsive grid system for various screen sizes 
Example - index.html
line 39 - "class= container"
line 76 - "col-md-5" - give 5/12 columns for medium screen size

- Table structure
Example - paragames.html
line 84 - "table table-striped table-bordered"
i)   call table style
ii)  give table striped look
iii) give table border


2. font-awesome
Includes resources of icons available

<!-- Link -->
http://fontawesome.io/

<!-- File -->
font-awesome.min.css

<!-- Activation -->
Example - index.html
line 13 - includes the font-awesome icons

<!-- Usage -->
line 321 - 324
<li><a class="facebook" href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
<li><a class="facebook" href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
<li><a class="facebook" href="#"><i class="fa fa-google-plus" aria-hidden="true"></i></a></li>
<li><a class="facebook" href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
fa fa-* are the icons


3. jarallax

Jarallax is an open-source javascript library which makes adjusting css based on interaction easy.
With Jarallax it's easy to create a parallax scrolling website.

Parallax scrolling is a web site trend where the background content is moved at a different speed than the foreground content while scrolling.

<!-- Link -->
http://www.jarallax.com/

<!-- File -->
jarallax.js 

<!-- Activation -->
Example - about.html
line 342 - includes jarallax.js

<!-- Usage -->
Example - about.html
line 344 - 349
Initiate the jarallax parameter


4. jQuery

jQuery is a cross-platform JavaScript library designed to simplify the client-side scripting of HTML.

<!-- Link -->
http://jquery.com/download/

<!-- File -->
jquery-2.1.4.min.js 

<!-- Activation -->
Example - index.html
line 398 - includes jquery.js

<!-- Usage -->
Example - index.html
line 23 - 28
2 methods are used here
i)  event.preventDefault() - prevent the page refresh
ii) offset() - Get the current coordinates of the first element, or set the coordinates of every element, in the set of matched elements, relative to the document.


5. jquery.picEyes

picEyes is a simple, lightweight jQuery gallery / image viewer plugin for presenting your images in fullscreen mode. The plugin displays enlarged images in a modal-style full browser window popup and the users can navigate between them by clicking on navigation arrows and bottom thumbnails. Infinite looping is supported as well.

<!-- Link -->
https://www.jqueryscript.net/gallery/Full-Window-Modal-style-Photo-Gallery-Plugin-with-jQuery-picEyes.html

<!-- File -->
jquery.picEyes.js 

<!-- Activation -->
Example - gallery.html
line 304 - includes jquery.picEyes.js

<!-- Usage -->
Example - about.html
line 307 - Initiate the picEyes

line 80 - 198
implementation on gallery section


6. jquery.wmuSlider

wmuSlider is an easy and fast jQuery plugin that allows you to create a clean and responsive Carousel / Slider with fade and slide animations.

<!-- Link -->
https://github.com/Bluinfaccia/wmuSlider

<!-- File -->
jquery.wmuSlider.js 

<!-- Activation -->
Example - index.html
line 404 - includes jquery.wmuSlider.js

<!-- Usage -->
Example - index.html
line 168 - 169 - Implementation on sponsors section
Include the class for the div


<!-- Note that 7, 8, 9 are implemented together to make the move to top button and smooth scrolling function -->
7. move-top

javascript file to move to the top of a webpage.

<!-- Link -->
http://www.mattvarone.com/web-design/uitotop-jquery-plugin

<!-- File -->
move-top.js

<!-- Activation -->
Example - index.html
line 425 - includes move-top.js

<!-- Usage -->
Example - index.html
line 430
On the webpage, the move to top button on the right bottom side


8. SmoothScroll

A teeny tiny, standard compliant, smooth scroll script with ease-in-out effect and no dependancy.

<!-- Link -->
https://github.com/alicelieutier/smoothScroll

<!-- File -->
SmoothScroll.min.js 

<!-- Activation -->
Example - index.html
line 424 - includes SmoothScroll.min.js 

<!-- Usage -->
Example - index.html
line 430
On the webpage, the move to top button on the right bottom side


9. easing

Typically used for the rate of change of a parameter

<!-- Link -->
http://gsgd.co.uk/sandbox/jquery/easing/

<!-- File -->
easing.js 

<!-- Activation -->
Example - index.html
line 426 - includes easing.js

<!-- Usage -->
Example - index.html
line 430 - scrolling (move to top) icon + transition timing