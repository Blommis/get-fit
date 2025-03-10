# Get Fit website 

## How to View the Project
- [View the deployed website](https://blommis.github.io/get-fit/)

## Table of contents 
1. [Get Fit](#get-fit)
2. [How to View the Project](#How-to-View-the-Project)
3. [Tables of content](#Tables-of-content)
4. [Description](#Description)
5. [Features](#Features)
6. [Wireframes](#Wireframes)
7. [Bugs discovered](#Bugs-discovered)
8. [User stories](#User-stories)
9. [Used technologies](#Used-technologies)
10. [Colors](#Colors)
11. [Fonts](#Fonts)
12. [Testing](#Testing)
13. [Validation and Issues](#Validation-and-Issues)
14. [Lighthouse](#Lighthouse)
15. [Credits](#Credits)
16. 

## Description
This project is a modern and responsive gym website designed to provide users with an engaging and seamless experience. The website features an intuitive layout, eye-catching design, and essential information about the gym's services, membership plans, and class schedules.

Key features included: 
* A hero section with a compelling call-to-action for new members to sign up and get a 20% discount.
* A fully responsive design, ensuring accessibility on all devices.
* A membership sign-up and sign in form with an exclusive discount offer.
* About page with gallery of the members, gym itself and member stories. 



## Features
1. Navigation
2. Contact
3. About
4. Sign up 
5. footer

## Wireframes 
### Homepage
<img src="assets/images/Skärmbild 2025-03-04 104131.png">
<img src="assets/images/Skärmbild 2025-03-04 104232.png">

### About us page
<img src="assets/images/Skärmbild 2025-03-04 104312.png">
<img src="assets/images/Skärmbild 2025-03-04 104344.png">

### Sign up page 
<img src="assets/images/Skärmbild 2025-03-04 104444.png">
<img src="assets/images/Skärmbild 2025-03-04 104509.png">

## Bugs discovered
### Solved bugs 
* The navbar was overlapping the heading when clicking on "Contact" (index.html#contact). To fix this, I added `.section { padding-top: 4rem; }` in the CSS. However, this caused every heading with text to be pushed down, so I had to adjust it by adding `margin-top: 60px` to almost every ID in the CSS. 

* I solved the issue with the product cards not being of equal height across different devices by adding the h-100 class to the .card class. This ensures the cards are consistently the same height, regardless of the device or content size.


## User stories 

### Responsive User Experience (Must haves 1)

#### User Story:
As a visitor, I want the gym website to be user-friendly and responsive, so I can easily navigate and access information on any device.

#### Acceptance Criteria:

* The website automatically adjusts to different screen sizes (desktop, tablet, mobile).

* Navigation is clear and intuitive, with a well-structured menu.

* Buttons, forms, and text are easily readable and accessible on all devices.

* Pages load quickly and do not break on smaller screens.

#### Tasks:

* Implement responsive design using CSS Grid/Flexbox and media queries.

* Optimize images and content for faster load times.

* Conduct usability testing to ensure smooth navigation.

Ensure all buttons, links, and forms are touch-friendly for mobile users.



### create contact sesssion (Must haves 2)

#### User story: 
As a visitor, I want to find the gym’s location, contact details, and opening hours, so I can visit or reach out with questions.

#### Acceptance Criteria:

* A contact section includes the gym’s address, phone number, and email.

* Opening hours are displayed clearly on the contact section.

#### Tasks:

* Create a contact section with gym details.

### Get a gallery of the gym showing people and environment (Must haves 3)

#### User Story:
As a potential gym member, I want to see a gallery of people enjoying their workouts, so I can get motivated to join the gym.

#### Acceptance Criteria:

* The gallerypage features high-quality images of gym-goers exercising.

* A dedicated gallery contains motivational photos.

* All media is optimized for fast loading and responsiveness.

#### Tasks:

* Design and develop a about pagesection showcasing gym photos.

* Ensure mobile-friendly optimization for images.

### Displaying Different Types of Memberships (Must haves 4)

#### User Story: 
As a potential customer, I want to view detailed information about the different membership options,
so that I can choose the best plan for my needs.

#### Acceptance Criteria:

* The system displays all available membership types with a clear description.

* Each membership type includes pricing, benefits, and duration.

* Users can compare different memberships easily.

* The design is responsive and works on all devices.

#### Tasks:

* Design and structure a section that lists all membership types.

* Add key details for each membership (price, benefits, duration).

* Implement a comparison feature (optional).

* Ensure the layout is responsive on desktop and mobile.

* Test the page for usability and readability

### Subscribe to newsletter section (Should have 1)

#### User Story:
As a gym member, I want to subscribe to a newsletter, so I can stay updated on new classes, promotions, and events.

#### Acceptance Criteria:

* A subscription form allows users to enter their email.

* Users receive a confirmation page after signing up.

* The admin can send monthly newsletters with gym updates.

#### Tasks:

* Develop a subscription form with email validation.

* Implement an email confirmation system.

### Storytelling (Could have 1)

#### User Story:
As a gym member, I want to read success stories and testimonials from other members, so I can feel more motivated to join and stay committed.

#### Acceptance Criteria:

* Create a storytelling stories from gym members

#### Tasks:

* Design a success stories page with real gym members’ feedback.

* Implement moderation tools for admin approval.


# Used technologies
* HTML: Hyper Text Markup Language 
* CSS: Cascading Style Sheets
* Javascript (Due to one of my bugs and tips from Boardwalking Games I used javascript once)

# Colors 
I chose these colors to create a balanced and visually appealing design. The bright yellow (#FFD43B) adds a vibrant and energetic touch, perfect for capturing attention and creating a sense of positivity. The dark grey (rgb(39, 39, 41)) provides a modern and professional feel, while black gives depth and contrast, ensuring readability. White is used to create clean spaces and highlight content, maintaining a minimalistic and sophisticated look overall. Together, these colors represent energy, professionalism, and clarity.

* #FFD43B;
* rgb(39, 39, 41);
* White
* Black 

# Fonts 
I chose these fonts to establish a clear and modern typography style. The primary font, "Inter," is clean, legible, and versatile, making it ideal for body text and ensuring a comfortable reading experience. It provides a professional, contemporary feel to the design. The secondary font, "Racing Sans One," adds a touch of uniqueness and personality, offering a more dynamic and engaging look for headings or emphasis. Together, these fonts balance functionality with creativity, ensuring a modern and approachable aesthetic.
* primary-font: "Inter", sans-serif;
* secondary-font: "Racing sans one", sans-serif;


# Testing 
## Manuel testing 
As part of the manual testing process, I enlisted my girlfriend to assist in evaluating the functionality and user experience of the system. She tested various features, navigating through different user flows to identify potential issues. Her feedback was invaluable in highlighting areas for improvement, such as usability and responsiveness.

In addition to basic functionality testing, manual testing can include verifying form submissions, ensuring accessibility features are working, checking compatibility across different browsers and devices, and performing exploratory testing to uncover hidden bugs. This hands-on approach ensures a more thorough review of the system, addressing both expected and unexpected user behaviors.

## Validation and Issues 
* index.html
* about.html
* signup.html

### HTML
* When I reviewed my HTML pages, I found an issue where I had two sections with the same name, #new-contact, which I had to fix. Instead, I changed the second one to #second-contact.
*  I also noticed that the aria label couldn't be selected in the <form>, so I removed it (I had an image there). 
<img src="assets/images/Skärmbild 2025-03-06 132555.png">
<img src="assets/images/htmlissue.png">
<img src="assets/images/Skärmbild 2025-03-06 163257.png">

### CSS
* I didn't find any errors when I reviewed my CSS.
<img src="assets/images/Skärmbild 2025-03-06 212753.png">

# Lighthouse
* I reviewed the Lighthouse report, and the results were good across all pages, including performance, accessibility, and best practices.
<img src="assets/images/homepagelighthouse.png">
<img src="assets/images/Skärmbild 2025-03-07 082637.png">
<img src="assets/images/Skärmbild 2025-03-07 090846.png">
<img src="assets/images/Skärmbild 2025-03-07 112134.png">
<img src="assets/images/Skärmbild 2025-03-07 112032.png">
<img src="assets/images/Skärmbild 2025-03-07 112251.png">

## Credits
- The code for the social media icons animations was taken from [font awesome](https://fontawesome.com/)
- The code for mine font styles was taken from [Google fonts](https://fonts.google.com/)
- The images (Free) was taken from [Unsplash] (https://unsplash.com/)


 