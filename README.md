# google-homepage

You can view the completed project [here](https://zaidkhraibut.github.io/google-homepage/).

< In this challenge I recreate the Google homepage used basic (and some intermediate) HTML and CSS.

I learned a lot during this project and I think it's a fantastic place to start if you're just setting out to learn web development. Not only did I learn quite a bit about HTML and CSS, but it also reinforced the use of git and the command line.

Some insight I've gained after completing this project:

1.  The Box Model really started to click while I was laying out this page. It was pretty trickt to figure out how to center-align the logo, search bar, and buttons, but the research I did taught me some valuable CSS lessons. Namely, everything has it's own box and you can do some really great elemental manipulation once you start learning how to put those boxes inside other boxes.

2.  Adding/intensifing a dropshadow is a fanastic and easy way to show website-responsiveness. This was such an easy thing to implement but one of the coolest feautres to see in action.

3.  Navbars were very trick at first. I set out to build the footer from scratch without the use of any tutorial -- it was the last thing I had to build for the site and I was confident I could do it. It took a little tinkering, but ultimatley the lessons I learned throughout this build helped me throw together the footer much, much quicker than I expected.

4.  Using the psuedoclass :focus with the property outline:none blew my mind. This elimanates the browsers default box highlighting when boxes come into focus. Very easy to implement but it gets rid of the tell-tale sign of a begginer's website.

5.  Setting a min-width: on the footer was an incredibly easy way to increase website responsiveness. This made sure my footer did not overlap onto itself when resizing my browser. As you pull your browser in horizontally, the right or left footer will move closer and closer to it's opposite side. Setting a min:width 960px makes sure your elements stop moving once the footer becomes smaller than 960px; instead, your browser will now leave those elements where they are and continue to narrow without taking either side with it. Open up the project and start to pull in your browser window to see what I mean!


A few challenges I faced while completing this project:

1.  Google's search bar has the text indented when you begin to type. A standard input text-field begins its text immediatley at border-left. I solved this problem by putting the input text-field inside of a div, and moving the entire text-field within the div to create the apperence of indented text. The border and dropshadow you can see on the searchbar isn't the actual input text-box being styled, it's a box around it that actually has those effects.

2.  I had difficulty styling the Google Search and I'm Feeling Lucky buttons. I was able to get a satisfactory width and height, however, I can't seem to figure out how to style the buttons indivually. Right now, they both carry the same deminsions and in the future I would like to learn how to style them seperately. The Search button should be a little bit smaller than the I'm Feeling Lucky button.

3.  I wasn't able to figure out how to style an image into the navbar and position it properly. This is a very common web convention and I'm thinking it might have something to do with <img> being an inline element by default. I plan on taking a look into this and hopefully I can implete this feature in future projects.

4.  Not so much a challenge, but I'm very eager to learn about responsive layouts.



Zaid Khraibut



This project was completed as part of [The Odin Project](http://www.theodinproject.com/web-development-101/html-css) curriculum. >
