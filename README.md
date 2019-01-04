# UCD Milestone Project - The Monkees static webpage
This is a front-end only webpage for a band called The Monkees for their fans and 
followers. It provides the latest information on the band, their upcoming shows,
samples of their music and links to external sites to buy tickets or merchandise.
It also allows fans to sign up to their newsletter or enquire about booking the band.

This webpage was created as part of Code Institute's Software Diploma. 
<br> It can be viewed at : https://kmaaallen.github.io/UCD-milestone--Monkees/.


## UX
This website is predominantly for fans of the band and is designed to
provide all the information they might want in a single place. 
The following user stories were brainstormed during the planning process and 
informed decisions for particular sections of the site.

1) As a fan of the band I want to get the latest news / gig info so that I can buy tickets to the next show.
2) As a fan of the band I want to hear the latest music so I can keep up to date with their next album.
3) As a event planner I want to check availability and contact the band so that I can book them for an event.
4) As a member of the public I want to find out about the band and listen to some samples so that I can decide if I like the band.
5) As a venue I want to see the bands fanbase (i.e social presence) so that I can see if booking them for a 
venue would generate revenue.

During project development I also created some wireframes for my project. My initial wireframes changed after some feedback on
the dark color scheme and some changes in layout. The final layout is slightly different as issues arose during development and the color scheme
changed again after user testing (i.e feedback from family and friends).
Both sets of wireframes have been included and these can be viewed under the documents folder: https://github.com/kmaaallen/UCD-milestone--Monkees/tree/master/Documents/Project%20Development/WireFrames .

## Features
### Existing Features
#### Feature 1 - Navigation bar
The navigation bar allows users to navigate the site by clicking on links to other pages or the sign up modal.
This collapses to a 'burger icon' dropdown menu in mobile screen sizes to reduce over-crowding and improve user experience.

#### Feature 2 - Sign up to newsletter link 
The sign up link implements a modal in the same page when clicked on. This allows users to sign up to the band's email newsletter
by entering their email and pressing submit. The form checks for a valid email address before allowing submission and closes upon successful submission or clicking outside the modal area.
This link is available in the fixed footer on large and medium screen sizes and moves to the fixed navigation at top of page in mobile.
to make it more visually pleasing and avoid over crowding in mobile view. 
The sign up link can also be accessed from the "Never miss the news again!" banner on the home page.
The link displays an underline when hovered on (in all locations: nav,footer and main page) in desktop to indicate it is a link and for consistency.

#### Feature 3 - Embedded video link
A 'latest video' is embedded into the homepage which users can press play and pause on at any time to view

#### Feature 4 - Large hero image with 'Book the band' title and link to book page
This feature is emphasised on the home page with its large and constrasting background image. The link itself bolds (font weight increases)
when hovered over (on desktop) to indicate it is a link. This link will take the user to the book page in the same browser window where they
can fill out the query form or check the calendar for the band's availability.

#### Feature 5 - Social media links in footer
The fixed footer displays links to facebook, twitter and youtube channels for the band. The icons are from FontAwesome and change 
color when hovered over to indicate they are a link.
These icons remain to the right of the footer on larger screen sizes and move to the center for prominence in mobile view.
When clicked on these links take the user to external social media sites in a new tab. 

#### Feature 6 - Carousel of images of the band at top of 'About' page
These large images display black and white photographs of the band to capture attention.
Users can let the carousel play or select the left and right glyphicons or the navigation dots beneath the images to move through the carousel.

#### Feature 7 - Embedded audio files on 'music' page
Four songs from The Monkees are embedded in the 'Music' page which users can choose to play and pause at any time to listen
to a selection of hits from the band.

#### Feature 8 - 'Contact Us' form on 'Book' page
This form allows users to submit a query by filling out the email, contact number and query fields and submit their enquiry.
The form checks for a valid email address when entered and all fields are required (the enquiry cannot be submitted unless all fields are completed).
The number field input is also restricted to number entries only. 

#### Feature 9 - Calendar of availability on 'Book' page
This is a calendar created with HTML and CSS. It is not currently interactive and the two month view merely allows users to check
if the band is available on certain dates (as unavailable dates are blocked out in contrasting pink colour).


### Features Left to Implement
#### Feature 1 - Add functionality to calendar
I would like to add javascript functionality to the calendar so the user can change from month to month and click on individual days to see
if it is available and if not to see why not - i.e "booked for private event" or similar.

#### Feature 2 - Merchandise feature
Current music page only plays samples. Would be better to have official merchandise shop element here underneath or add a link to Amazon or another retailer
so users can buy the records after listening.

#### Feature 3 - Sign up modal and contact form
The addition of a thank you message would benefit the user here. i.e "Thank you, your enquiry has been submitted."


## Technologies Used
### HTML, CSS and JavaScript
Used as base languages to write and style webpages.
<br> HTML: https://www.w3.org/TR/html/
<br> CSS: https://www.w3.org/Style/CSS/Overview.en.html
<br> JavaScript: https://www.w3schools.com/js/default.asp

### Bootstrap
This project uses Bootstrap (and classes imported from Bootstrap) as a framework to assist in page layout, navigation, modal and carousel features.
<br>https://getbootstrap.com/

### Cloud9
This project was written on Cloud9.
<br>https://c9.io/login

### JQuery
This project uses JQuery to assist in execution of bootstrap and javaScript features, particularly the modal element.
<br>https://jquery.com/

### FontAwesome
The social link icons for facebook, twitter and youtube (in footer) were imported from FontAwesome.
<br>https://fontawesome.com/

### Google Fonts
Main theme font "Luckiest Guy" and sub-theme font "Roboto" were imported from Google fonts.
<br>https://fonts.google.com/

### GitHub
Local git repository was pushed to remote repository on GitHub and site was published using GitHub pages.
<br>https://github.com/

### W3C HTML and CSS online validators
Online validators were used to check code was valid for both HTML and CSS.
HTML validator: https://validator.w3.org
CSS Validator: http://jigsaw.w3.org/css-validator/

### Autoprefix tool
This online autoprefix tool was used to check when vendor pre-fixes were necessary. This was used after my cross-browser testing
to identify issues and fix bugs.
Available at : https://autoprefixer.github.io/

## Testing
### Testing my user stories 
Testing documentation regarding user stories and cross-browser testing can be viewed at:
<br> https://github.com/kmaaallen/UCD-milestone--Monkees/blob/master/Documents/Testing/TESTING.docx

## Deployment
This page has been deployed using GitHub Pages and can be viewed at : https://kmaaallen.github.io/UCD-milestone--Monkees/

## Credits
### Content
All content regarding The Monkees in the 'about' page was taken from the wikipedia pages referenced in the project
documentation. These references can be accessed in the documents folder under 'Referencing' 
<br> https://github.com/kmaaallen/UCD-milestone--Monkees/blob/master/Documents/Referencing/Information%20references

The code snippet in stylesheet.css to hide the spin icon in number field of form was taken from Stack Overflow (commented out in stylesheet.css). Original author 'Swerhen' posted 21/03/14.
<br> This is the link : https://stackoverflow.com/questions/3790935/can-i-hide-the-html5-number-input-s-spin-box

The code snippet in stylesheet.css to remove background colour for autofill of contact form was taken from CSS-TRICKS (commented ot in stylesheet.css). Author: Geoff Graham.
<br> This is the link: https://css-tricks.com/snippets/css/change-autocomplete-styles-webkit-browsers/

### Media
Images, audio and video were provided by Code Institute and can be accessed here:
<br> https://github.com/Code-Institute-Org/project-assets

Additional images were sourced from google images and filtered by the advanced search. Only images "free to use, share or modify, even commercially"
were selected.
The three images from the carousel on the 'About' page were sourced in this way. Links to the origin of these images are below:
<br>https://upload.wikimedia.org/wikipedia/commons/e/ed/The_Monkees.jpg
<br>https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/The_Monkees_May_1967.jpg/800px-The_Monkees_May_1967.jpg
<br>https://upload.wikimedia.org/wikipedia/commons/e/ee/The_Monkees_1967.jpg
<br>The generic band image used as a background image for 'Book the band' link on homepage was also found this way, image source below:
<br>https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTg7BHEw41onOuDsiCJ9753kv-lLAAz1fDzhTGiMH-F2oZFn3w8Mw

### Acknowledgements
Thanks to those of the Code Institute Slack community who helped out when I was stuck and to my friends and family for testing the usability of the site.