Screenshot 1
Edited screenshot 1.
Colours for the edit:
Red: body
Top green: header
Middle green: div
Bottom green: section 
Middle green, top yellow: div
Middle green, bottom yellow: grid
Bottom green, top yellow: div
Bottom green, bottom yellows: cards
Blue: div
The reason the bottom green is a section and not a green is because there is a h1 element. If you make a section whitout a h element,
the code wont be valid. 
We haven't necessarily done the tasks of the oblig in the correct order, but from what we were able to understand, the tasks should 
be correct.
All svg tags are taken either from https://www.finn.no/ or https://www.fabric-ds.io/iconography 
https://www.w3schools.com/ and https://developer.mozilla.org/en-US/ has been really helpful for finding the correct information.

-------Screenshot 2---------
I started by studying the assignment text. I downloaded Screenshot2 image to declare which elements I will use to build up the 
html structure. I then went to finn.no's log in page. Here I inspected the html structure to get a clue as to how the various
elements are structured. I used photoshop to create a sketch of which elements I would use. The color codes where supposed to 
make it more clear what the different boxes were supposed to represent. 
Color codes for my the sketch;
red = body
green = div to section of left and right side of the pages
yellow = card structure
pink = buttons
blue = form for login

I started by creating the html structure in page_screenshot2.html
I wanted to have a clean, structured and correct html code. This will benefit me later in the coding. I used the BEM system to 
name my classes so that its easy to grab them in CSS. My HTML code is based on my own interpretation of existing elements and codes
from finn.no's side, as well as the design elements that Nora and I created for the design system. I used some of the design 
system elements. The two Screenshot have many differences, therefore many of the elements only exist in one of the pages. So 
although we have used the same design system they do not have a lot in common. We found it the same way with the css. For the 
source to the pictures, i used the url i found the finn.no html code.
My CSS file is mainly structured according to the left and right side. 
I have used BEM and Sass to make an efficient code. This makes it both easier to read and manipulate. I started with the most 
obvious things like the background being gray and the font having to be a sans serif. As described in the design system, I chose 
Arial. Then I focused on finishing the left side first. The left side is not made up of as many elements as the right, but also 
has two different boxes. There I filled in styles for the image and text. What took the longest was right__card. I spent some time 
making use of the correct css styles to shape the form and buttons. In the end, I think the result is similar to the original and 
I feel I have used BEM and sass well. I have learned a lot during this obligation, especially perhaps the most about Github. In 
github we only had small conflicts which we within the group were able to resolve on our own.