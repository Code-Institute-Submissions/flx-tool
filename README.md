# FLX - Foreign Licence Exchange Tool
![amiresponsive](https://i.imgur.com/NzSVoBL.png)


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
8. [Problem Solving](#8-problem-solving)
9. [Code Validation](#9-code-validation)
10. [Website Deployment](#10-website-deployment)
11. [Credits & Acknowledgments](#11-credits--acknowledgments)
12. [Repositiory Support](#12-repositiory-support)

# 1: Overview

The NDLS is forced to serve customers on an appointment only basis due to COVID-19 restrictions. This has heavily affected customer satisfaction ratings as well as company revenue.


The primary concern is foreign driving licence exchange appointments as they are usually first time customers and unfamiliar with the NDLS. These applications are more complex in comparison to standard Irish licence applications, therefore they have a considerably lower success rate.

The low success rate is causing frustration for the customer due to the applicant having to rebook another appointment which can take weeks. In addition to this, the NDLS can only charge a fee for successful applications, hence the revenue loss.

> We must __improve the success rate__ for this type of application. To achieve this, we should __offer easy to understand guidance__ for customers that will help to __alleviate the commmon issues__ that arise when exchanging a foreign licence.

# 2: Description

The NDLS Foreign Licence Exchange Tool, or simply FLX is an easy online tool designed to guide customers through their application process. This tool exists in order to improve overall customer satisfaction and boost revenue.

# 3: User Stories

Below are some user stories which reveal how this website is helpful.
> + 'A User, __Is my licence valid for exchange__ in Ireland?'
> + 'A User, __I don't have time__ to sift through the overwhelming amount of information on the official NDLS website.'
> + 'A User, I want to __be confident that I'm not missing anything__ such as required documentation.'
> + 'A User, __Where is my local NDLS?__'
> + 'A User, I want to read some __common mistakes applicants make and how I can avoid them.__'
> + 'A User, I want to know how to __make an appointment.__'
> + 'A User, I want to __contact the NDLS__ helpline.'

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
>    * Verify eligibility.
>    * __Guide the user__ through the requirements, __help them understand__ their licence and __RSA rules.__
>    * Answer __common queries__ and concerns.
>    * Make the __forms and appointment booking system__ available.
>    * __Contact__ information.
### Content Requirements
>    * Home Page
>        * "Are You Eligible For An Irish Licence?"
>        * "Is Your Licence Exchangeable In Ireland?"
>        * Forms & Supporting Documentation
>        * "What Can You Expect Upon Arrival?"
>        * Less Common Issues
>    * Form Download Links & Descriptions
>    * Contact Us
>    * Book Appointment Link
---
## Structure Plane
### Information Architecture
>Simplicity and ease of comprehension is the focus.
>
>The home page will therefore contain almost all of the most relevant information. The content will be in order of importance. This will help the user accomplish their goals easier.
>
>The forms page will contain download links for all the relevant forms. In addition, descriptions and tips will be available.
>
>The contact page will contain a map with pinned NDLS locations, phone number to the helpdesk, contact form,
### Interaction Design
>Bite-sized paragraphs and clearly defined sections will allow the user to consume information with ease. This will also help avoid overwhelming the user with information.
>
>Provide contact form that the user can interact with.
---
## Skeleton Plane
>Wireframes can be found [here](https://github.com/JakubMrowicki/ci-ms1/blob/master/assets/docs/Wireframes.pdf)
>
>The website will be laid out over 3 pages. Home, Forms and Contact page.
>
>The navigation will contain a logo as well as links to the 3 pages. In addition there will be an external link for booking an appointment with the NDLS directly.
>
>The footer will contain copyright information, navigation links and some social media links.
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
Other Browsers
Mobile Devices 
Chrome Dev Tools
# 8: Problem Solving

# 9: Code Validation
HTML was Validated using the [W3 Validator](https://validator.w3.org/) and returned no errors.

CSS  was Validated using [Jigsaw W3 Validator](https://jigsaw.w3.org/css-validator/validator) and returned no errors.

Alicia Ramirez' [Closing Tag Checker for HTML5](https://www.aliciaramirez.com/closing-tags-checker/) was used to further validate the code.
# 10: Website Deployment
This project is deployed to the public by using GitHub Pages.
[View On GitHub Pages](https://jakubmrowicki.github.io/flx-tool/)

# 11: Credits & Acknowledgments
* Thanks to [AlecRust's response on StackOverflow](https://stackoverflow.com/a/41247934) I was able to add colour previews in my README file.
* Thanks to [Zim's response on StackOverflow](https://stackoverflow.com/a/54574324) I was able to center my logo on mobile devices without affecting desktop users.
* Thanks to [Necrone's reponse on StackOverflow](https://stackoverflow.com/a/33091315) for the blur effect code.
* Thanks to [Marco Trulla on codepen.io](https://codepen.io/Ragnarokkr/pen/KAejm) for a box-shadow vignette effect.
* Thanks to [Arseniy-II on StackOverflow](https://stackoverflow.com/a/56895999) for their smooth scroll solution.
# 12: Repositiory Support
For support please email at [xdshiftblue@gmail.com](mailto:xdshiftblue@gmail.com)