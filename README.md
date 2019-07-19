# FIRST-PROJECT

This project was built for my student assignment, It is a website that allows visitors to Strängnäs to see how beautiful the town is and also what it has to offer.

## UX

#### USER STORIES
As a visitor to the Strängnäs I want to know about things to see and do locally and also the surrounding areas. I would like to see a map so that it would make it easier to navigate around and also links to the places/activities websites to gather more information or book tickets if needed.

Here is a link to my wireframes: https://balsamiq.cloud/skey8pl/pxfxgq6/r5B98?f=N4IgUiBcAMA0IDkpxAYWfAMhkAhHAsjgFo4DSUA2gLoC%2BQA%3D

I changed my final design of the website so that all the information would be the same on desktop and mobile so that users would not miss out on anything. So instead of taking the images and videos page off I decided to leave it on.
I also moved the Navbar to the top of the screen instead of in the middle on the landing page so that it would keep the same appearance throughout.

#### STRATEGY
This project was designed for visitors to Strängnäs. Visitors to the website should be able to seewhat Strängnäs has to offer, either if they are visiting for a day or taking a longer break.

#### SCOPE
There should be images to show how beautiful Strängnäs is, there should also be a map so that places of interest are easier to find. There will be links to social media and external websites if the customer feels that they need more information.
All images in the images & videos page will be made clickable so that they can be viewed on a full screen either on desktop or mobile. The navigation bar shall become a burger icon on mobile devices that will drop down the pages when pressed making it easier to navigate around the website on a mobile device. There shall be a sign up area in the footer so you can have special offers and discounts on anything in Strängnäs or around Södermanland.

#### STRUCTURE
The information is structured so that the relevant information is placed in their own pages:
* History
* Things to do
* Images & videos
* Map

The Navbar will be fixed to the top on all devices and screen sizes to keep it user friendly and easily accessable. The footer will be visible when the user has scrolled to the bottom of the page so that more of the actual content is shown on the screen.
 
#### SKELETON
Full screen landing page features an image of Strängnäs in the summer and will want users want to see more. It will be kept full screen on all devices, all of the information will be available on desktop and mobile devices as I dont want anyone to miss out on the features my website has to offer.

#### SURFACE
I wanted to keep the website simple and clean with not to much going on so that users eyes are focused on the content and not elsewhere. I have chosen a light grey background on all pages, and the navbar and footer are also in the same colour so that it blends in seemlesly. The links in the Navbar are coloured blue and there is a swedish flag in the left corner as Strängnäs is in Sweden.
The headers for each page has the same design with a blue background (same blue as the navbar text) and the text is a light grey (same as the background of the pages).

## FEATURES

In all of my pages there is a link to social media, and a chance to sign up with an email to receive offers.
All images in the images & video page are clickable so they can be viewed at a larger size and also saved. It also has a video link that directs the user to youtube to view the video of Strängnäs.
Things to do page has links to the website of the mentioned activities so users can easily find the website.
All links that are clicked are opened in another browser window so users can easily find their way back to my website.

#### FUTURE FEATURES
* For users to add their own images and videos and also comments and recommendations.
* More languages options so anyone who visits the website no matter where they come from they will be able to understand and use it.

## TECHNOLOGIES USED
* HTML5 - as its the most widely used declarative language.
https://developer.mozilla.org/en/docs/Web/Guide/HTML/HTML5
* CSS3 - used with HTML5 to produce colour, style and layout to my page.
https://developer.mozilla.org/en/docs/Web/CSS/CSS3
* BOOTSTRAP (v4.3.1) - was used to create the grid layout of my website and also the navbar and footer. https://getbootstrap.com/
* GIT - used to track changes I have made in my code. https://git-scm.com/
* GITHUB - works hand in hand with GIT, after files are added and commited to GIT they can be pushed to GITHUB into my repository. https://github.com/
* PIXLR X - used to change image size so it does not effect the quality. https://pixlr.com/x/
* FONT AWESOME/IONICONS -  used to create logos in footer. https://fontawesome.com/    
* https://ionicons.com/
* GOOGLE PHOTOS - used to download my images to be used. https://www.google.com/photos/about/
* YOUTUBE - used for the video of Strängnäs. https://www.youtube.com/

## TESTING
My website was tested in Chrome, Firefox, Safari, Opera and Microsoft Edge. It was also tested on android and ios devices and all worked as it should. A link from GITHUB was sent to my family and friends in England to make sure that it wrked on all of their devices. All links worked and opened in a different browser window. The email sign up was also tested to make sure a valid email address has to entered in order for the sign up button to work.

#### BUGS AND FIXES

* Images loading to slow - SOLUTION- changed all image sizeswith built in resizer tool in AWS Cloud9 so that images would not take long to load.
* Images not clear after resizing with AWS Cloud9 - SOLUTION - resized again using Pixlr x instead, now images are clear.
* Sign up button when clicked just refreshes the page - SOLUTION - added "required" to the input element to fix the problem.
* Scrolling the images and videos page and map page does not work on ios - SOLUTION - after many hours trying to fix the problem I found out that iframes are not well suited to ios, so I decided to remove the iframes for the videos and make a screen shot of the video and create a button on top of the image that when clicked will lead you to the video on youtube in a different window. For the map page i resized the map so scrolling it was not needed.

## DEPLOYMENT

I deployed my website and files using GIT and GITHUB hosting. GIT is used to push files up to GITHUB where i can store the code for you to see. If you want to see the source code you click on the file name ie. index.html or style.css.

Link to my website: https://kososwede.github.io/first-project/index.html

## CREDITS
#### CONTENTS
HISTORY
* Text was copied from wikipedia https://en.wikipedia.org/wiki/Str%C3%A4ngn%C3%A4s

THINGS TO DO
* ARSENALEN text was copied from wikipedia https://sv.wikipedia.org/wiki/F%C3%B6rsvarsfordonsmuseet_Arsenalen
* STRÄNGNÄS DOMKYRKA text was copied from wikipedia https://en.wikipedia.org/wiki/Str%C3%A4ngn%C3%A4s_Cathedral
* STRÄNGNÄS VÄDERKVARN text was copied from wikipedia https://sv.wikipedia.org/wiki/Str%C3%A4ngn%C3%A4s_v%C3%A4derkvarn

#### MEDIA

##### LANDING PAGE
* Image used is my own.
##### HISTORY 
* Images obtained from the swedish nstional heritage https://www.flickr.com/photos/swedish_heritage_board/4699465591 - https://www.flickr.com/photos/swedish_heritage_board/4699457529/in/photostream/
##### THINGS TO DO
* ARSENALEN- Image used is my own.
* STRÄNGNÄS DOMKYRKA- Image obtained from https://farm5.staticflickr.com/4022/5156929679_059ef91ddd_o.jpg
* STRÄNGNÄS VÄDERKVARN- Image used is my own.
##### IMAGES & VIDEOS 
* Images used are my own.
* Video obtained from Youtube https://youtu.be/J5FrnGHEJdw posted by Juha Aurendahll.

## ACKNOWLEDGEMENTS
I received inspiration for this project from
* w3schools.com https://www.w3schools.com/html/default.asp
* Bootstrap.com https://getbootstrap.com/docs/4.3/getting-started/introduction/
* CSS-tricks.com https://css-tricks.com/
* stackoverflow.com https://stackoverflow.com/


 