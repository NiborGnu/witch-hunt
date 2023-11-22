# Witch Hunt

The witch hunt website is made to inform people about the witch hunt in Sweden called "the Great Noise". With information from that time and records of 3 trials at that time.

The site can be viewed on GitHub pages [here](https://niborgnu.github.io/witch-hunt/)

![Responsive Mockup](documentation/all-devices-black.png)


---
---

## User Stories

### First Time Visitor Goals:
* As a First Time visitor, I want to easily understand the main purpose of the site, so I can learn more about the content.
* As a First Time Visitor, I want to be able to easily navigate through the website, so I can find the content.

### Returning Visitor Goals
* As a Returning Visitor, I want to be able to read more in-depth records about trials and first-hand writings.

## Features

+ ### Navbar

+ ##### Navigation
    - Positioned at the top of the page.
    - Contains logo on the left side.
    - Contains navigation links on the right side:
        * HOME - leads to the Home page
        * WITCHES - leads to the page where you can read about witches and their trials.
        * CONTACT - leads to the contact page where you can contact the site owner.
    - The links have animated hover effects.

    - The navigation is clear to understand for the user.
    ![NavBar desktop](documentation/nav-bar-desktop.png)

    - The navigation bar is responsive:
        
        * On mobile devices:

            * On Mobile: The navigation bar is filled with the logo to the right and a bars menu is implemented on the right side.
            ![NavBar Mobile Closed](documentation/nav-bar-mobile.png)

            * When the bars menu is clicked, there is a dropdown menu with the links.
            ![NavBar Mobile Open](documentation/nav-bar-mobile-dropdown.png)

        * On tablets: The navigation bar looks the same as on the desktop
        ![NavBar desktop](documentation/nav-bar-desktop.png)


---
+ ### Home Page:

    - Background image is put in the HTML body of the page

    - Represent:

        * The concept of the page
        * Invite interest to read more

    - The page is responsive on all common screen sizes.

        ![Responsive Mockup](documentation/home-screen.png)

---

+ #### Hero Section

    - The hero section consists of 3 text brackets 
    and on-screen bigger than 768px 2 image

        * Page title introducing the great noise
        * Information about how many victims and an image 
        * Information about the reason and questions of why and an image

    ![Hero Section](documentation/hero-section-desktop.png)

--- 

+ #### Video Section

    - Titel to let the user know there is a video about the Great noise to see here

    - Shows a video about the great noise

    
    ![Video Section](documentation/video-section-desktop.png)

---

+ #### Witches section

    - Titel tells users that here they can be directed to read more about 3 specific witches and their trails

    - Indication to read more about Stor-Märit from Lillhärdal 

    - Indication to read more about Elisabetta from Näs

    - Indication to read more about Margreta from Sund

    ![Witches Section](documentation/witches-section-desktop.png)


---
+ #### Footer

    - Footer contains social media links that open in a new tab.
​
    ![Footer](documentation/footer-desktop.png)
​
---
+ ### Witches Page

    - Same background image on this site as on the Home page.

    - Witches page has a title to introduce the page and tell the user that on this page you can read about prominent witches and their trials.

    - 3 sections each about different witches an introduction about them and a translation about their trials in an extension with a hover function. 
        
        * Each trail section has a link to where the information originated and tells the user that the link is in Swedish.

        * Each trial section has a back-to-top button to take them back to the top of the witches page.

        * The trail record icon is not responsive. Will fix it with javascript when I know how to.

    - The page is responsive on all common screen sizes.
    
    - It has a footer identical to the home page's footer.

    ![Witcher page](documentation/witches-page-desktop.png)


---
+ ### Contact page

    - The contact page has a contact form:

        - All text input fields are acquired.
        - All inputs are set to be required to be filled out.
        - The submit button is animated on hover.

    - The page is responsive on all common screen sizes.

    - The submit button leads to the response page.

    - It has a footer identical to the home page's footer.
​

    ![Contact page](documentation/contact-page-desktop.png)


---
+ ### Response page

    - Response page appears after submitting the contact form.
    - It contains the thank you message.
    - It will automatically direct the user to the main page in 10 seconds.


    ![Response page](documentation/response-page-desktop.png)

---
## Technologies Used

- [Fontawesome](https://fontawesome.com/) was used for all icons.
- [Favicon](https://icons8.com/icons/set/witch) was used to add an icon in the tab.
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items symmetrically on the pages.
- [VSCode](https://code.visualstudio.com/) was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) was used for the version control of the website.
- [GitHub](https://github.com/) was used to host the code of the website.
- [Photoshop](https://www.adobe.com/products/photoshop.html) was used to resize images for the README file.


---
## Design

### Color Scheme

![Color pallet](documentation/color-pallet.png) 

- Red was used as the main color of this website because of its brightness and eye-catching to make the text easy to read and make the user more emotional. The color is associated with such opposite emotions as love and hate.

- Black is used as the background color since it is often correlated with power, elegance, sophistication, and depth.

- Rosewood color was used because of its association with strength, open-mindedness, and receptivity.

- White color was used to lighten the website by symbolizing purity and innocence. 

### Typography

![Main Font](documentation/font.png)

- Fenix Google Font was used as the main font of the website to increase the readability of the content on the pages.

- And in case of problems with Fenix sans-serif was inputted as a backup.


### Wireframes

#### Mobile devices

- [Home Page. Mobile Screen](documentation/mobile-home.png)
- [Witches Page. Mobile Screen](documentation/mobile-witches.png)
- [Contact Page. Mobile Screen](documentation/mobile-contact.png)
- [Response Page. Mobile Screen](documentation/mobile-response.png)


#### Tablets

- [Home Page. Tablet Screen](documentation/tablet-home-page.png)
- [Witches Page. Tablet Screen](documentation/tablet-witches-page.png)
- [Contact Page. Tablet Screen](documentation/tablet-contact-page.png)
- [Response Page. Tablet Screen](documentation/tablet-response-page.png)

#### Desktop

- [Home Page. Desktop Screen](documentation/desktop-home-page.png)
- [Witches Page. Desktop Screen](documentation/desktop-witches-page.png)
- [Contact Page. Desktop Screen](documentation/desktop-contact-page.png)
- [Response Page. Desktop Screen](documentation/desktop-response-page.png)


---

## Testing

## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.


    ![Home Page HTML Validator](documentation/w3_validator_home_page.png)
    
  #### Witches Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Witches Page HTML Validator](documentation/w3_validator_witches_page.png)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/w3_validator_contact_page.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3_validator_response_page.png)
    
+ ### CSS
    - No errors or warnings were found when passing through the official W3C (Jigsaw) validator

  ![CSS Validator errors](documentation/w3c_validator_css.png)

### Compatibility And Responsiveness

In order to confirm the correct functionality, responsiveness, and appearance:

+ [Responsive Website Design Tester](https://responsivedesignchecker.com/) Was used to test responsiveness

+ The website was tested on the following browsers: Chrome, Firefox, Edge

    - Chrome

    ![Chrome](documentation/compatibility-chrome.png)

    - FireFox

    ![FireFox](documentation/compatibility-firefox.png)

    - Edge

    ![Edge](documentation/compatibility-edge.png)

---

## Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Witches | Click on the "Witches" link | The user is redirected to the witches page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page, In new tab | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page, In new tab | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page, In new tab | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page, In new tab | Yes | Yes | - |
| Home page | | | | | |
| "Video" button in video section | Click on the "Video" button | The user started the video | Yes | Yes | This video is not automaticcly played for better user experience |
| Witches page | | | | | |
| "Witches" button in stor-marit section | Click on the "records" button | The user see the extention | Yes | Yes | Icon not responsive to know text is showing. Will fix when learned how in js |
| "Source" button in record-marit section | Click on the "Source" button | The user opens source in new tab | Yes | Yes | - |
| "Back to top" button in record-marit section | Click on the "Back to top" button | The user was moved back to header | Yes | Yes | - |
| "Witches" button in elisabetta section | Click on the "records" button | The user see the extention | Yes | Yes | Icon not responsive to know text is showing. Will fix when learned how in js |
| "Source" button in record-elisabetta section | Click on the "Source" button | The user opens source in new tab | Yes | Yes | - |
| "Back to top" button in record-elisabetta section | Click on the "Back to top" button | The user was moved back to header | Yes | Yes | - |
| "Witches" button in margreta section | Click on the "records" button | The user see the extention | Yes | Yes | Icon not responsive to know text is showing. Will fix when learned how in js |
| "Source" button in record-margreta section | Click on the "Source" button | The user opens source in new tab | Yes | Yes | - |
| "Back to top" button in record-margreta section | Click on the "Back to top" button | The user was moved back to header | Yes | Yes | - |
| Contact page | | | | | |
| First name input | Enter the first name | The first name is entered | Yes | Yes | If user doesn't enter the first name, the error message appears |
| Last name input | Enter the last name | The last name is entered | Yes | Yes | If user doesn't enter the last name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. |
| Enter message in textarea | Enter message | Message was entered | Yes | Yes | If user doesn't enter text, the error message appears. |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |


---

+ ## LightHouse report

    - Using lighthouse in dev tools I confirmed that the website is performing well, accessible, and the colors and fonts chosen are readable.
    
  ### Home page

  - 83 Performance due to embedded YouTube video.

  ![Home Page Lighthouse](documentation/lighthouse_home_page.png)

  ### Witches page

  ![Witches Page Lighthouse](documentation/lighthouse_witches_page.png)

  ### Contact page

  ![Contact Page Lighthouse](documentation/lighthouse_contact_page.png)

  ### Response page

  - 86 Accessibility to refreshing the page automatically.

  ![Response Page Lighthouse](documentation/lighthouse_response_page.png)

---

## Bugs
+ ### Unsolved bugs
    - None.
+ ### Mistakes
    - Mistakes were made while committing changes
        * One commit is too long
        * I used the past tense in the commit before I learned to not do that
+ ### 

+ ### 


---

## Deployment

### Deployment to GitHub Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/NiborGnu/witch-hunt), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://niborgnu.github.io/witch-hunt/)

### Local Deployment

- If you use Gitpod, you can [click here](https://github.com/NiborGnu/witch-hunt.git), which will start the Gitpod workspace for you.

---

## Future improvements

- add Javascript indicator to witches record extension
- add custom 404 page;
- add accessibility report with [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/);
- add a fully functional contact form.

---
## Credits

+ #### Content

    - Inspiration for the responsive hamburger navbar came from [Kevin Powell](https://www.youtube.com/user/KepowOb) on his YouTube channel.

+ #### Media

    - All the images for the website were taken from [Freepik](https://www.freepik.com/) and [Pixabay](https://pixabay.com/).

    + Body Background Image:
        
        - [Witch Burning](https://pixabay.com/illustrations/witch-burning-funeral-pyre-phoenix-351208/)

    + Home images:
        - [1st image](https://www.freepik.com/free-ai-image/medium-shot-scary-character-posing_59233389.htm#query=witches%20burning&position=26&from_view=search&track=ais)
        - [2nd image](https://www.freepik.com/free-ai-image/view-daunting-witch-character_58508538.htm#query=witch%20burning&position=46&from_view=keyword&track=ais);

    - [Video](https://www.youtube.com/watch?v=QnBupvZoTw8) Taken from YouTubee user Pinnso

+ #### Tools

    - [Photoshop](https://www.adobe.com/products/photoshop.html) was used to edit all images.

+ #### Inspiration

    * [Code Institute](https://codeinstitute.net/se/) - For the training and classes in all the basics of HTML and CSS
    
    * [Kevin Powell](https://www.youtube.com/@KevinPowell) - Fore awesome ccs tutorials

    * [National Archive Sweden](https://riksarkivet.se/motkallorna/rattegangsprotokollen) - For the Trail records I translated from there

    * [Pinnso](https://www.youtube.com/watch?v=QnBupvZoTw8) - For the video. I link on my home page about the Great Noise

    * [Fontawesome](https://fontawesome.com/search?q=more&o=r&m=free) - For the nice Icons I have been using that they have