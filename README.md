# Hull College 

<img  src="assets/images/amiresponsive.avif"  alt="Mockup of the Hull College website on a phone, tablet, laptop and monitor screen">

[View the live project here](https://mjjstockman.github.io/hull-college/).

***
## Table of contents
1. [Introduction](#Introduction)
2. [UX and Design](#UX-and-design)
    - [User Demographics](#User-Demographics)
    - [User Stories](#User-Stories)
    - [Wireframes](#Wireframes)
    - [Changes to the design throughout development](##Changes-to-the-design-throughout-development)
    - [Colour Scheme](#Colour-Scheme)
    - [Typography](#typography)
3. [Features](#Features) 
     - [Navigation and Header](#Navigation-and-Header)
     - [Hero Image](#Hero-Image)
     - [About Information Box](#About-Information-Box)
     - [Award Winning and Student Satisfaction](#Award-Winning-and-Student-Satisfaction)
     - [About Information Box](#About-Information-Box)
     - [Courses Section](#Courses-Section)
     - [Contact Section](#Contact-Section)
     - [Footer](#Footer)
4. [Future Features](#Features-to-Implement-in-the-future)
5. [Testing](#Testing)
6. [Deployment](#Deployment)
    - [How the site was Deployed](#How-the-site-was-Deployed)
    - [How to Fork the Repository](#How-to-Fork-the-Repository)
    - [How to create a Clone](#How-to-create-a-Clone-using-SSH)
7. [Credits](#Credits)
    - [Images](#Images)
    - [Acknowledgements](#Acknowledgements)
    - [Images](#Images)
***

# Introduction

This is a fictional website (for educational purposes) for potential students to find basic information about **Hull College** in East Yorkshire, England.  It gives basic information on the college's success, the courses offered and a way to contact them so users can gauge the suitability of the college.  

[Back to top ⇧](#Hull-College)
# UX and Design

## User Demographics
The target market are individuals who are wanting to find out more about the college to see if they want to enrol. It is not for current students.

## User Stories
1. As a potential student, I want to quickly see what courses are offered so I can see if they are of interest.

2. As a potential student, I want to see some general "about" text so I can confirm that I am on the correct site for my needs.

3. As a potential student, I want to see facts and figures on student satisfaction so I can gauge whether I want to enrol.

4. As a potential student, I want to be able to contact the college so that I can ask any questions I have.

[Back to top ⇧](#Hull-College)
## Wireframes

| Small screens |Medium screens  | Large screens |
|--|--|--|
| <img  src="assets/images/small-new.avif"  alt="Wireframe of small screen"> | <img  src="assets/images/medium-new.avif"  alt="Wireframe of medium screen"> | <img  src="assets/images/large-new.avif"  alt="Wireframe of large screen">|

[Back to top ⇧](#Hull-College)
## Changes to the design throughout development
The original design was slightly different to the above wireframes.  The following particualrs were changed during implementation to better the user experience and aesthetics:

The header was changed so that the logo was centered and the navigation drops underneath when the scrren is reduced to a particular size.  This meant that the navigation links did not get too close together.

Form labels were moved above their inputs, placeholders removed and all inputs and the submit button were stacked and the same width.  

A map showing the colleges location was added to the contact section.

[Back to top ⇧](#Hull-College)
## Colour Scheme
Blue was chosen as the main colour for the site. Research had shown that this is a colour associated with reliability, productivity, trust and order, which are the principles the college wish to promote.

 [Coolors](https://coolors.co/) was then used to find a mix of blues for the main colour platette, with the following decided upon:

 - Header: #03045e 
 - About: #caf0f8 
 - Courses: #90e0ef 
 - Contact: #00b4d8   
 - Footer: #0077b6

<img  src="assets/images/blue-colours.avif"  alt="Blue colour scheme from Coolors.co">

- Main text: #12130f
- Navigation and footer text/icons: #fffafa
- Accent color: #800080
- Sumbit button: #faf482

[Back to top ⇧](#Hull-College)
## Typography

[Typespiration](https://typespiration.com/) was used to find complimenting [Google Font](https://fonts.google.com) pairings, with the following decided upon:

- Headings: Roboto Condensed, with a fallback of sans-serif.
- Body: Poppins, with a fallback of sans-serif.

[Back to top ⇧](#Hull-College)
# Features
## Navigation and Header

The navigation bar allows the user to easily select which area of the site they wish to view. It will be located at the top of the site as this is common practice and is the area where most users eyes will be initially drawn to. It will be 'sticky', meaning it will stay at the top of the users screen even when they scroll the site. This is because the site is a one page design and it is essential for the user to always be able to navigate the site wherever their current position. When a link is hovered over it becomes underlined to help the user confirm they are about to select the relevant link. The underline remains once selected and the relevant navigation link is highlighted when the site is scrolled.

 The 'hamburger' icon was not used on small screens (where the navigation bar will collapse and be represented as three horizontal lines. When touched/clicked, this would reveal the navigation in a dropdown menu). This is often done due to the limited real estate space making the text hard to read when the screen is this size. However, this design was not used to make the site more easy to navigate for all users. Furthermore the navigation only contains three links so they have the space to remain next to each other still on small screens without causing accessibility and design issues. However, the logo will be centred and the navigation drop below at a particular screen width. 

[Back to top ⇧](#Hull-College)
## Hero Image

An eye-catching full screen image is placed under the navigation. This helps grab the users attention and convey positive, professional feelings.

[Back to top ⇧](#Hull-College)
## About Information Box
A small box containing introductory information is placed below the hero image. This is eye-catching and quickly confirms to the user that they are on the correct site. It offers general information on the college so users quickly get a feel for its achievements.

[Back to top ⇧](#Hull-College)
 ## Award Winning and Student Satisfaction

A brief description of the four awards the college has won is displayed under cartoon images of awards. Beneath these are statistics of student success and recommendations. These help to install confidence in the quality of the college and help conversion rates of those viewing the site to enrol. Larger screens display the awards and statistics four in a row, reducing to two and then stacked on top of each other as screens get smaller. This is to give the user the best experience in terms of accessibility and usability. These sections mirror each other to help give the site a sense of balance.

[Back to top ⇧](#Hull-College)
## Courses Section
This section contains images for the courses available at the college so users can quickly see if they offer a course they are interested in. Icons from Font Awesome are used for the courses to add visual interest and to make each course quickly identifiable and more memorable. On large screens the courses are displayed three in a row, changing to two and then one as the screen gets smaller.

[Back to top ⇧](#Hull-College)
## Contact Section
This section allows the user to easily contact the college by using a form to send a message. The fields are clearly marked, all required and the email field must contain a valid email. The message is limited to 400 characters to keep them succinct and reduce the amount of characters needed to be stored in the database. The Submit button is a bright distinctive colour, acting as a call to action for the user.

A map showing the college's location is also included in this section, allowing users to quickly identify where the college is based.

[Back to top ⇧](#Hull-College)
## Footer
The footer feature at the bottom of the page contains links to Hull Colleges social media links. This will help users find more information and stay up to date with the college. The links open in a new tab so users are not taken away from Hull College's website. They are the same colour as those in the navigation for consistency and to help them stand out.

[Back to top ⇧](#Hull-College)
# Features to Implement in the future
Add a dropdown to each course in the Courses section containg information on the course.

# Technologies Used
## Main Languages Used
- HTML
- CSS

[Back to top ⇧](#Hull-College)
## Additional Languages Used

- Javascript was used to change the highlighted navigation link on scroll.

[Back to top ⇧](#Hull-College)
# Testing

Details on site testing can be found [here](TESTING.md).

[Back to top ⇧](#Hull-College)
# Deployment
## How the site was Deployed
The code was deployed to GitHub Pages in the following way:
1. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
2. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
3. Open Settings by clicking on the Settings link (with the cog icon).
4. Scroll down to the GitHub Pages section and click on the link.
<img  src="assets/images/github-pages.avif"  alt="GitHub Pages section">
4. Click the dropdown box in the Source section (which currently states "none") and select master (this may be named "main" for some users).
<img  src="assets/images/github-source.avif"  alt="Selecting master branch as source">
6. Click Save.
7. The URL address for the deployed site will be shown.
<img  src="assets/images/deployed-address.avif"  alt="Example of URL once deployed">

[Back to top ⇧](#Hull-College)
## How to Fork the Repository
1. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
2. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
3. Click "Fork" at the top right of the page.
4. The repository will be copied into your GitHub account.

[Back to top ⇧](#Hull-College)
## How to create a Clone using SSH
1. Log into [GitHub](https://github.com/login) or [create an account](https://github.com/join).
2. Select the [GitHub Repository](https://github.com/mjjstockman/hull-college).
3. Click on the Code button.
4. Copy the provided SSH link.
<img  src="assets/images/code-dropdown.avif"  alt="Example of the provided link">
5. Open Terminal.
6. Navigate into the directory you want to clone the repositry to.
7. Type git clone and paste the copied URL.
```
$ git clone https://github.com/mjjstockman/hull-college
```
8. Press **Enter**.

[Back to top ⇧](#Hull-College)
# Credits

Many thanks to the following which were used throughout the creation of this site:
- [w3c Markup Validator](https://validator.w3.org)
- [Adobe Stock Image](https://stock.adobe.com)
- [Am I Responsive?](http://ami.responsivedesign.is)
- [Balsamiq](https://balsamiq.com/)
- [Coolors](https://coolors.co/)
- [Design Course tutorial](https://www.youtube.com/watch?v=z9H7p1_iI14)
- [Favicon.io](https://favicon.io)
- [Font Awesome](https://fontawesome.com)
- [Free Formatter](https://www.freeformatter.com/)
- [Google Fonts](https://fonts.google.com)
- [Git](https://git-scm.com)
- [GitHub](https://github.com)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [Looka](https://looka.com/)
- [Malsu Codepen](https://codepen.io/malsu/pen/VwKzoPG)
- [Pexels](https://www.pexels.com)
- [Responsinator](http://www.responsinator.com)
- [Squoosh](https://squoosh.app)
- [Super Cool Design](https://supercooldesign.co.uk/blog/how-to-write-good-alt-text)
- [TinyPNG](https://tinypng.com/)
- [Typespiration](https://typespiration.com/)

[Back to top ⇧](#Hull-College)
## Images

The Hero image was taken from [Adobe Stock Image](https://stock.adobe.com/).

All other images were taken from [Pexels](https://www.pexels.com/).

[Back to top ⇧](#Hull-College)
## Acknowledgements
- Many thanks to my mentor for guidance.
- Thank you to the Code Institute Slack community for their advice.

[Back to top ⇧](#Hull-College)