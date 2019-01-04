# TESTING USER STORIES:

## USER STORY 1: As a fan of the band I want to get the latest news / gig info so that I can buy tickets to the next show. 
### Test 1: View tour dates and buy tickets
1) Go to the site and scroll down to the latest news section.<br>
2) View upcoming tour dates, click on 'here' link to buy tickets and verify it takes you to a buy tickets page in a new tab. (The 'buy ticket' page is not a real webpage, it is a blank mock up to demonstrate link works for the purposes of this project).
### Test 2: Sign up to newsletter
1) On homepage scroll down to 'Never miss the news again' section <br>
2) Click on 'Sign up' link to verify modal appears with sign up form<br>
3) Enter email address in email field and confirm form checks for validity of email address.<br>
4) Press submit button and confirm modal closes after completion of sign up.<br>
5) Repeat this test for 'sign up' links in footer (desktop) on each page and navigation bar (mobile) for each page of site.
## USER STORY 2: As a fan of the band I want to hear the latest music so I can keep up to date with their next album. 
### Test: Listen to song samples
1) Click on 'music' link on fixed navigation bar (desktop) and verify it takes you to music page.<br>
2) Click on play button for an audio clip and confirm audio plays. Verify pause, stop and volume controls work.<br>
3) Repeat for each audio clip<br>
4) Repeat this test in mobile layout (music link in drop down menu)<br>
## USER STORY 3: As a event planner I want to check availability and contact the band so that I can book them for an event. 
### Test: Enquire about availability
1) From the homepage scroll down to 'Book the band' link<br>
2) Click on link and verify it takes you to 'book' page<br>
3) Enter email, number and query into the relevant fields and verify form checks for validity of email address and only number submitted in number field and requires all fields to be filled before allowing submission.<br>
4) Repeat this test initiating from the 'book' link in navigation bar (desktop) and initiating from the 'book' link in dropdown menu (mobile).
## USER STORY 4: As a member of the public I want to find out about the band and listen to some samples so that I can decide if I like the band. 
### Test: Navigate to 'about' page and 'music' page to hear samples
1) From home page click on 'about' link in navigation bar (desktop) or dropdown menu (mobile) and verify it takes you to 'about' page.<br>
2) From any page click on 'music' link in navigation bar (desktop) or dropdown menu (mobile) and verify it takes you to 'music' page.<br>
3) Audio tested in user story 2 above.<br>
4) Repeat to test links on all pages.<br>
## USER STORY 5: As a venue I want to see the bands fanbase (i.e social presence) so that I can see if booking them for a venue would generate revenue. 
### Test: Test links to social pages work
1) From any page click on each social link (facebook, twitter, youtube) in the footer.<br>
2) Verify each link opens a new tab to the relevant social platform (ie. facebook link opens The Monkees facebook group in new tab etc.).<br>
3) Repeat for each social link on each page.<br>

## CROSS-BROWSER TESTING:
### Method:
Using free tool Browserling (available at https://www.browserling.com/ ) I tested my deployed webpage on Windows Explorer, Opera and Android systems.<br>
On my own laptop I tested my deployed webpage on Safari, Firefox and Google Chrome.<br>
I used the following systematic approach to test for issues:<br>
IN DESKTOP (LARGER SCREEN SIZES):<br>
1) Test each navigation link in top navigation bar takes you to the correct page (test navigation bar on each page)<br>
2) Test social links icons in footer take you to the relevant social site in a new tab (test social icons on each page)<br>
3) Hover over ‘Sign up to the latest news’ link in footer – confirm underline to indicate link appears.<br>
    a.Confirm clicking on link launches sign up modal.<br>
    b.For sign up modal (test sign up link and modal in footer on each page)<br>
        i.Try to submit without entering anything – confirm form prompts you to enter in email field.<br>
        ii.Try to enter non-email in field, confirm form requires valid email before submission.<br>
        iii.Check modal closes on submission or when background outside of modal is clicked.<br>
4) HOMEPAGE:<br>
    a.Test each ‘buy’ ticket link under ‘European Tour Dates’. Each link should take you to the blank ticket test page in a new tab.<br>
    b.Check video controls work – test volume, picture and audio working, full size working etc.<br>
    c.Hover over ‘Sign up to our newsletter’ – check underline appears and that clicking on link launches sign up modal and it functions as outlined above.<br>
    d.Hover over ‘Book the Band’ text – confirm text weight increases to indicate link<br>
        i.Confirm clicking on link takes user to ‘book’ page <br>
5) ABOUT PAGE:<br>
    a.Wait to confirm slideshow of images (carousel) begins without prompting.<br>
        i.Confirm clicking left and right controls to move the images in the carousel<br>
        ii.Confirm selecting one of the control dots beneath the carousel takes you to the appropriate picture.<br>
6) MUSIC PAGE:<br>
    a.Confirm all four album images, song titles and audio controls are visible and accessible.<br>
        i.Check each audio control to see it is working (play/pause etc.) and playing audio.<br>
7) BOOK PAGE:<br>
    a.Press submit button on contact form without entering in any fields. Confirm this prompts you to enter email.<br>
    b.Confirm form checks for valid email format<br>
    c.Confirm form checks number only has been entered in phone field<br>
    d.Confirm all fields must be filled in before form will allow you to submit<br>
IN SMALLER SCREEN SIZES (MOBILE AND OTHER SMALL SCREEN SIZES)<br>
1) Test each navigation link in top navigation bar burger drop down has darker color change on hover and when clicked, takes you to the correct page (test navigation dropdown on each page)<br>
2) Test social links icons in footer take you to the relevant social site in a new tab (test social icons on each page)<br>
3) Click on ‘Sign up’ link in top navigation bar<br>
    a.Confirm clicking on link launches sign up modal.<br>
    b.For sign up modal (test sign up link and modal in top navigation bar on each page)<br>
        i.Try to submit without entering anything – confirm form prompts you to enter in email field. <br>
        ii.Try to enter non-email in field, confirm form requires valid email before submission.<br>
        iii.Check modal closes on submission or when background outside of modal is clicked.<br>
4) HOMEPAGE:<br>
    a.Test each ‘buy’ ticket link under ‘European Tour Dates’. Each link should take you to the blank ticket test page in a new tab.<br>
    b.Check video controls work – test volume, picture and audio working, full size working etc.<br>
    c.Click ‘Sign up to our link, confirm it launches sign up modal and it functions as outlined above.<br>
    d.Confirm clicking on ‘Book the Band’ link takes user to ‘book’ page <br>
5) ABOUT PAGE:<br>
    a.Wait to confirm slideshow of images (carousel) begins without prompting.<br>
        i.Confirm clicking left and right controls to move the images in the carousel<br>
        ii.Confirm selecting one of the control dots beneath the carousel takes you to the appropriate picture.<br>
6) MUSIC PAGE:<br>
    a.Confirm all four album images, song titles and audio controls are visible and accessible.<br>
        i.Check each audio control to see it is working (play/pause etc.) and playing audio.<br>
7) BOOK PAGE:<br>
    a.Press submit button on contact form without entering in any fields. Confirm this prompts you to enter email.<br>
    b.Confirm form checks for valid email format<br>
    c.Confirm form checks number only has been entered in phone field<br>
    d.Confirm all fields must be filled in before form will allow you to submit<br>



