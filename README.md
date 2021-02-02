# FLX - Foreign Licence Exchange Tool
![amiresponsive](https://i.imgur.com/uwRMvCI.png)

[View Project on GitHub Pages](https://jakubmrowicki.github.io/flx-tool/)


The goal of this website is to __increase the success rate__ at the NDLS _(National Driving Licence Service)_ __for customers exchanging foreign licences.__

# Table of Contents
1. [Overview](#1-overview)
2. [Description](#2-description)
3. [User Stories](#3-user-stories)
4. [User Experience (UX)](#4-user-experienceux)
    * [Strategy Plane](#strategy-plane)
    * [Scope Plane](#scope-plane)
    * [Structure Plane](#structure-plane)
    * [Skeleton Plane](#skeleton-plane)
    * [Surface Plane](#surface-plane)
5. [Features](#5-features)
6. [Technologies Used](#6-technologies-used)
7. [Trials & Testing](#7-trials--testing)
8. [Problem Solving](#8-problem-areas--solutions)
9. [Code Validation](#9-code-validation)
10. [Website Deployment](#10-website-deployment)
11. [Credits & Acknowledgments](#11-credits--acknowledgments)
12. [Repository Support](#12-repository-support)

# 1: Overview

The NDLS is forced to serve customers on an appointment only basis due to COVID-19 restrictions. This has heavily affected customer satisfaction ratings as well as company revenue.


The primary concern is foreign driving licence exchange appointments as they are usually first time customers and unfamiliar with the NDLS. These applications are more complex in comparison to standard Irish licence applications, therefore they have a considerably lower success rate.

The low success rate is causing frustration for the customer due to the applicant having to book another appointment which can take weeks. In addition to this, the NDLS can only charge a fee for successful applications, hence the revenue loss.

> We must __improve the success rate__ for this type of application. To achieve this, we should __offer easy to understand guidance__ for customers that will help to __alleviate the common issues__ that arise when exchanging a foreign licence.

# 2: Description

The NDLS Foreign Licence Exchange Tool, or simply FLX is an easy online tool designed to guide customers through their application process. This tool exists in order to improve overall customer satisfaction and boost revenue.

# 3: User Stories

Below are some user stories which reveal how this website is helpful.
+ 'A user; __Is my licence valid for exchange__ in Ireland?'
+ 'A user; __I don't have time__ to sift through the overwhelming amount of information on the official NDLS website.'
+ 'A user; I want to __be confident that I'm not missing anything__ such as required documentation.'
+ 'A user; __Where is my local NDLS?__'
+ 'A user; I want to read some __common mistakes applicants make and how I can avoid them.__'
+ 'A user; I want to know how to __make an appointment.__'
+ 'A user; I want to __contact the NDLS__ helpline.'

# 4: User Experience(UX)
## Strategy Plane
* What is the purpose of this application?
    * The purpose of this application is to __aid customers__ who come to __exchange their foreign licence__ at the NDLS.
    * Most of the time, __customers who are exchanging a licence have never visited our service before.__ This results in a __high rejection rate due to uninformed customers__ who don’t bring all the __required documentation.__
    * By informing the customer before they apply, __user experience overall benefits__ and the __company earns their fee__ for the successful application.
* Who is the user?
    * Adult user.
    * Due to the nature of the application, it is likely that the applicant has __limited English__. It would help to __use simple and clear language__ throughout the content.
    * Usually, the user is preparing for their __very first visit__ to the NDLS.
* Why is the content relevant?
    * By consuming the easily digestible content, the requirements will be clear to the user and thus __helping the user achieve their end goal.__
    * Frequently asked questions will be answered clearly.
* Business goals?
    * Increase the success rate of applicants.
    * This is important because there is a __finite number of appointments__ per day and only successful applicants are charged a fee. Meaning that each rejected application is a loss for the business.
* Value for the user?
    * __Save time__ by avoiding a wasted trip due to submitting insufficient documentation.
    * __Make it convenient for the user__, save them from digging through the official website which is designed to cater to all applicants.
---
## Scope Plane
### Function Requirements
* Verify eligibility.
* __Guide the user__ through the requirements, __help them understand__ their licence and __RSA rules.__
* Answer __common queries__ and concerns.
* Make the __forms and appointment booking system__ available.
* __Contact__ information.
### Content Requirements
* Home Page
    * "Are You Eligible For An Irish Licence?"
    * "Is Your Licence Exchangeable In Ireland?"
    * "What Can You Expect Upon Arrival?"
    * Common Issues
* Form Download Links & Descriptions
* Contact Us
* Book Appointment Link
---
## Structure Plane
### Information Architecture
Simplicity and ease of comprehension is the focus.

The home page will therefore contain almost all the most relevant information. The content will be in order of importance. This will help the user accomplish their goals easier.

The forms page will contain download links for all the relevant forms. In addition, descriptions and tips will be available.

The contact page will contain information about opening hours, contact info, a form and a link to find your local centre.
### Interaction Design
Bite-sized paragraphs and clearly defined sections will allow the user to consume information with ease. This will also help avoid overwhelming the user with information.

Provide contact form that the user can interact with.

---
## Skeleton Plane
Wireframes can be found [here](https://github.com/JakubMrowicki/ci-ms1/blob/master/assets/docs/Wireframes.pdf)

The website will be laid out over 3 pages. Home, Forms and Contact page.

The navigation will contain a logo as well as links to the 3 pages. In addition, there will be an external link for booking an appointment with the NDLS directly.

The footer will contain copyright information, navigation links and some social media links.

---
## Surface Plane
### Colours
__Primary Colours:__
Colour | Colour Code | Preview
--- | --- | :---:
Blue | #017DC3 | ![#017DC3](https://via.placeholder.com/15/017DC3/000000?text=+)
Light-Grey | #EDEDED | ![#EDEDED](https://via.placeholder.com/15/EDEDED/000000?text=+)


__Highlight/Focus Colour:__ 
Colour | Colour Code | Preview
--- | --- | :---:
Orange | #F26432 | ![#F26432](https://via.placeholder.com/15/F26432/000000?text=+)



__Text Body Colours:__
Colour | Colour Code | Preview
--- | --- | :---:
Dark-Grey | #383838 | ![#383838](https://via.placeholder.com/15/383838/000000?text=+)
Orange | #F26432 | ![#F26432](https://via.placeholder.com/15/F26432/000000?text=+)
Off-White | #FAFAFA | ![#FAFAFA](https://via.placeholder.com/15/FAFAFA/000000?text=+)


### Typography
I want the fonts to be clear and easy to read so I chose [Oswald](https://fonts.google.com/specimen/Oswald) and [Open Sans](https://fonts.google.com/specimen/Open+Sans). 


"Oswald" will be used to titles to make them stand out.
"Open Sans" will be used for the body.
# 5: Features
* Applicant eligibility check
* Licence eligibility check
* Application forms & reports downloads and descriptions
* General contact information for the service and contact form.
# 6: Technologies Used
This project uses the following technologies:
* HTML5
* CSS3
* JavaScript
* Bootstrap 4.5
* FontAwesome Icons
* Google Fonts
* Github & Git
* GitPod
* Photoshop

# 7: Trials & Testing
* Website was run through the Mobile-Friendly Test by Google and was deemed Mobile Friendly. To further test this, I opened the website on my phone and checked it there too.
    * [Home Page Results](https://search.google.com/test/mobile-friendly?id=Oytshjhu15HS8f-47vI0ZA)
    * [Forms Page Results](https://search.google.com/test/mobile-friendly?id=Ze7_ntbKorMHKzmX5LGO6w)
    * [Contact Page Results](https://search.google.com/test/mobile-friendly?id=H-epR2ju3aboQ_8uWSS2cw)
* Individual html pages & css files were tested using W3 Validator and returned no error messages.
* Tested all the links on the website, and made sure that external links open in a new tab.
* Tested responsiveness to ensure the website looks good on all devices.
* Tested the form, made sure you cannot submit it without entering all the required information.
* Validated and fixed Colour Contrast issues using the [Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/)
* Validated HTML and CSS using W3 Validators.
* Ran style.css through [Autoprefixer](https://autoprefixer.github.io/) to add vendor prefixes.
* Checked and fixed any typos and grammar issues that I could find by using a Chrome Extension called [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik).

# 8: Problem Areas & Solutions
* I wanted the navbar logo to be centered on mobile devices but couldn't figure out how to achieve my goal. I Googled my problem and found [Zim's response on StackOverflow](https://stackoverflow.com/a/54574324). By altering this users code I was able to achieve the look I was going for with ease.
* I wanted the "Get Started!" button to take the user to the first piece of content on the page. However I didn't like how there was no transition, just an instant page jump. I was able to find a solution by [Arseniy-II on StackOverflow](https://stackoverflow.com/a/56895999) and thus enhancing the user experience by smoothly transitioning to the first header.
* Some colour combinations I chose didn't pass the Color Contrast Accessibility Validator, so I had to increase the contrast on some elements by changing the colours slightly.
* I added hover effects to the nav bar items, however I didn't want this hover effect to impact the last nav link which is the external link due to styling. How I fixed it is I added it's very own :hover effect which is the same as when it's not being hover over. There are probably better ways to do this, like for example using :nth-child(-n+3), however I couldn't get this to work.

# 9: Code Validation
HTML was Validated using the [W3 Validator](https://validator.w3.org/) and returned no errors.

CSS  was Validated using [Jigsaw W3 Validator](https://jigsaw.w3.org/css-validator/validator) and returned no errors.

Alicia Ramirez' [Closing Tag Checker for HTML5](https://www.aliciaramirez.com/closing-tags-checker/) was used to further validate the code.
# 10: Website Deployment
This project is deployed to the public by using GitHub Pages.

To deploy the project, the following steps were followed.
* When viewing the repository page, click on the settings button.
* Scroll down to the GitHub Pages section.
* Select the master branch and save.
* After about 15 minutes, the website is live.

[View On GitHub Pages](https://jakubmrowicki.github.io/flx-tool/)

# 11: Credits & Acknowledgments
* Many thanks to my mentor, Ignatius Ukwuoma for his suggestions and overall support of this project.
* Thanks to [AlecRust's response on StackOverflow](https://stackoverflow.com/a/41247934) I was able to add colour previews in my README file.
* Thanks to [Zim's response on StackOverflow](https://stackoverflow.com/a/54574324) I was able to center my logo on mobile devices without affecting desktop users.
* Thanks to [Necrone's reponse on StackOverflow](https://stackoverflow.com/a/33091315) for the blur effect code.
* Thanks to [Marco Trulla on codepen.io](https://codepen.io/Ragnarokkr/pen/KAejm) for a box-shadow vignette effect.
* Thanks to [Arseniy-II on StackOverflow](https://stackoverflow.com/a/56895999) for their smooth scroll solution.

### Content
* The images used on the website were taken by me at my local NDLS centre.
* Content is mostly self-written, the exception being the official NDLS requirements lists to avoid confusion.
# 12: Repository Support
For support please email at [xdshiftblue@gmail.com](mailto:xdshiftblue@gmail.com)