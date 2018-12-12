# UCD Milestone Project - The Monkees static webpage
This is a front-end only webpage for a band called The Monkees for their fans and 
followers. It provides the latest information on the band, their upcoming shows,
samples of their music and links to external sites to buy tickets or merchandise.
It also allows fans to sign up to their newsletter or enquire about booking the band.

This webpage was created as part of Code Institute's Software Diploma. 


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
the dark color scheme and some changes in layout. The final layout is also slightly different as issues arose during development.
Both sets of wireframes have been included in These can be viewed under <link href="/Documents/Project Development/WireFrames" type="text/css" />.

## Features
### Existing Features
#### Feature 1 - Navigation bar
The navigation bar allows users to navigate the site by clicking on links to other pages or the sign up modal.
This collapses to a 'burger icon' dropdown menu in mobile screen sizes to reduce over crowding and improve user experience.
#### Feature 2 - Sign up to newsletter link 
The sign up link implements a modal in the same page when clicked on. This allows users to sign up to the band's email newsletter
by entering their email and pressing submit. The form checks for a valid email address before allowing submission.
This link is available in the fixed footer on large and medium screen sizes and moves to the fixed navigation at top of page in mobile.
to make it more visually pleasing and avoid over crowding in mobile view. 
The sign up link can also be accessed from the "Never miss the news again!" banner on the home page.
The link displays a white underline when hovered on (in all locations: nav,footer and main page) to indicate it is a link and for consistency.
****
need to fix a few issues here before completing this feature section
****

#### Feature 3 - Embedded video link
A 'latest video' is embedded into the homepage which users can press play and pause on at any time to view

#### Feature 4 - Large hero image with 'Book the band' title and link to book page
This feature is emphasised on the home page with its large and constrasting background image. The link itself bolds (font weight increases)
when hovered over to indicate it is a link. This link will take the user to the book page in the same browser window where they
can fill out the query form or check the calendar for the band's availability.

#### Feature 5 - Social media links in footer
The fixed footer displays links to facebook, twitter and youtube channels for the band. The icons are from FontAwesome and change 
color when hovered over to indicate they are a link.
These icons remain to the right of the footer on larger screen sizes and move to the center for prominence in mobile view.
****
When clicked on these links take the user to external social media sites in a new tab. 
****
#### Feature 6 - Carousel of images of the band at top of 'About' page
****
NOT READY YET
****
#### Feature 7 - Embedded audio files on 'music' page
Four songs from The Monkees are embedded in the 'Music' page which users can choose to play and pause at any time to listen
to a selection of hits from the band.

#### Feature 8 - 'Contact Us' form on 'Book' page
This form allows users to submit a query by filling out the email, contact number and query fields and submit their enquiry.
The form checks for a valid email address when entered and all fields are required (the enquiry cannot be submitted unless all fields are completed).

#### Feature 9 - Calendar of availability on 'Book' page
This is a calendar created with HTML and CSS. It is not currently interactive and the two month view merely allows users to check
if the band is available on certain dates (as unavailable dates are blocked out in contrasting pink colour).


### Features Left to Implement
#### Feature 1 - Add functionality to calendar
I would like to add javascript to the calendar so the user can change from month to month and click on individual days to see
if it is available and if not to see why not - i.e "booked for private event" or similar.

#### Feature 2 - Merchandise feature
Current music page only plays samples. Would be better to have official merchandise shop element here underneath or add a link to Amazon or another retailer
so users can buy the records after listening.



## Technologies Used
### HTML, CSS and JavaScript
Used as base languages to write and style webpages.
<br> HTML: https://www.w3.org/TR/html/
<br> CSS: https://www.w3.org/Style/CSS/Overview.en.html
<br> JavaScript: https://www.w3schools.com/js/default.asp

### Bootstrap
This project uses Bootstrap as a framework to assist in page layout, navigation, modal and carousel features.
<br>https://getbootstrap.com/

### Cloud9
This project was written on Cloud9.
<br>https://c9.io/login

### JQuery
This project uses JQuery to assist in execution of bootstrap and javaScript features, particularly the modal element.
<br>https://jquery.com/

### FontAwesome
FontAwesome was used to get social link icons for facebook, twitter and youtube.
<br>https://fontawesome.com/

### Google Fonts
Main theme font "Kavoon" was taken from Google fonts.
<br>https://fonts.google.com/

### GitHub
Local git repository was pushed to remote repository on GitHub and site was published using GitHub pages.
<br>https://github.com/

## Testing
### Testing my user stories 
USER STORY 1: As a fan of the band I want to get the latest news / gig info so that I can buy tickets to the next show.
1) Go to the site and scroll down to the latest news section.
2) View upcoming tour dates, click on 'here' link to buy tickets and verify it takes you to a buy tickets page in a new tab.
(The 'buy ticket' page is not a real webpage, it is a blank mock up to demonstrate link works for the purposes of this project).

1) On homepage croll down to 'Never miss the news again' section
2) Click on 'Sign up' link to verify modal appears with sign up form
3) Enter email address in email field and confirm form checks for validity of email address.
4) Press submit button and confirm sign up message is displayed ****
5) Repeat this test for 'sign up' links in footer (desktop) on each page and navigation bar (mobile) for each page of site.

USER STORY 2:As a fan of the band I want to hear the latest music so I can keep up to date with their next album.
1) Click on 'music' link on fixed navigation bar (desktop) and verify it takes you to music page.
2) Click on play button for an audio clip and confirm audio plays. Verify pause, stop and volume controls work.
3) Repeat for each audio clip
4) Repeat this test in mobile layout (music link in drop down menu)

USER STORY 3: As a event planner I want to check availability and contact the band so that I can book them for an event.
1) From the homepage scroll down to 'Book the band' link
2) Click on link and verify it takes you to 'book' page
3) Enter email, number and query into the relevant fields and verify form checks for validity of email address and requires all
fields to be filled before allowing submission.
4) Check submission confirmation message is displayed ****
5) Repeat this test initiating from the 'book' link in navigation bar (desktop) and initiating from the 'book' link in dropdown
menu (mobile).

USER STORY 4: As a member of the public I want to find out about the band and listen to some samples so that I can decide if 
I like the band.
1) From home page click on 'about' link in navigation bar (desktop) or dropdown menu (mobile) and verify it takes you to 'about' page
2) From any page click on 'music' link in navigation bar (desktop) or dropdown menu (mobile) and verify it takes you to 'music' page.
3) Audio tested in user story 2 above.
4) Repeat to test links on all pages.

USER STORY 5: As a venue I want to see the bands fanbase (i.e social presence) so that I can see if booking them for a 
venue would generate revenue.
1) From any page click on each social link (facebook, twitter, youtube) in the footer. 
2) Verify each link opens a new tab to the relevant social platform (ie. facebook link opens The Monkees facebook group in new tab etc.).

## Deployment


## Credits
### Content
All content regarding The Monkees in the 'about' page was paraphrased from the wikipedia pages referenced in the project
documentation. These references can be accessed here: <link href:"/Documents/Referencing/Information references"/>

### Media
Images, audio and video were provided by Code Institute and can be accessed here:
<link href:"https://github.com/Code-Institute-Org/project-assets"/>

Additional images were sourced from google images and filtered by ****

### Acknowledgements
I received inspiration for this project colour scheme from an album of The Monkees titled "The Definitive Monkees" released 
in 2001, a copy of which I own.