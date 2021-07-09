
For testing writeup there are basically 5 parts.
1) List the websites you used to validate your code and what they are for.
2) Go through the user stories you wrote in the UX part of your ready, and explain how your website meets those needs.
3) Write about how each part of your responsive website behaves on different screen sizes.

And if you want to knock the grade for testing all the way up to the max:
4) Manually go though every part of your site and write out how you confirmed that each link, hover effect and other interactive parts of the site work as you expect.
5) List any bugs you came across while creating the site and while testing it. Include the fixes you came up with. (I have two sections here, one for fixed bugs and one for bugs I have not found a solution for yet.)







# Kryan Live - Testing 

[Main README.md file](/README.md)

[View live project](https://rebeccatraceyt.github.io/KryanLive/)

[View website in GitHub Pages](https://github.com/rebeccatraceyt/KryanLive)

***
## Table of contents
1. [Testing User Stories](#Testing-User-Stories)
2. [Manual Testing](#Manual-Testing)
3. [Automated Testing](#Automated-Testing) 
     - [Code Validation](#Code-Validation)
     - [Browser Validation](#Browser-Validation)
     - [Lighthouse Auditing](#Lighthouse-Auditing)
4. [User Testing](#User-Testing)


***

## Testing User Stories

#### Potential Students:
1. As a potential student, I want to quickly see what courses are offered so I can see if they are of interest.

     - The six courses on offer are clearly listed within the Courses section.
     - Images relating to the subjects are used to draw the users attention.
     - The name of the course is capatlised and in a different colour the body text to stand out.
     - Icons from Font Awesome are used before and after the courses heading, once again to draw the users attention and make the subjects more memorable.

     <img src="assets/images/courses-section.avif" alt="Screenshot of courses section">

2. As a potential student, I want to see some general "about" text so I can confirm that I am on the correct site for my needs.

     - The about section contains a paragraph of introductionary text, letting the user quickly understand the purpose of the site.

     <img src="assets/images/about-intro-section.avif" alt="Screenshot of about introduction section">

3. As a potential student, I want to see facts and figures on student satisfaction so I can gauge whether I want to enroll. 

     - The about section contains information on the student satisfaction. 

     <img src="assets/images/about-student-satisfaction-section.avif" alt="Screenshot of student satisfaction section">

4. As a potential student, I want to be able to contact the college so that I can ask any questions I have.

     - The contact section has a form to send the college a questions/messages.

     img src="assets/images/about-student-satisfaction-section.avif" alt="Screenshot of courses section">








[Back to top ⇧](#Kryan-Live---Testing)

## Manual Testing

### Common Elements Testing
Manual testing was conducted on the following elements that appear on every page:

- Hovering over the Navbar will trigger `hover` effect, confirming the link the users are on

     ![Navbar hover effect](assets/testing-files/gen-gif/navbar.gif)

- Hovering over Social links will trigger `hover` effect and clicking on them will open a new tab

     Facebook:

     ![Facebook Social link](assets/testing-files/gen-gif/facebook.gif)

     Instagram:

     ![Instagram Social link](assets/testing-files/gen-gif/instagram.gif)

     Twitter:

     ![Twitter Social link](assets/testing-files/gen-gif/twitter.gif)

     Spotify:

     ![Spotify Social link](assets/testing-files/gen-gif/spotify.gif)

     Apple Music:

     ![Apple Music Social link](assets/testing-files/gen-gif/apple-music.gif)

     Deezer:

     ![Deezer Social link](assets/testing-files/gen-gif/deezer.gif)

### Home Page
Manual testing was conducted on the following elements of the [Home Page](index.html):

- Clicking logo on left of screen will refresh the landing page

     ![Homepage Refresh](assets/testing-files/home-gif/home-logo.gif)

- Hovering over 'Out Now' link will create a `hover` effect

     !['Out Now' hover effect](assets/testing-files/home-gif/home-link.gif)

- On a mobile device, the hero image stacks on top of the other column for UX purposes

     ![Home page - mobile version](assets/testing-files/home-gif/home-mobile.png)

- The responsiveness of the Home page

     ![Home page responsiveness](assets/testing-files/home-gif/home-res.gif)

### Bio Page
Manual testing was conducted on the following elements of the [Bio Page](bio.html):

- Clicking the logo on the top left of the page will return the user to the Home Page

     ![Bio page to Home page](assets/testing-files/bio-gif/bio-logo.gif)

- Hovering over each accordion menu will trigger the `hover` effect and clicking the link within will open it in a new tab

     Jordo and 'the Legs':
 
     ![Accordion link opens in new tab](assets/testing-files/bio-gif/bio-accordion1.gif)

     The Scratch:

     ![Accordion link opens in new tab](assets/testing-files/bio-gif/bio-accordion2.gif)

     The Hit Machine Drummers:

     ![Accordion link opens in new tab](assets/testing-files/bio-gif/bio-accordion3.gif)

- On a mobile device, the hero image stacks on top of the other column for UX purposes

     ![Bio page - mobile version](assets/testing-files/bio-gif/bio-mobile.gif)

- The responsiveness of the Bio page

     ![Bio page responsiveness](assets/testing-files/bio-gif/bio-res.gif)

### Live Page
Manual testing was conducted on the following elements of the [Live Page](live.html):

- Clicking the logo on the top left of the page will return the user to the Home page

     ![Live page to Home page](assets/testing-files/live-gif/live-logo.gif)

- Hovering over the venue name will trigger a `hover` effect and clicking it will open the event page in a new tab

     ![Live page venue link](assets/testing-files/live-gif/live-venue.gif)

- Hovering over the ticket button will trigger a `hover` effect and clicking will open ticketing site in a new tab   

     ![Live page button link](assets/testing-files/live-gif/live-ticket.gif)

- Clicking on the map `iframe` embed will open the map in a new tab

     ![Live page map link](assets/testing-files/live-gif/live-map.gif)

- On a mobile device, the hero image stacks on top of the other column for UX purposes

     ![Live page - mobile version](assets/testing-files/live-gif/live-mobile.png)

- The responsiveness of the Live page

     ![Live page responsiveness](assets/testing-files/live-gif/live-res.gif)

### Press Kit Page
Manual testing was conducted on the following elements of the [Electronic Press Kit Page](epk.html):

- Clicking the logo on the top left of the page will return the user to the Home page

     ![Press Kit page to Home page](assets/testing-files/epk-gif/epk-logo.gif)

- Clicking the `next tab` icon on the carousel will allow the user to flick through the images

     ![Carousel image selection](assets/testing-files/epk-gif/epk-pics.gif)

- Hovering over the article link will trigger a `hover` effect and clicking will open article in a new tab

     ![Indie Buddie link](assets/testing-files/epk-gif/epk-link1.gif)

- Clicking on the IGTV `iframe` embed will open the video in a new tab

     ![IGTV video link](assets/testing-files/epk-gif/epk-link2.gif)

- Clicking on the Spotify `iframe` will allow the users to control the music playing in the embed

     ![Spotify embed](assets/testing-files/epk-gif/epk-link3.gif)

- Hovering over the Booking Agent's name will trigger a `hover` effect. On click will lead users to a `mailto` platform

     ![Mailto Hover effect](assets/testing-files/epk-gif/epk-mail.gif)

- When filling out the contact form, the user must complete all fields

     ![Contact form required fields](assets/testing-files/epk-gif/epk-form.gif)

- On a mobile device, the hero image stacks on top of the other column for UX purposes

     ![Press Kit page - mobile version](assets/testing-files/epk-gif/epk-mobile.gif)

- The responsiveness of the Electronic Press Kit page

     ![Press Kit page responsiveness](assets/testing-files/epk-gif/epk-res.gif)

[Back to top ⇧](#Kryan-Live---Testing)

## Automated Testing

### Code Validation
The [W3C Markup Validator](https://validator.w3.org/) service was used to validate the HTML.

**Results:**

- Home Page

     ![Home Page HTML Validation Results](assets/testing-files/automated/home.png)



The [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) service was used to validate the CSS.

**Results:**
![Style sheet validation results](assets/testing-files/automated/style.png)

### Browser Validation
- Chrome - [test image](assets/testing-files/automated/chrome.png)
- Safari - [test image](assets/testing-files/automated/safari.png)
- Edge - [test image](assets/testing-files/automated/edge.png)
- Opera - [test image](assets/testing-files/automated/opera.png)
- Firefox - [test image](assets/testing-files/automated/firefox.png)

### Lighthouse Auditing
- Click [here](assets/testing-files/automated/lighthouse.pdf) for full report
- No recommendations in this report have been implemented in the first release but will be looked into for future releases.

[Back to top ⇧](#Kryan-Live---Testing)

## User testing 
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues. Their helpful advice throughout the process led to many UX changes in order to create a better experience. 

It was through this testing that the following changes were made:
- Change to the Navbar background color on mobiles in order for the toggler menu icon to more distinguishable to the background image.
- Change to Navbar font-size on mobile for clearer reading.
- Complete overhaul of Live page in order to display the information in a more user-friendly way.

[Back to top ⇧](#Kryan-Live---Testing)


## Issues and Bugs 
A number of bugs and issues were encountered during the sites development, as detailed below.  

Some images had a small amount of white space below them.  This is beacuse images are inline elements and therefore treated as text and assumed to have descenders.  Research found that the white space can be removed by declaring the image as a block level element.
https://mor10.com/removing-white-space-image-elements-inline-elements-descenders/

The page was taking a long time to load.  This was fixed by reducing the file size of images used.  ADD TINY PNG. LATER CHANGES TO AVIF https://convertio.co/ https://avif.io/
https://tinypng.com/

The sticky header (with the logo and navigation) initially displayed behind the iframe map.  This issue was sovled by adding a z-index of 1 to the header.
https://stackoverflow.com/questions/52091989/embedded-iframe-video-overlap-the-fixed-navbar-while-scrolling

HTML validation (at https://validator.w3.org/) showed errors for the description and keywords meta tags in the head.  This was due to mismatching quotation marks, as seen below:

<img src="assets/images/quotation.avif" alt="Inccorect quotation marks for meta tags">