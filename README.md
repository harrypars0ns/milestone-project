# The Gardeners Cooperative

User-Centric-Frontend-Development-Milestone-Project.

This website is to be used as: a portfolio for potential clients and a place for people to get in touch to work with us. It provides essential information on the nature & structure of the company, a portfolio of examples of our work plus a contact form with social media links.
 
## UX
 
The site was designed to be as user friendly as possible. As we are catering to most of west London I wanted to make sure that the UX was viable for elderly people, those with bad eye-sight, people with dyslexia and those who aren't comfortable using complex websites.

We work with nature and I wanted the design to acknowledge and represent that; I used natural colours like green, brown, lavender, sky-blue and blossom-pink. 

The font sizes have been set to the biggest and most legible they can without sacrificing the usability and aesthetic of the website.

Whether you are a prospective client or a member of the collective you will have no problems in your experience of this site.

## Features
The carousel was added as a way to show many images of our work without taking up too much "real-estate". I incorporated parallax scrolling which adds a lot of depth to the site. The navbar has some animation and is stuck to the top of the screen for constant control over where you want to go.  

### Features Left to Implement


- When I have time I would like to add a sign-in option with 'Gardener' and 'Customer' account types. Gardeners would have access to message boards for all our workers to plan jobs, enlist help and seek work. 

## Technologies Used

- HTML
- CSS
- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** for aiding placement and using established design trends such as FontAwesome icons and buttons.
- [Google Fonts](https://fonts.google.com/)
    - The project uses the **Google Fonts** 'Exo' & 'Roboto' in varying weights and sizes.

## Testing

When I started this project I got about halfway through before I realised I hadn't made it truly responsive. After writing a silly number of media queries in some attempt to cover all screen sizes I decided to start again with a new, responsive foundation on which everything would work properly. Now the site looks good across all screen sizes including mobile, tablet, desktop and landscape-mobile.

When clicking the portfolio section of the NAV, the nav bar used to cover the 'Portfolio' heading. Now if you click it it should transport you a few pixels above the heading.

If you don't enter required information in the contact form, it will not submit. An error message will display. This will also occur if an invalid email address is submitted. If all information is valid, the page will reload.

The 'About'/'Portfolio' section was made to take up as much space as the content requires to let the text and carousel respond to the screen size. Using the mobile simulator on Chrome Dev Tools you can see this working. The carousel controls have been tested to make sure they scroll properly on all devices.

The site works across many browsers including: Chrome, Firefox, Safari and Edge. The site works across ALL mobile sizes. I had a terrible moment when I thought I had finished only to find that the site doesn't work on a on a mobile in landscape mode. Landscape now works perfectly on all mobiles.

The social media buttons are not currently linked to anywhere so they will load the page again in a new tab. They will (when social media is set up) link to the 'TGC' profile of the relevent social media sites in a new tab.

I had a button with a call to action on the landing page but the icon in the button was not available on some mobiles. I have removed the button until this gets sorted. 

I ran the css through the W3C validator with no errors found.



## Deployment

I am hosting the site on GitHub pages on the master branch. If you want to run the code locally you can use 'git clone'. Alternatively you can download all the files in a .zip file and open 'index.html' in your browser of choice.


## Credits

### Content

I built the Nav-bar and form from scratch. Content from the "About us" section was written by me. 


### Media
I used Pexels (stock images) for all my images, because people upload a whole photo shoot I could get a selection.
I cropped the images in the carousel so they were all the same size. I also darkened some images that needed higher contrast with the light text.


### Acknowledgements

- The Carousel is a bootstrap component. I added more spots for images in the carousel so that I could have more examples of our work. (https://getbootstrap.com/docs/4.4/components/carousel/)

- I used the Bootstrap grid for responsive placement. (https://getbootstrap.com/docs/4.4/layout/grid/)
 

