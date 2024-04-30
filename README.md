# Rose-Garden-

   Rose Garden website is page for people looking for a shop to purchase rose flowers.

   Users of this website will be able to get informations on Rose Garden i.e, what we do, open times, get in touch, gallery and how to place an order.

   The site can be accessed by this [link](https://ovundiano.github.io/Rose-Garden-/)

![Responsive Mockup](documentation/responsive-image.webp)

## Features 

- __Navigation Bar__

  - Featured on the top of all three pages. It shows the garden name on the left corner: Rose Garden.
  - On the right top it shows links of Home, Gallery and Order which links to different pages of the Web page.
  - The navigation is in a Lato font with Rose Garden in Italic font style and other links in normal font style and a color that contrast with the background.
  - The navigation clearly tell the users the name of the website with informations easy to find in different sections.

![Nav Bar](documentation/nav-bar.png)

- __The Hero Section__

  - The hero section includes a photograph of rose flower as the background with text overlay.
  - It shows the name and address of the garden in white text.
  - It provides the users with clear information of different colors of rose flowers and it's symbolic meaning.
  - It also tell the users what rose garden specializes on. 
  - This section also contain the what we do section include an image of rose flower as the background with text overlay.
  - This section gives details to users on what rose garden does: Vase collection, Funeral, New baby/Baby shower, Birthday, Gift Sets and Sympathy arrangement. 
  - This section introduces the user to Rose Garden with an eye catching animation to grab their attention.
  - This should also encourage users to consider placing an order for rose flowers. 

![Hero section](documentation/hero-image.webp)

- __Contact__

  - This section contains the different opening times of weekdays and weekends.
  - It also contain the contact details of rose garden to enable users get in touch with rose garden for more clarification.
  - This section will be updated as these times change to keep the user up to date. 

![Contact](documentation/contact-image.png)

- __The Footer__ 

  - The footer section contains social media icon links to enable the users find us on facebook, instagram and youtube.
  - The footer is important to users because it gives them the ability to find us on social media.

![Footer](documentation/footer-image.png)

- __Gallery Page__

  - The gallery contains images of rose flowers in different colors.
  - This section gives users the room to make choices of the colors of rose flowers they want.

![Gallery](documentation/gallery-image.png)

- __The Order Page__
  - This page has a rose flower as the background.
  - This section has a form to collect details from the users to help them place orders.
  - The form collects the users name, email address, pick up means and submit button.
  - This enable users to place an order after viewing the web page.

![Order page](documentation/order-image.png)

  __The Response Page__
  - This page has a rose flower as the background.
  - It is the feedback a user get after filling the order form to place an order.
  - It gives users the knowledge that there orders has been received and will be processed.

  ![Response page](documentation/response-image.png)
  
## Testing 

- I tested that this page works in different browsers: Chrome and Firefox.
  
- I confirmed that this page is responsive, looks good and functions on all standard screen sizes using the devtools device tool bar.

- I confirm that the navigation, Home Gallery and Order are all readable and easy to understand.

- I confirm that the form works requires entry in every field, will only accept an email in the email field and the submit button works.

## Validator testing

+ ### HTML
    - Initially, three errors were found in the footer section of all the HTML pages, which has been rectified and has no error currently. Errors are detailed in the Bug section.

  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Home Page HTML Validator](documentation/w3-vallidator-homepage.png)

    #### Gallery Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/w3-vallidator-gallery.html.png)

  #### Order Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Order Page HTML Validator](documentation/w3-vallidator-order.html.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3-vallidator-response.html.png)
    
+ ### CSS

  - No errors were returned when passing through the official W3C CSS Validator (Jigsaw).

  ![Jigsaw CSS Validator](documentation/css-validator-image.png)

 ## LightHouse report
 - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/home-lighthouse.webp)

   ### Gallery page

  ![Gallery Page Lighthouse](documentation/gallery-lighthouse.png)

  ### Order page

  ![Order Page Lighthouse](documentation/order-ligthhouse.png)

  ### Response page

  ![Response Page Lighthouse](documentation/response-ligthhouse.png)

 ## Bugs

 ### Solved bugs
   1.  There was duplicate ID of networks in the footer section of all three pages of html.
    
    -Solution: I changed the ID of social-networks in the unordered list to class and added an ID of icon.

![Bug](documentation/bug-image.png)

#### Unfixed Bugs

None.

## Deployment

### Deployment to GitHub Pages

  - The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab.
  - From the general navigate to pages.
  - In the pages, from the source drop down menu, select the main branch, then click save.
  - Once saved, the link will be created to the website. 

The live link can be found [here](https://ovundiano.github.io/Rose-Garden-/)

#### Local Deployment

In order to make a local copy of this project, you can clone it.
In your IDE Terminal, type the following command to clone my repository:

- `git clone https://github.com/Ovundiano/Rose-Garden-.git`

- Alternatively, if you use Gitpod, you can [click here](https://gitpod.io/#https://github.com/vundiano/Rose-Garden-), which will start the Gitpod workspace for you.

## Future improvements
- Add favicon with [Favicon Generator. For real.](https://realfavicongenerator.net/);
- Add custom 404 page;
- Improve the quality of the commit messages (I am aware that some of them are not very clear and not meeting the standards and will improve them in the future);
- Add accessability report with [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/);

## Credits  

### Content 

- Inspiration for the what we do section came from [Flowers.IE](https://flowers.ie/collections/rose-arrangements)
- The meaning of different Rose colors was gotten from [Surprose.com](https://www.surprose.com/blog/meaning-of-rose-colours#:~:text=For%20example%2C%20blue%20roses%20symbolise,fresh%20start%20or%20a%20farewell.)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The Lato font was gotten from [Google Font](https://fonts.google.com/)

#### Media

- All images gotten from [Amazon.com](https://www.amazon.co.uk/roses-flowers/s?k=roses+flowers)

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items simmetrically on the pages.
- [Gitpod](https://www.gitpod.io/) was used as the main tool to write and edit code.
- [GitHub](https://github.com/) was used to host the code of the website.
- [Git](https://git-scm.com/) was used for the version control of the website.
- [Tinypng](https://tinypng.com/) was used for resizing images.
- [Pinetools](https://pinetools.com/merge-images) was used for merging images.

## Acknowledgment

- Divine Mazi, My wife was a great support system towards the realization of this project.
- [Iuliia Konovalova](https://github.com/IuliiaKonovalova) was a great mentor and was very supportive towards making this project see the light of the day.
- [Code Institute](https://codeinstitute.net/) tutors and Slack community members for their support and help.
- [Kevin Powell](https://www.youtube.com/user/KepowOb) for his amazing CSS tutorials.
- [Love Running](https://codeinstitute.net/) tutors and Slack community members for their support and help.
