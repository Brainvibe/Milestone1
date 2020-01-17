# Mary's Sweets

<img width="1000" height="400" src="https://github.com/Brainvibe/Milestone1/blob/master/assets/images/page_preview.png">

This project aims to be a online presence to a new bakery business. Client wanted a minimalistic but effective website, providing key information about their business.

## UX

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
User stories:

    As a user type, I want to perform an action, so that I can achieve a goal.


## Wireframes
<p align="center">
Desktop
</p>

![Desktop](https://github.com/Brainvibe/Milestone1/blob/master/wireframes/Desktop.png)

<p align="center">
Mobile
</p>


![Mobile](https://github.com/Brainvibe/Milestone1/blob/master/wireframes/Mobile.png)

<p align="center">
Tablet
</p>


![Tablet](https://github.com/Brainvibe/Milestone1/blob/master/wireframes/Tablet.png)


**Features**


    Home - Allows users to undestand the mission of the business.
    
    About us - Users can learn here a more detailed information about the business, who they are, their mission, 
    and what they do. 

    Our Sweets - It showcases all Bakery products, so the user knows what's available to them. 

    Contact us - Allows the user to contact the business to order cakes or to ask any other 
    information they want to. 




**Features to add**

    Online store - Instead of using the contact form to order the cakes, a full e-commerce 
    solution would be ideal. For the business and the customer. 
    
    Different payment methods - In order to reach to a wider range of customers. 
    
    Social feed - Real time updates, from business social accounts 
    
    


**Technologies Used**

+ **Visual Studio Code** - IDE used for this project. [Visual Studio Code Website](https://code.visualstudio.com/)
+ **Live server** - VsCode extension developed by Ritwick Dey, it launches a local development server with live reload feature for static & dynamic pages. [Live Server by Ritwick Dey](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
(https://getbootstrap.com/)
+ **HTML 5** - Used to create the main structure of the website.
+ **CSS** - Used to style and layout the website.
+ **Bootstrap** - Framework used [Bootstrap](https://getbootstrap.com/)
+ **jQuery** - In order for Collapse to work with the Navbar [jQuery](https://jquery.com/)
+ **Fontawesome** - All footer icons are from Font Awesome. [Font Awesome](https://fontawesome.com/)
+ **Popper.js** - Used for Navbar [Popper.js](https://popper.js.org/)
+ **Git** - Version control used. [Git](https://git-scm.com/)
+ **GitHub** - Hosted repository. [Github](https://github.com/)
+ **GitHub Pages** - Used to host the live website. [Github Pages](https://pages.github.com/)
+ **tinypng** - Use to compress all images in this project - [tinypng](https://tinypng.com/)
+ **Google Fonts** - Pacifico and PT Sans Narrow fonts - [Google Fonts](https://fonts.google.com/)
+ **Balsamiq** - Wireframing software - [Balsamiq](https://balsamiq.com/) 

**Testing**

+ W3C Validation services
    Markup Validation Service - It detected some minor errors that were easily fixed. 

Before I started the more in depth testing, I ensured that the website served the purpose it was built for by running through each of the user stories myself and checking all requirements were met.

- I checked all navigation, href and anchor links were working and pointed to the correct destinations. - *Working*

- All images were correctly sized across the site and displayed correctly in the photo carousels. - *Working*


- I tested the responsiveness of the website across every different phone size within Google Developer Tools. - *Working*

- I ran Audit tests within Google Developer Tools on both Mobile and Desktop to check that everything was hitting the highest scores possible. - Each section was 90-100%.
    - Doing this outlined the fact I needed to compress many of my images to allow for maximum speed performance. I successfully compressed every image to the threshold before it impacted on visible quality.

    **Please note the 'Best Practices' score is reduced on each page due to me deliberately placing low contrast text at the bottom of the page**

    ![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/readme-images/1.JPG?raw=true)

    ![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/readme-images/2.JPG?raw=true)

    ![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/readme-images/3.JPG?raw=true)

    ![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/readme-images/4.JPG?raw=true)

- I used the [W3C HTML Markup Validator](https://validator.w3.org/) to check all HTML was applied and working correctly. - *Working*

- I used the [W3C CSS Validator](http://www.css-validator.org/) to check all the CSS was also valid and working correctly. - *Working*

- I tested the website on my Iphone 5s and my Macbook Pro. - *Working*



- I posted my webpage into the Slack 'Peer Review' channel for feedback from other students. 

- I ran my website through [GTmetrix](https://gtmetrix.com) and it presented me with speed issues I had not been given on Google Developer Tools. It outlined that some of the images had been resized within the IDE so their native pixel ratio was still far too large, and I could save space by resizing these on top of the compression I had already applied. 
    ![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/readme-images/gmetrix-1.JPG?raw=true)




In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

    Contact form:
        Go to the "Contact Us" page
        Try to submit the empty form and verify that an error message about the required fields appears
        Try to submit the form with an invalid email address and verify that a relevant error message appears
        Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.
Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

    Different values for environment variables (Heroku Config Vars)?
    Different configuration files?
    Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.
Credits

Content

    The text for section Y was copied from the Wikipedia article Z

## Media

The photos used in this project are all free to use, obtained from [Pexels](https://www.pexels.com/). License information can be found [Here](https://www.pexels.com/photo-license/). 

**Acknowledgements**

    Auto-hide collapse menu code from [here](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click).
    Smooth Scrolling from [W3schools] (https://www.w3schools.com/howto/howto_css_smooth_scroll.asp).
    Opaque overlay from Whiskey Drop Code institute mini project.