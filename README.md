# **Milestone 1 - PulseGym**

## **Gym website**

---
<!--Images Here-->
I have created this webpage to showcase the skills I have learned over the first section of the Code Institute Full Stack Web Developer course; this is the first of four projects that I will be creating for the course.
For this project I have chosen to create a web page for a ficticous Gym.
The reason for this selection is that it will allow me to show my abilities to create a static webpage for a commercial entity using html, css and UX design techniques.

---

### **_Table of contents:_**

1. [Description](#gym-website)
2. [UX](#ux)
    1. [The Focus](#the-focus)
    2. [Wireframes](#wireframes)
    3. [Styling](#styling)
    4. [User Stories](#user-stories)
3. [Features](#features)
    1. [Existing Features](#existing-features)
    2. [Features Left to Implement](#features-left-to-implement)
4. [Technology Used](#technology-used)
5. [Testing](#testing)
    1. [Testing User Stories](#testing-user-stories)
    2. [Code Validation](#code-validation)
    3. [Manual Testing](manual-testing)
6. [Deployment](#deployment)
    1. [Remote Deployment](#remote-deployment)
    2. [Local Deployment](#local-deployment)
7. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
    3. [Acknowledgements](#acknowledgements)

---

## **UX**
---

### **The Focus**

The focus of this website is to showcase the highlights of the Gym, and the many activities that it has. The opening callout section aims to grab the attention of possible new members with a short and punchy about section to inform the user a little about the Gym without overloading them in detail.

This Gym has a particularly large amount of fitness classes, so they have been giving the largest section of the site. The fitness classes have been divided into three different categories so the user can hone in to the type of class they are looking for easily. All the classes have a booking button to allow the user to book a class there and then.

The website is simple to navigate and uses a single page style making navigation with a mobile particularly easy. The font colours are striking but not overwhelming making it clear and attractive to read through the website.

### **Wireframes**
<!--Wireframes here with small paragraph-->
### **styling**
#### *Framework*
Bootstrap and jQuery have both been used to form the structural layout of this website.

#### *Fonts*
Throughout the website Open Sans is used in various forms

#### *Colors*
There are four non-image colors used on the website:
    <!--colors here-->

#### *Icons*
All icons that appear on this page are sourced from [FontAwesome](https://fontawesome.com/)

### **User Stories**

* **First Time Visitor Goals**
    * *As a First Time Visitor*, I want to be able to navigate the website simply and easily.

    * *As a First Time Visitor*, I want to access the site across all devices.
    * *As a First Time Visitor*, I want to find out what classes the gym offers.
    * *As a First Time Visitor*, I want to know about the Membership fees.

* **Returning Visitor Goals**

    * *As a Returning Visitor*, I want to locate the gyms social media links to stay up to date with any new content.

    * *As a Returning Visitor*, I want to find out about any changes to fitness classes.
    * *As a Returning Visitor*, want to find out how to contact the Gym.
    * *As a Returning Visitor*, I want to find out any new Membership offers.

---

## **Features**

---

* The Project is a one-page website with five main sections and a footer.

    1. The website has a home section that has a jumbotron with an image background and callout text. Within the jumbotron is a join button which navigates to the Membership section.

    2. The second section is a short About Us section which advertises why people should join the gym, it also has a link to the footer where you can access the address and social links
    3. The third section is the largest section, the Fitness Classes section. The section is divided into three sub-sections and has cards describing each class. Each class has its own button to book a class.
    4. The next section is the Testimonials section. The testimonials are displayed on a bootstrap carousel and each testimonial has an image of the person giving the testimonial.
    5. The last main section is the Membership section. The section has two parts, a card describing the membership options and a sign up form offering membership.
    6. At the bottom is a footer. The footer has three columns. The first column holds the address, the middle column displays the company logo and The last column has social media icons.

### **Existing Features**

*	The site has been designed to be responsive across all devices

*	The page has a permanent sticky navbar which navigates to the top of each section of the page.
*	The navbar is styled differently for different screen sizes, changing from a three line “hamburger” icon on mobile to a traditional worded navbar on full-size screens
*	Each exercise class has its own individual card with a booking button to book classes
*	The classes section has three different styles depending on screen size
*	The Testimonies section uses a carousel feature to rotate through the comments. 
*	Each testimony has a picture of the customer and rotates both automatically and via user buttons.
*	The membership section displays the membership options and also has a sign up form
*	The footer displays the address, logo and social media links
*	On smaller devices the address in the footer becomes a dropdown
*	On smaller devices the footer becomes a single vertical column


### **Features Left to Implement**

* Personal Training Session options.

* A multi-functional bookings interface
* An active payment section
* An area for selling health products/gym equipment

---

## **Technologies Used**

---

All of the folloing technologies were used to create this website:-

*	Both **HTML5** and **CSS3** have been used throughout the project to create the text and style of the website

*	**JavaScript** and [Jquery]( https://jquery.com/) were used to implement the carousel function on the testimonies section and to simplify DOM manipulation
*	[GoogleFonts](https://fonts.google.com/) has been used to style the font of the text throughout the website
*	[FontAwesome](https://fontawesome.com/) was used to add icons to the exercise class headers
*	[Bootstrap]( https://getbootstrap.com/) was used for layout aesthetics, including grid styling and device responsiveness
*	[Gimp]( https://www.gimp.org/) was used to create the company logo
*	[GitHub]( https://github.com/) was used to host the website
*	[Gitpod]( https://www.gitpod.io/) was used to code the website
*	[Balsamiq]( https://balsamiq.com/) was used to create the wireframes of the project

---

## **Testing**

---

### **Testing User Stories from the UX Section**

**First Time Visitor Goals**

* *As a First Time Visitor*, I want to be able to navigate the website simply and easily.

    *	The website has a sticky navigation menu that is always available to allow quick access to each section of the site.
    *	Each section is clearly marked with a main header and all sub-sections are clearly labelled
    *	The home section has a join button which directs the customer to the membership section where they can sign up or send a question to the company
    *	Each fitness class has its own bookings button and each class is labelled with the time and day of the class
* *As a First Time Visitor*, I want to access the site across all devices.
    *	The website is responsive across all devices
    *	The website has three different layouts depending on what size screen the customer is using
* *As a First Time Visitor*, I want to find out what classes the gym offers.
    *	The fitness classes section is accessible via the sticky navbar
    *	The fitness classes section is the largest section of the site and is divided into three separate categories for clearer navigation
    *	Each class has its own card with a booking button
* *As a First Time Visitor*, I want to know about the Membership fees.
    *	The Navbar has a membership button which directs to the membership fee info
    *	The two types of membership are displayed in the membership area with their prices and the additional extras included in the membership

**Returning Visitor Goals**

* *As a Returning Visitor*, I want to locate the gyms social media links to stay up to date with any new content.

    *	The about section, just below the first section has a link to the footer which has both the address and the social links
    *	The about section is also located on the sticky navigation bar
* *As a Returning Visitor*, I want to find out about any changes to fitness classes.
    *	All classes are listed on the fitness classes section which can be located using the navigation bar
    *	The social media links can be accessed via the footer, these will also provide any information about classes and schedules
* *As a Returning Visitor*, want to find out how to contact the Gym.
    *	The footer contains the address, phone number and email address to the gym
    *	The footer also has the social media links for Facebook, Instagram and Twitter. All of which can be used to contact the gym
    *	The About section contains a link to the footer
* *As a Returning Visitor*, I want to find out any new Membership offers.
    *	The membership section has a link on the navbar
    *	The membership area shows a card with prices and offers
    *	All of the social media links are on the footer, these can also be accessed to see any offers currently available

### **Code Validation**

#### *W3 Validators*
*    The HTML was Validted at [W3C Markup Validation Service](https://validator.w3.org/). 
<!--![HTML-Code-Validation]( screen shot ) -->

   *    The CSS was validate at [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/). 
<!--![CSS-Code-Validation]( screen shot ) -->

### **Manual Testing**

#### *Google Developer Tools*

   *    The websites design responsiveness has been tested on all device sizes using Google Developer Tools.  
 
#### *Testing On Different Browsers*
   *    Google Chrome
   *    Firefox
   *    Maybe a browers site
    
#### *Testing Responsiveness On Different Devices*
   *    Acer Aspire E 17
   *    Samsung S10
   *    Samsung S8
   *    Samsung S6
   *    iPhone 11
    
#### *Issues Found*

*   I had a non-website issue during this poject. This is the second repository of this project as I have been frozen out of the original repository by a GitHub bug.
    *   The issue was only solved by transfering all possible data to a second repository.

*   An issue was found with the carousel on mobile devices, The resizing would make the right hand button drop below the rest of the carousel.
    *   The issue was resolved with some changes to button and text sizes

*   The address text in the footer would show flex to too many lines on smaller devices
    *   The issue was fix with a design change rather than a bug fix, the address now moves to a dropdown list on smaller devices

---

## **Deployment**

---

### **Remote Deployment**
1. Navigate to the GitHub [Repository:]( <!--GitHub address--> )
2. Click the **Settings** Tab.
3. Scroll Down to the **Git Hub Pages** Heading.
4. Select **Master Branch** as the source.
5. Click the **Save button**.
6. Click on the link to go to the live deployed page.

### **Local Deployment**
1. Navigate to the GitHub [Repository:]( <!--GitHub address--> )
2. Click the **Code** drop down menu.
3. Download the ZIP file and unpackage locally
4. Open a code editor of your choice and open the unziped file using the code editor.
5. Click **Save** and save to your local device

---

## **Credits**

---

### **Content**
*	Layout styling was inspired by the Whiskey Drop tutorial at [Code Institute](https://codeinstitute.net/) 
*	Text for the exercise section was inspired by [Puregym](https://www.puregym.com/classes/categories/) 


### **Media**

* The photos used in this site were obtained from [Pixabay](https://pixabay.com/) 
    * With special mention to:
        * [Steve Buissinne](https://pixabay.com/users/stevepb-282134/Steve_Buissinne) 
        * [Joanna Dubaj](https://pixabay.com/users/dubajjo-2559514/) 
        * [Pavel Jurča](https://pixabay.com/users/pavel-jurca-3841851/) 
        * [Shushipu](https://pixabay.com/users/shushipu-4316831/) 
        * [wikiimages](https://pixabay.com/users/wikiimages-1897/?tab=popular) 
        * [tumisu](https://pixabay.com/users/tumisu-148124/?tab=popular) 
        * [robinhiggins](https://pixabay.com/users/robinhiggins-1321953/?tab=popular) 
        * [juanital57](https://pixabay.com/users/juanital57-475513/?tab=popular) 
        * [Arcaion](https://pixabay.com/users/arcaion-2057886/?tab=popular) 
        * [janoazs](https://pixabay.com/users/janoazs-1338906/?tab=popular)  

*	The Kim K photo used for the testimonials was obtained from [Glenn Francis](https://www.facebook.com/GlennFrancis.Photographer/#!/profile.php?id=502908168) 

*   The original illustration used to create the company logo used on this site was obtained from 
    [Gerd Altmann](https://pixabay.com/users/geralt-9301/?tab=popular) at [Pixabay](https://pixabay.com/)


### **Acknowledgements**

*	I received design inspiration from:

    * **Matt Rudge** at [Code Institute](https://courses.codeinstitute.net/login) 
    * [Cololib](https://colorlib.com/wp/gym-websites-design/)
    * [Puregym]( https://www.puregym.com/) 

*	I received styling inspiration from:

    *   [CSS-Tricks.com](https://css-tricks.com) 
    *	**“Zim”** from [StackOverflow]( https://stackoverflow.com/questions/62572072/bootstrap-4-carousel-text-left-image-right) 
