# Biotope Aquascaping
## Milestone Project One
Biotope Aquascaping is a business concept that brings together the love for aquatic plants, nature and fish keeping. Aquascape aquariums are beneficial to physical and mental wellbeing and can have a positive, calming, stress-relieving effect on both their owners and viewers. Bioptope Aquascaping offers their services to rebuild the clients' old aquariums or create new ones in places like private houses, offices, dentist cabinets, restaurants, or wherever the conditions are favorable. Based on years of experience and learning from their mistakes, Biotope Aquascape can design and build clients' future aquariums from the ground up. The purpose of the website is for them to be easily reached and also to share information about them and what they do.
***
## Demo
The live website can be viewed here - [Biotope Aquascaping](https://florindorneanu.github.io/biotope-aquascaping/)

The GitHub repository can be viewed here - [FlorinDorneanu/biotope-aquascaping](https://github.com/FlorinDorneanu/biotope-aquascaping)


![Responsive Home Page](images-readme/responsive-home.png)
![Responsive Services Page](images-readme/responsive-services.png)
![Responsive Benefits Page](images-readme/responsive-benefits.png)
![Responsive Contact Page](images-readme/responsive-contact.png)
***

## User Experience (UX)

## Strategy


### User Stories
#### First Time Visitor Goals
* As a first-time visitor, I want to be able to easily navigate throughout the site to find content;
* As a first-time visitor, I want to easily understand the purpose of the website;
* As a first-time visitor, I want to see pictures with the artwork;
* As a first-time visitor, I want to be able to navigate throughout the site with ease;
* As a first-time visitor, I want the links to function as expected.

### Returning Visitor Goals
* As a returning visitor, I want to find the best way to contact the business;
* As a returning visitor, I want to find the social links.

### Reasons a user may visit the site 
* A user looking to know more about aquascaping;
* A user conducting research on our services;
* A user seeking to beautify their home or workspace;
* A user looking to rebuild the already-existing aquarium;
* A user trying to get in touch with the business.

### Reasons for the website
* Increase clients;
* Provide a way for new and existing clients to contact the business;
* Self-promotion.

## Scope - Functionality
* The site must be easy to navigate around;
* The site should have a simple and visually appealing design;
* The site should function as expected.

## Scope - Content
* Tell the audience about our services;
* Let the audience know about the benefits of biotope aquascaping;
* Make it easy to get in touch by contact form and social media.

## Structure

This website will consists of four pages:
* A Home page, with a small description and a "services" button;
* A Services page which will contain three services that the business has to offer;
* A Benefits page that lists the benefits of having an aquascape aquarium;
* A Contact page with a form to get in touch with "Biotop Aquascaping".


## Skeleton
* Home Page Wireframes - [desktop and mobile](images-readme/home-wireframe.png)
* Services Page Wireframes - [desktop and mobile](images-readme/home-wireframe.png)
* Benefits Page Wireframes - [desktop and mobile](images-readme/home-wireframe.png)
* Contact Page Wireframes - [desktop and mobile](images-readme/home-wireframe.png

## Surface

### Colour

This website was requested to have a simple yet visually appealing design. To keep up with the request, two colours were used throughout the site: Teal(#008080) and White(#FFF). These colours go perfect with the aquatic theme that was chosen.

### Imagery

The images chosen for the "Services" page were taken from [this website]() to showcase exactly what every type of decorated aquarium could look like for the users to get not only readble information but also a visual example. The background image(banner image) was taken from [Envato]() and it was chosen for the nice contrast and to to keep up with the theme of the website.

### Typography

For fonts, https://fonts.google.com/ has been used. For headings, "Source Sans Pro" has been chosen and for the content, "Poppins" font was chosen because it goes perfectly with the "Source Sans Pro" font and it gives the website a modern and playful vibe. Letter spacing was increased in some places to make the text more defined and to stand out.

This code was imported at the top of the style.css file:
```
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&family=Source+Sans+Pro&display=swap');
```

### Call to Action
* The navigation bar in the header section are highlighted with a nice hover effect: an underline that start from the left side and goes for 0.4 seconds to the right side when the mouse is hovered over them.
* On the Home page, a "Services" button has been added for the user to easily access it when entering the website. For consistency reasons, the button has the same effect as the navigation links.
* The "Send" button from the contact form was styled white with black text for contrast purposes.
* The colour "Teal" was used for styling the social links. The media links will send the use to "Biotope Aquascaping" social media pages.
***
## Features
### Navigation Bar and Logo
The navigation bar and logo are set at the top of the webpage. The navigation links are highlighted when hovered over. When clicked, the logo sends the user to the home page. The navigation links take the user tp the correct page of the website. For the larger screens, the logo is placed in the top left corner of the webpage and the navigation is in the top right corner of the webpage. On smaller screens, the navigation bar goes under the logo and both elements are centered.

### Responsiveness
The website is responsive at all breakpoints. The page layout will change to something more suited to smaller devices when needed. This has been achieved using media queries. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily.

### Accessibility 
Alt-attribute and aria-label have been added to every image and navigation link. Header elements have been used in sequence so that the site makes semantic sense to screen readers. High contrast has been used throughout the design.

### Footer
The footer contains the social links for [Facebook](https://www.facebook.com/), [Twitter](https://twitter.com/), [Youtube](https://www.youtube.com/) and [Instagram](https://www.instagram.com/).

### Home Page
Features an inviting heading, a small description and a "Services" button. All of them are positoned in the center of the page.

### Services Page
A heading is placed at the top of the page. Underneath the heading, an icon is set inside a circle designed with two lines by its sides. Moving further, this page consists of three types of aquariums that the business can provide. An image and a description of every type of aquarium are set at each one of them. As this is a fictive business created for the Milestone Project One, the images were taken from [this website]() and the descriptions were inspired by [this website]().

### Benefits Page
As in the "Services" page, heading is placed at the top of the page, having the same style for the icon. This page contains four benefits of aquascape aquariums. Every benefit has a description of it. In the "Reduces Axiety" section an external link for a study is provided so that the user can learn even more from there. On the right side of each benefit title, an specific icon can be found.

### Contact Page
Consists of:
* A contact form;
* The form includes fields for the user to enter their business name and contact details using - input type="text";
* The email input field requires the answer to be an email;
* The "Mobile" input field must be a number to be valid;
* There is a - textarea - to allow the user to ask any further details. I have used placeholder text to encourage the user to make any further comments;
* The submit button has high contrast;
* The form is stacked for mobile use;
* All fiels are set to "required".
***

## Technologies Used
* HTML5 - Mark-up language using semantic structure.
* CSS3 - Cascading style sheet used for styling.
* Gitpod.io - For writing the code, using the command line for commiting and pushing to GitHub.
* GitHub - Used to host the repository.
* Git - Used for version control of the project.

### Design
* [Google fonts](https://fonts.google.com/) - For styling the typography.
* [Balsamiq wireframe](https://balsamiq.cloud/) - To build wireframes in the design phase.
* [Font Awesome](https://fontawesome.com/) - For the social media icons.
* [Beautifier](https://beautifier.io) - To beautify my code.
* [Tiny PNG](https://tinypng.com/) - To compress my images.
* [Online-Convert](https://image.online-convert.com/convert-to-webp) - To convert my images to WebP.

### Testing
* [HTML Validator](https://validator.w3.org/#validate_by_input) - Testing validity of HTML.
* [CSS Validator](https://jigsaw.w3.org/css-validator/) - Testing validity of CSS.
* [Am I Responsive](https://ui.dev/amiresponsive#) - Checking the responsive nature and creating the mock-ups provided.
* DEV Tools - Lighthouse.

## Testing
* Tested that the logo sends the user to the home page.
* Tested if the user is sent to the correct page of the website when clicking the navigation links.
* Tested that the "Services" button works.
* Tested that the "Send" button works.
* Attempting to submit the form without required fields results in a browser error message.
* Attempting to submit the form with an email that doesn't contain the appropriate tokens results in a browser error message.
* Submitting the form with all the correct information provided, sends the user to the Code Institute form dump, which displays data from all the fields.
* Clicking on the social media links in the footer results in the browser navigating to the appropriate social media site in a new browser tab.

[HTML Validator]((https://validator.w3.org))

![HTML Validator Home Page](images-readme/homepage-validator.png)

![HTML Validator Services Page](images-readme/servicespage-validator.png)

![HTML Validator Benefits Page](images-readme/benefitspage-validator.png)

![HTML Validator Contact Page](images-readme/contactpage-validator.png)

[CSS Validator](https://jigsaw.w3.org/css-validator/)

![CSS Validator](images-readme/css-validator.png)
***

### Performance Testing

Tested using the Developer Tools Lighthouse for desktop and mobile :

### Desktop
![DevTools Home Page Desktop](images-readme/devtools-home-desktop.png)
![DevTools Services Page Desktop](images-readme/devtools-services-desktop.png)
![DevTools Benefits Page Desktop](images-readme/devtools-benefits-desktop.png)
![DevTools Contact Page Desktop](images-readme/devtools-contact-desktop.png)

### Mobile
![DevTools Home Page Mobile](images-readme/devtools-home-mobile.png)
![DevTools Services Page Mobile](images-readme/devtools-services-mobile.png)
![DevTools Benefits Page Mobile](images-readme/devtools-benefits-mobile.png)
![DevTools Contact Page Mobile](images-readme/devtools-contact-mobile.png)





