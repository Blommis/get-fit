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

## Project Goals
The Get Fit website is designed to inspire a healthy and active lifestyle by providing a modern, user-friendly, and visually engaging digital experience. The goal is to reflect the gym’s brand values while meeting the expectations of current and potential members.

### Objectives
* Strengthen Digital Presence:
Position the gym as a professional, welcoming, and energetic space through a sleek, functional website.

* Ensure Accessibility Across Devices:
Develop a fully responsive layout that performs seamlessly on mobile, tablet, and desktop.

* Increase Engagement and Conversions:
Encourage new memberships with strong calls-to-action, exclusive offers, and inspiring content.

* Build for Future Expansion:
Lay the foundation for potential features like storytelling from current members and online class schedule.

## Target Audience
The Get Fit website is designed to appeal to a broad and inclusive audience. It targets both current and potential gym members of all ages and fitness levels. The platform caters to beginners seeking a welcoming introduction to training, as well as experienced individuals looking for new challenges and inspiration.

### The website is structured to meet the needs of:

* Individuals just starting their fitness journey who value a supportive environment

* Seasoned gym-goers in search of variety, advanced training options, or community engagement

* Families, professionals, and students seeking flexible access to schedules, sign-ups, and updates

* Users of all ages who expect modern, intuitive digital experiences

* With a focus on accessibility, motivation, and community, Get Fit aims to position itself as the go-to gym for anyone looking to improve their health and well-being, regardless of their starting point.



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


## Wireframes 
### Homepage
<img src="assets/images/wf-homepage-desktop.png">
<img src="assets/images/wf-homepage-mobile.png">

### About us page
<img src="assets/images/wf-aboutpage-desktop.png">
<img src="assets/images/wf-aboutpage-mobile.png">

### Sign up page 
<img src="assets/images/wf-signup-desktop.png">
<img src="assets/images/wf-signup-mobile.png">

### Sign in page
<img src="assets/images/wf-signin-desktop&mobile.png">

## Bugs discovered
### Solved bugs 
* The navbar was overlapping the heading when clicking on "Contact" (index.html#contact). To fix this, I added `.section { padding-top: 4rem; }` in the CSS. However, this caused every heading with text to be pushed down, so I had to adjust it by adding `margin-top: 60px` to almost every ID in the CSS. 

* I solved the issue with the product cards not being of equal height across different devices by adding the h-100 class to the .card class. This ensures the cards are consistently the same height, regardless of the device or content size.

 



# Used technologies
* HTML: Hyper Text Markup Language 
* CSS: Cascading Style Sheets
* Javascript (Due to one of my bugs and tips from Boardwalking Games I used javascript once)

# Colors 
I chose these colors to create a balanced and visually appealing design. The bright yellow (#FFD43B) adds a vibrant and energetic touch, perfect for capturing attention and creating a sense of positivity. The dark grey (rgb(39, 39, 41)) provides a modern and professional feel, while black gives depth and contrast, ensuring readability. White is used to create clean spaces and highlight content, maintaining a minimalistic and sophisticated look overall. Together, these colors represent energy, professionalism, and clarity. The color blue (#2D89EF) and gray (#A6A6A6) represent basic and silver memberships, respectively. The use of red is intended to highlight prices, as this color tends to attract attention and is more visually appealing for promoting sales. Move on to next color - I have chosen #63E6BE for the check icon, which visually distinguishes the benefits offered by the different membership types.

* #FFD43B
* rgb(39, 39, 41);
* White 
* Black 
* Red
* #2D89EF
* #63E6BE
* #A6A6A6
* #212529 (Navbar: data-bs-theme ="dark")

<img src="assets/images/get-fit-colors.png">

# Fonts 
I chose these fonts to establish a clear and modern typography style. The primary font, "Inter," is clean, legible, and versatile, making it ideal for body text and ensuring a comfortable reading experience. It provides a professional, contemporary feel to the design. The secondary font, "Racing Sans One," adds a touch of uniqueness and personality, offering a more dynamic and engaging look for headings or emphasis. Together, these fonts balance functionality with creativity, ensuring a modern and approachable aesthetic.
* primary-font: "Inter", sans-serif;
* secondary-font: "Racing sans one", sans-serif;

<img src="assets/images/primary-font.png">
<img src="assets/images/secondary-font.png">

# Testing 
## Manuel testing 
1. User Experience Testing (Friends & Family)
To gain insights from diverse perspectives, I involved friends and family members of different ages and technical backgrounds in the testing process. They navigated the website independently, simulating a first-time visitor’s experience. This provided valuable feedback on layout structure, user flow, and how easy it was to find important information.<br><br> For example, they commented on how intuitive it felt to have a call-to-action button placed prominently at the top of the homepage. To enhance the user experience further, they suggested adding a shopping basket feature that would allow visitors to purchase memberships directly through the website, rather than needing to visit the gym in person.  

## Browser Testing
To ensure the website functions properly and maintains a consistent design across multiple platforms, I tested it manually in a range of browsers, including:

* Google Chrome
* Microsoft Edge 
* Safari (Ipad/iPhone)

I verified that the layout loaded correctly, fonts and colors displayed consistently, and that all interactive elements performed as expected.

## Button & Navigation Testing
Every clickable element on the website was tested thoroughly to ensure full functionality. This included:

* Navigation bar links
<img src="assets/images/navbar-links.png">

* Call-to-Action Buttons
Key buttons like “Sign me Up”, "Sign up" and “Sign In” were tested to make sure links and forms opened correctly and that validation worked as intended (e.g., requiring full name and valid email before submission).
However, the “Cancel” button currently does not function as expected, since there is no linked action or code responding when the user clicks it. This is a known issue that will be addressed in future updates to improve the overall user experience.

<img src="assets/images/calltoaction-button.png">
<img src="assets/images/signup&cancel.png">
<img src="assets/images/signinbutton.png">


* Newsletter Subscription Button
The newsletter subscribe button was tested to verify that user data could be submitted and confirmation messages appeared as expected.

<img src="assets/images/subscribe-button.png">

* Social Media Icons
Footer icons linking to external platforms like Instagram, twitter and Facebook were checked to ensure they opened the correct pages in new tabs.

<img src="assets/images/socialmedia-buttons.png">

* Utility Links
Links such as “Return to homepage” were also tested to ensure they improved usability by quickly guiding users back to the top of the page.
* Note on Terms & Privacy Link
The "Terms & Privacy" link included in the sign-up/in form is intentionally non-functional and does not redirect the user to another page. It has been added purely for visual purposes to reflect the typical structure of such forms. A comment in the HTML clearly indicates that the link is inactive.

<img src="assets/images/returntohomepage-button.png">
<img src="assets/images/terms&privacy.png">
<img src="assets/images/htmlcode-term&privacy.png">

## Form and input testing

Form and input fields were tested to ensure proper functionality, validation, and user guidance throughout the sign-up and login processes. 

All forms were tested to confirm that users are required to enter necessary details before proceeding. For example:

* The sign-up form correctly prompts users to fill in their full name and a valid email address.

* Attempting to submit the form with missing or incorrect data triggers built-in validation messages.

* Empty fields or improperly formatted emails (e.g., missing “@”) block submission and provide clear error cues.

<img src="assets/images/formerror1.png">
<img src="assets/images/formerror2.png">
<img src="assets/images/subscribeerror.png">

## User stories Testing

### Must haves
#### 1. User Story:
"As a visitor, I want the gym website to be user-friendly and responsive, so I can easily navigate and access information on any device."

Results: I resized the browser and used various devices (smartphone, tablet, laptop) using website: [Responsive Test Tool](https://responsivetesttool.com/)
, to confirm the layout adjusted smoothly. Navigation remained intuitive, buttons were clickable, and text stayed readable across screen sizes.
#### 2. User story:  
"As a visitor, I want to find the gym’s location, contact details, and opening hours, so I can visit or reach out with questions."

Results: The contact section was tested for visibility and accuracy. I checked that address, email, and phone number were easy to find and that the opening hours were clearly displayed. The layout remained intact on both mobile and desktop.

<img src="assets/images/contactinfo.png">
<img src="assets/images/opening-times.png">

#### 3. User story
"As a potential gym member, I want to see a gallery of people enjoying their workouts, so I can get motivated to join the gym."

Results: I verified that the high-quality images in the about/gallery section loaded correctly and displayed properly on all devices. In some cases, the loading time was slightly longer by a second or two.

<img src="assets/images/gallery.png">

#### 4. User story
"As a potential customer, I want to view detailed information about the different membership options,
so that I can choose the best plan for my needs."

Results: Membership types were checked for clarity and structure. Each plan displayed price, benefits, and duration, and users could easily scan and compare them. The design worked well across screen sizes, and content was optimized for readability.

<img src="assets/images/memberships.png">

### Should have

#### User Story:
"As a gym member, I want to subscribe to a newsletter, so I can stay updated on new classes, promotions, and events."

Results: The newsletter form was tested for email input validation. Submitting the form without a valid email triggered error messages, and submitting a correct email displayed a confirmation message. The feature was tested on different browsers to ensure consistent performance.

<img src="assets/images/subscribe.png">
<img src="assets/images/Tu-subscribe.png">

### Could have
#### User Story:
"As a gym member, I want to read success stories and testimonials from other members, so I can feel more motivated to join and stay committed."

Results: The storytelling stories section was designed to give a sense of community and motivate potential members by showcasing real gym experiences. I tested the section to ensure that testimonials were easy to read, responsive across devices, and visually engaging.

<img src="assets/images/storytelling.png">

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


 