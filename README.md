<h1 align="center"> Gym Day</h1>

## Introduction

Gym Day is a site that is designed to allow people to apply for a gym membership at a gym of the same name based in London, England. The target audience of this site is people who want to get fit at a gym and potentially wish to use a personal trainer. Gym Day aims to provide users with a quick, no hassle way to register for a membership and provides information about the gym itself - mainly through images and small amounts of text.

[The live view can be accessed here.](https://jackday94.github.io/Project1_Gym_Day/)

![Responsive Mockup](assets/images/gym-day-mockup.webp)

## Table of Contents

1. [Design](#design)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Testing](#testing)
5. [Deployment](#deployment)
6. [Credits](#credits)

## Design 

### Colours

When considering the colour scheme for the site, I wanted something that represented colours you may find within a gym such as weights, treadmills, gym attire etc. I therefore opted for a rather dark colour scheme for my hero image and header and footer, but also tried to use some colours with a brighter contrast to make things more welcoming to visitors.

![Colour pallete](assets/images/colour-pallete.webp)

### Font styles

For the font styles, I wanted something that was modern and would give strong headings that could be complemented by a lighter font for the main body. For this I used Google Fonts to choose the 'Koulen' style for headings and the logo and 'Roboto Flex' for the main body.

### Images

I chose to incorporate many images depicting people working out within a gym and some images of rooms full of gym equipment in order to showcase what the gym is like. I chose images that would work with the sections and pages that they were for. For example; the personal trainer section depicts focused shots of individuals within a gym. All of my images for this project are royalty free from Pexels or istock.

### Wireframes

I used Balsamiq Wireframes to create the basic structure of what I wanted my site to look like. This made it easier for me to focus on the styling of my site, as I already had a good idea of the layout.

- Desktop

![Desktop wireframe](assets/images/wireframe-desktop.webp)

- Mobile

  ![Mobile wireframe](assets/images/wireframe-mobile.webp)

## Features

### Existing Features

- __Navigation Bar__

  - The navigation bar is displayed on all pages of the site and features links to each page, for easy navigation and the logo of the site, which also acts as a link back to the home page.
  - The navigation bar is fixed and follows the user as they scroll the page, allowing them to click any of the navigation links wherever they are on the page.
  - When used on mobile devices, the navigation bar will act responsively by displaying vertically rather than horizontally.
  - The navigation links will change colour and underline when hovered and active, letting the user know what page they are currently on.

![Nav Bar](assets/images/navigation.webp)

- __The landing page__

  - The landing page features a large background image overlayed with text welcoming people to the site and a register button to entice users to register to the Gym.
  - The background image changes on smaller devices so that the user can still determine that they are looking at a website for a gym.
    - Desktop

    ![Home image desktop](assets/images/hero-photo-desktop.webp)

    - Mobile

    ![Home image mobile](assets/images/hero-photo-mobile.webp)

- __Why Should you join (About us) section__

  - The about us section highlights the benefits of registering for a membership at Gym Day and shows the user why it stands apart from other gyms, encouraging them to register. 
  - A carousel of images from the gym show users what they will gain access to with their membership and highlights the fun of being part of the gym.
  - Users can interact with the carousel with the forwards and backwards arrows. This allows them to look at specific images showing different parts of the gym. 

![About us](assets/images/about-us.webp)

- __Location section__

  - This section displays an embedded Google map showing the location of the gym to users, allowing them to easily find the gym. 
  - An image of the outside of the gym is displayed next to the map. This shows users what the entrance to the gym looks like so they know they have arrived at the right place.
  - The gym address is also displayed in plain text, making it easier for users to enter the address into sat navs to travel to. 

![Location](assets/images/location-section.webp)

- __Peronsal trainer section__ 

  - The personal trainer section shows profiles of personal trainers who work at the gym, encouraging users to register to get the benefit of using one of these trainers. 
  - This section also helps to highlight the friendlieness of the gym and aims to make users more comfortable in their registration.

![Personal trainers](assets/images/personal-trainer-section.webp)

- __Footer__

  - The footer section lists the social media pages of the gym using recognised icons for easy identification. Each link opens in a new tab so it doesn't disturb the users browsing on the Gym Day page.
  - This encourages users to follow and stay connected with any updates the gym may post on social media. 

![Footer](assets/images/footer.webp)

- __The Registration page__

  - The registration page allows users to register to the gym by filling out the form displayed on the page. The user is asked to provide their name, email, phone number and gender before they can submit their registration. 
  - When the user clicks submit, they are asked to confirm they wish to submit. This was done to prevent accidental submissions before the user was ready.

![Register page](assets/images/register-page.webp)

- __The Contact page__

  - The contact page is used to allow users to easily contact the gym about a query that they may have. On this page the user must enter their name, email, a topic and a message before they can send their message.
  - A dropdown list is provided for users to select a topic, allowing them to categorise their query more easily.
  - A confirmation box is also used when users submit, to prevent accidental submission.

![Contact page](assets/images/contact-page.webp)

- __Thank you pages__

  - When the user submits a form they are brought to either the register-complete page for the registration form, or the message-received page for the contact form. This provides feedback to the user that their submission has been completed successfully and lets them know that they will be contacted by the gym shortly after.

![Registration complete](assets/images/register-complete.webp)
![Message sent](assets/images/message-sent.webp)

### Features Left to Implement

- Payment page - I feel that a payment page would be good to implement to allow users to pay for their membership at the time of registering. This would benefit users by removing the need to pay for their membership in the gym itself, and potentially allow them to renew their membership online.

## Technologies

- HTML5 - Used for the structure and content of my web pages.
- CSS3 - Used for the styling of pages.
- [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/) - Used for its mobile-first approach, giving me more time to focus on styling rather than positioning. Also used for the image [carousel](https://getbootstrap.com/docs/5.1/components/carousel/#with-indicators) and personal trainer [cards.](https://getbootstrap.com/docs/4.3/components/card/#card-decks)
- [Font Awesome](https://fontawesome.com/) - For the social media icons used in the footer and the icons in the about us section.
- [Google fonts](https://fonts.google.com/) - Used to choose the fonts for my site.
- [Gitpod](https://www.gitpod.io/) - Used as my code editor.
- [GitHub](https://github.com/) - Used for deploying and hosting my site.

## Testing 

This section details the testing I undertook to ensure that my site functioned as it was required.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjackday94.github.io%2FProject1_Gym_Day%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjackday94.github.io%2FProject1_Gym_Day%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) (The warnings produced are due to the imported bootstrap styles).
- Accessability via Lighthouse
  - No accessability issues found for the [home page.](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fjackday94.github.io%2FProject1_Gym_Day%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)
  - No accessability issues found for the [register page.](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fjackday94.github.io%2FProject1_Gym_Day%2Fregister.html&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)
  - No accessability issues found for the [contact page.](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fjackday94.github.io%2FProject1_Gym_Day%2Fcontact.html&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)  

### Form Testing

- I tested all my forms on the site to ensure they didn't allow the user to submit without entering the required information.

![Register Test](assets/images/register-form-test.webp)
![Contact Test](assets/images/contact-form-test.webp)

- I also tested my forms to see if they would ask for confirmation before submitting.

![Confirmation check](assets/images/confirmation-check.webp)

### Link Testing

- I made sure that all my links were working and links to external sites, such as those used in the footer, opened sites in a new tab when clicked.

### Mobile Testing

- To test my site for responsiveness on mobile devices I used Mozilla Firefox and Google Chrome developer tools to resize my viewport to suit various mobile devices. 
- I checked responsiveness both in portrait and landscape views to ensure all site features functioned and that a user could use the site for its intended purpose. The smallest viewport size that I tested was 320x480.
- I also used my mobile device (Samsung Galaxy S20 Ultra 5G) and my brother's devices (iPhone 11/ iPad Pro 12.9) to test on physical devices using different operating systems. This allowed me to simulate real world scenarios where the site will be viewed on different devices.

### Bugs

- As of the time of deployment there are no current bugs that I have experienced with the site. However, when testing different viewports for responsiveness earlier in development, I noticed that sometimes my top navigation would disappear and then reappear after dragging the viewport. This only occured twice and I have not been able to effectively replicate it.

## Deployment

I deployed my site to GitHub pages using the following steps:
  1. Select Project1_Gym_Day from my GitHub dashboard, navigate to the Settings tab 
  2. From the 'Code and automation' left menu, select pages
  3. From the source section select the main branch in the drop down menu, select save
  4. Once the main branch has been saved, the GitHub pages section will display a message saying that the site is ready to be published at https://jackday94.github.io/Project1_Gym_Day/
  5. After waiting for a few minutes and refreshing the page, GitHub pages will now display a messaging saying 'Your site is published at https://jackday94.github.io/Project1_Gym_Day/'
  6. The site is now deployed and can be viewed using the provided link 

## Credits 

### Content 

- Instructions on how to implement the header, footer and hero image were taken from the [Code Institute Love Running course material](https://codeinstitute.net/)
- Templates for the image carousel and card-deck trainer profiles were taken from the following Bootstrap pages: 
  - [Carousel](https://getbootstrap.com/docs/5.1/components/carousel/#with-indicators)  
  - [Card-deck](https://getbootstrap.com/docs/4.3/components/card/#card-decks)
- The icons in the footer and about us section were taken from [Font Awesome](https://fontawesome.com/)
- Instructions on how to implement flexbox, which I used to central align my forms and welcome text, were provided by [this article on css-tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-background)
- Information on various HTML and CSS atrributes and tags was taken from [W3Schools](https://www.w3schools.com/)
- Instructions on how to implement a confirmation box before form submission was taken from [stackoverflow](https://stackoverflow.com/questions/27921283/add-a-confirmation-alert-before-submitting-a-form)
- My mentor, Reuben Ferrante, for providing valuable feedback and showing me how to modernise my site by removing borders and applying a dark opacity to my background images.

### Media

- All images on my site (except the outside gym image) were taken from the free stock photo library [Pexels](https://www.pexels.com/)
- The image of the outside of the gym was taken from the stock photo site [iStock](https://www.istockphoto.com/)
- To look for colours for my website that would contrast well with each other, I used the website [Coolors](https://coolors.co/)
- I used the website [PureGym](https://www.puregym.com/) and [this bootstrap theme](https://startbootstrap.com/previews/agency) for some inspiration to the layout of my site.


