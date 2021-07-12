
For testing writeup there are basically 5 parts.
1) List the websites you used to validate your code and what they are for.
2) Go through the user stories you wrote in the UX part of your ready, and explain how your website meets those needs.
3) Write about how each part of your responsive website behaves on different screen sizes.

And if you want to knock the grade for testing all the way up to the max:
4) Manually go though every part of your site and write out how you confirmed that each link, hover effect and other interactive parts of the site work as you expect.
5) List any bugs you came across while creating the site and while testing it. Include the fixes you came up with. (I have two sections here, one for fixed bugs and one for bugs I have not found a solution for yet.)







# Hull College Testing 

[Main README.md file](/README.md)

[View live project](https://mjjstockman.github.io/hull-college/)

[View website in GitHub Pages](https://github.com/mjjstockman/hull-college)


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
[Back to top ⇧](#Hull-College-Testing)
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

     <img src="assets/images/contact-section-form.avif" alt="Screenshot of student satisfaction section">

[Back to top ⇧](#Hull-College-Testing)

## Manual Testing
All links on the site and within its documentation were checked to make sure they are working.


all links checked


Manually go though every part of your site and write out how you confirmed that each link, hover effect and other interactive parts of the site work as you expect.
ADD IF HAVE TIME, IF NOT ADD TO INCOMPLETE FEATURES IN README

http://www.responsinator.com/

[Back to top ⇧](#Hull-College-Testing)

## Automated Testing

### Code Validation
The [W3C Markup Validator](https://validator.w3.org/) service was used to validate the HTML.

**Results:**

- Home Page

     ![Home Page HTML Validation Results](assets/testing-files/automated/home.png)

The [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) service was used to validate the CSS.

**Results:**
![Style sheet validation results](assets/pdf/lighthouse-report.pdf)

[Back to top ⇧](#Hull-College-Testing)
### Browser Validation
- Chrome - [test image](assets/testing-files/automated/chrome.png)
- Safari - [test image](assets/testing-files/automated/safari.png)
- Edge - [test image](assets/testing-files/automated/edge.png)
- Opera - [test image](assets/testing-files/automated/opera.png)
- Firefox - [test image](assets/testing-files/automated/firefox.png)

[Back to top ⇧](#Hull-College-Testing)

### Lighthouse Auditing
- Click [here](assets/testing-files/automated/lighthouse.pdf) for full report
- No recommendations in this report have been implemented in the first release but will be looked into for future releases.

[Back to top ⇧](#Hull-College-Testing)

## User testing 
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues. Their helpful advice throughout the process led to many UX changes in order to create a better experience. 

It was through this testing that the following changes were made:
- Change to the Navbar background color on mobiles in order for the toggler menu icon to more distinguishable to the background image.
- Change to Navbar font-size on mobile for clearer reading.
- Complete overhaul of Live page in order to display the information in a more user-friendly way.

[Back to top ⇧](#Hull-College-Testing)


## Issues and Bugs 
A number of bugs and issues were encountered during the sites development, as detailed below.  

Some images had a small amount of white space below them.  This is beacuse images are inline elements and therefore treated as text and assumed to have descenders.  Research found that the white space can be removed by declaring the image as a block level element.
https://mor10.com/removing-white-space-image-elements-inline-elements-descenders/

The page was taking a long time to load.  This was fixed by reducing the file size of images used.  This was initally done using Tiny PNG, a smart lossy image compression tool (https://tinypng.com/).  All images were later changed to AVIF format to further reduce their size by using https://squoosh.app/.

The sticky header (with the logo and navigation) initially displayed behind the iframe map.  This issue was sovled by adding a z-index of 1 to the header.
https://stackoverflow.com/questions/52091989/embedded-iframe-video-overlap-the-fixed-navbar-while-scrolling

HTML validation (at https://validator.w3.org/) showed errors for the description and keywords meta tags in the head.  This was due to mismatching quotation marks, as seen below:

<img src="assets/images/quotation.avif" alt="Inccorect quotation marks for meta tags">

[Back to top ⇧](#Hull-College-Testing)