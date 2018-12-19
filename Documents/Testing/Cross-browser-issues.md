# Issues raised by cross browser testing 18/12/18 and resolutions if possible
## Audio not displaying - 'Error' message only in audio controls box on both Mobile and Desktop
Internet Explorer - NON-ISSUE - browserling tester did not support audio - tested on another IE and worked fine 18/12/18
## Last audio control box covered by footer in mobile view - inaccessible
Internet Explorer, Safari, Firefox - FIXED 19/12/18, wrapped last audio in div and added padding
## Video audio not playing
Internet Explorer - NON-ISSUE - browserling tester did not support audio - tested on another IE and worked fine 18/12/18
## Left and Right controls for carousel on 'about' page not functioning
All browsers - - FIXED 19/12/18 id's not set properly for carousel - now working on all browsers.
## Carousel doesn't start playing automatically when page opens
Firefox - NON-ISSUE - testing browser was too slow - carousel now playing automatically in firefox 18/12/18
## Control dots for carousel (to select images) do not function
All browsers - FIXED 19/12/18 id's not set properly for carousel - now working on all browsers.
## Audio controls overlapping song title in medium screen size
Safari - FIXED 19/12/18 Typo in media query in 'album-name' class
## Calendar margins still off on medium screen size and horizontal scroll has appeared
Safari - FIXED 20/12/18 width set to 100%, padding left - calendar now centered