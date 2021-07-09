# Hull College

## Introduction

This is a fictional website (for educationalpurposes) for potential students to find basic information about Hull College in East Yorkshire, England.  

## UX Design

### User Demographics
The target market are individuals who are wanting to find out more about the college to see if they want to enrol.  It is not for current students.

### User Stories

1. As a potential student, I want to quickly see what courses are offered so I can see if they are of interest.

2. As a potential student, I want to see some general "about" text so I can confirm that I am on the correct site for my needs.

3. As a potential student, I want to see facts and figures on student satisfaction so I can gauge whether I want to enroll.

4. As a potential student, I want to be able to contact the college so that I can ask any questions I have.

### Wireframes

Small screens
<img src="assets/images/small-new.avif" alt="Wireframe of small screen">

Medium sized screens
<img src="assets/images/medium-new.avif" alt="Wireframe of medium screen">

Large screens
<img src="assets/images/large-new.avif" alt="Wireframe of large screen">

#### How the wireframes changed throughout development
Smaller screens center the header logo and place the navigation below it.  This was done to increase the user experience on such screens and for aesthetic reasons.

All form labels were moved above their input.  Form inputs and the textarea were set to the same length.  This was changed after viewing [this video] (https://www.youtube.com/watch?v=z9H7p1_iI14) discussing form design.

A map showing the college's location was added to the contact section.

### Design

#### Colour Scheme

Blue was chosen as the main colour for the site.  Research had shown that this is a colour associated with reliability, productivity, trust and order, which are the principles the college wish to promote. 

Coolors.co was then used to find a mix of blues for the main colour platette, with the following decided upon:

Header: #03045e
About: #caf0f8
Courses: #90e0ef
Contact: #00b4d8
Footer: #0077b6

<img src="assets/images/blue-colours.avif" alt="Blue colour scheme from Coolors.co">

Main text: #12130f
Navigation and footer text/icons: #fffafa
Accent color: #800080
Sumbit button: #faf482

#### Typography
Typespiration.com was used to find complimenting Google Font pairings, with the following decided upon:

Headings: Roboto Condensed, with a fallback of sans-serif. 
Body: Poppins, with a fallback of sans-serif.

## Features

- __Navigation Bar__

 The navigation bar allows the user to easily select which area of the site they wish to view.  It will be located at the top of the site as this is common practice and is the area where most users eyes will be initially drawn to.  It will be 'sticky', meaning it will stay at the top of the users screen even when they scroll the site.  This is because the site is a one page design and it is essential for the user to always be able to navigate the site wherever their current position.  When a link is hovered over it becomes underlined to help the user confirm they are about to select the releavnt link.  The underline reamins once selected and the relevant navigation link is highlighted when the site is scorlled.  

The 'hamburger' icon was not used on small screens (where the navigation bar will collapse and be represented as three horizontal lines.  When touched/clicked, this would reveal the navigation in a dropdown menu).    This is often done due to the limited real estate space making the text hard to read when the screen is this size.  However, this design was not used to make the site more easy to navigate for all users.  Furthermore the navigation only contains three links so they have the space to remain next to each other still on small screens without causing accessibility and design issues.  However, the logo will be centered and the navigation drop below at a maximum width of 689px.

- __Hero Image__

An eye-catching full screen image is placed under the navigation.  This helps grab the users attention and convey positive, professional feelings.  

- __About Section__

- __About Information Box__

A small box containing introductory information is placed below the hero image.  This is eye-catching and quickly confirms to the user that they are on the correct site.  It offers general information on the college so users quickly get a feel for it's achevments.

Award Winning and Student Satisfaction

A brief description of the four awards the college has won is displayed under cartoon images of awards.  Beneath these are statistics of student success and recomendations.  These help to install confidence in the quality of the college and help conversion rates of those viewing the site to enroll.  Larger screens  display the awards and statistics four in a row, reducing to two and then stacked on top of each other as screens get smalller.  This is to give the user the best experience in terms of accesibility and usability.  These sections mirror each other to help give the site a sense of balance.

- __Courses Section__

This section contains images for the courses available at the college so users can quickly see if they offer a course they are interested in.  Icons from Font Awesome are used for the courses to add visual interest and to make each course quickly identifiable and more memorable.  On large screens the courses are displayed three in a row, changing to two and then one as the screen gets smaller.

- __Contact Section__

This section allows the user to easily contact the college by using a form to send a message.  The fields are clearly marked, all required and the email field must contain a valid email.  The message is limited to 400 characters to keep them succint and reduce the amount of characters needed to be stored in the database.  The Submit button is a bright distinctive colour, acting as a call to action for the user.

A map showing the college's location is also included in this section, allowing users to quickly identify where the college is based.

- __Footer__

The footer feature at the bottom of the page contains links to Hull College's social media links.  This will help users find more information and stay up to date with the college.  The links open in a new tab so users are not taken away from Hull College's website.  They are the same colour as those in the navigation for consistency and to help them stand out.

ADD IMAGES????

 
### Features to Implement in the future
- **Courses**
     Add information about each course when a courses image or heading is clicked.
 - **[LinkFire](https://www.linkfire.com/ "Link to LinkFire page") embedding**
     - **Feature** - smart-link embedding platform for music promotion
     - **Reason for not featuring in this release** - Budget not available for services

[Back to top ⇧](#Kryan-Live)

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


[Back to top ⇧](#Kryan-Live)

## Technologies Used
### Main Languages Used
- HTML
- CSS

### Additional Languages Used
- Javascript was used to change the highlighted navigation link on scroll.

### Frameworks, Libraries & Programs Used
- [Google Fonts](https://fonts.google.com/ "Link to Google Fonts")
    - Google fonts was used to import the fonts "Roboto", "Lato" and "Montserrat" into the style.css file. These fonts were used throughout the project.
- [Font Awesome](https://fontawesome.com/ "Link to FontAwesome")
     - Font Awesome was used on all pages throughout the website to import icons (e.g. social media icons) for UX purposes.
- [Git](https://git-scm.com/ "Link to Git homepage")
     - Git was used for version control by utilizing the GitPod terminal to commit to Git and push to GitHub.
- [GitHub](https://github.com/ "Link to GitHub")
     - GitHub was used to store the project after pushing
- [Balsamiq](https://balsamiq.cloud// "Link to Balsamiq homepage")
     - Figma was used to create the wireframes during the design phase of the project.
- [Am I Responsive?](http://ami.responsivedesign.is/# "Link to Am I Responsive Homepage")
     - Am I Responsive was used in order to see responsive design throughout the process and to generate mockup imagery to be used.

[Back to top ⇧](#Kryan-Live)

## Testing
Details about the testing of the site can be found [here](TESTING.md)

### How the site was Deployed
The code was deployed to GitHub Pages in the following way:

1. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
2. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
3. Open Settings by clicking on the Settings link (with the cog icon).
4. Scroll down to the GitHub Pages section and click on the link. 
<img src="assets/images/github-pages.avif" alt="GitHub Pages section">
4. Click the dropdown box in the Source section (which currently states "none") and select master (this may be named "main" for some users).
<img src="assets/images/github-source.avif" alt="Selecting master branch as source">
6. Click Save.
7. The URL address for the deployed site will be shown.
<img src="assets/images/deployed-address.avif" alt="Example of URL once deployed">


### How to Fork the Repositry

1. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
2. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
3. Click "Fork" at the top right of the page.
4. The repository will be copied into your GitHub account.

### How to create a Clone

1. Install the [GitPod Browser](https://www.gitpod.io/docs/browser-extension/) Chrome extension.
2. Refresh the browser once intilation has finished.
3. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
4. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
5. Click "GitPod" in the top right hand corner.

## Credits
The following were used throughout the creation of this site:

[Typespiration](https://typespiration.com/)

[Coolors](https://coolors.co/)

[Font Awesome](https://fontawesome.com/)

[Pexels](https://www.pexels.com/)

[TinyPNG](https://tinypng.com/)

[Balsamiq](https://balsamiq.com/)

[Am I Responsive](http://ami.responsivedesign.is/)

[w3c Markup Validator](https://validator.w3.org)

[lighthouse](https://developers.google.com/web/tools/lighthouse)

[Convertico](https://convertio.co/)

[Avif.io](https://avif.io/)

https://supercooldesign.co.uk/blog/how-to-write-good-alt-text

https://codepen.io/malsu/pen/VwKzoPG

https://squoosh.app/

https://www.youtube.com/watch?v=z9H7p1_iI14

### Content

### Media
The image used as the Hero was taken from [Adobe] (https://stock.adobe.com/)
All other images were taken from [Pexels](https://www.pexels.com/)

[Back to top ⇧](#Kryan-Live)

## Acknowledgements

- Thank you to the Code Institute Slack community for their general help and guidance.
- Many thanks to my mentor for the help along the way.


[Back to top ⇧](#Kryan-Live)

