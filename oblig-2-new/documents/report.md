# Report
   
   ## Implemented poster design
   
   We decided to implement poster number 2. We opened the PDF in Adobe Illustrator and extracted the SVGs needed for the website design. 
   
   ### Background 
   
   We deecided to go for a fixed background image so we extracted the backround as a PNG-file. The backround image was added through scss with the backround property. 
   
   ### SVGs and elements
   
   We mainly inserted the SVGs directly into the HTML code. Then we copied the styilng of the SVGs and pasted it into our scss for the sake of organisation. We did however link the SVGs in the footer with and <img> in HTML for the footer and in a few other places. We initially attempted to position the SVGs by using the CSS property "transform: translate", but that caused some complications with the parent containers leaving space on the website. We therefore changed strategy and decided to position elements with the CSS position property. We experimented back and forth with having the elements grouped together in different divs according to the positioning of the SVGs and elements.
   
   ## Animations

   ### Stars
   
   We used keyframe animation to animate the stars so that they sort of twinkle next to the moon. Keyframes and animation line taken from (line 126 and line 140, keyframes line 150-167 in SCSS): https://flaviocopes.com/rotate-image/
   
   ### Wavy text and car

   We implemented the wavy text design by creating a wavy path in illustrator and pasted it into the HTML (svg line 88-93 in HTML)  and used a text tag within the SVG to add text to the curve. We then removed the curve by styling to stroke: none and fill: none. The car was animated using SMIL animations (animation from line 106 - 108 and path on line 98 in HTML). The reason why we used this type of animation here was to create a more complex path for the animation.

   ### Co2 

   The co2 clouds (key frames from line 681 - 707 in SCSS) surrounding the kids standing on the earth SVG were animated using keyframe animations to create some small but vivid movement. 

   ## Resources

   https://developer.mozilla.org/en-US/

   https://www.w3schools.com/

   https://stackoverflow.com/