![Cheap Chopping Chops logo](assets/images/logo.png)


# Goal For This Project 

Welcome to “Cheap Chopping Chops”. This barber is the cheapest barbers in Dublin offering all styles from skin fades to quick trims. 

This site gives examples of the hair styles our barbers spealise in, the shockingly cheap price of these haircuts and the several locations we operate from. It allows potential customer to make booking enquiries in each of our stores via the contact form.

# Table of Contens 

* [UX](#ux "UX")
    * [User Goals](#user-goals "User Goals")
    * [User Stories](#user-stories "User Stories")
    * [Site Owner Goals](#site-owner-goals "Site Owner Goals")
* [Requirements-and-Expectations](#requirements-and-expectations "Requirements and Expectations)
    * [Requirements](#requirements-and-expectations "Requirements")
    * [Expectations](#expectations "Expectations")
* [Design-Choices](#design-choices "Design Choices")
    * [Inspiration](#inspiration "Inspiration")
    * [Fonts](#fonts "Fonts")
    * [Images](#images "Images")
    * [Icons](#Icons "Icons")
    * [Colours](#colours "Colors")
    * [Structure](#structure "Structure")
* [Wireframes](#wireframes "Wireframes")
* [Features](#features "Features")
    * [Existing-Features](#existing-features "Existing Feautres")
        * [Navigation-Bar](#navigation-bar "Navigation Bar")
        * [Landing-page](#landing-page "Landing Page")
        * [Book-Now-Section](#book-now-section "Book Now Section")
        * [Location-Section](#location-section "Location Section")
        * [Booking-Form-Section](#booking-form-section "Booking Form Section")
        * [Gallery-Section](#gallery-section "Gallery Section")
        * [Footer](#footer-section "footer section")
    * [Features-To-Be-Implemented](#features-to-be-implemented "Features to be Implemented")
* [Technologies](#technologies "Technologies")
    * [Languages](#languages "Languages")
    * [Libraries-&-Frameworks](#libraries "Libraries & Frameworks")


# UX

## User Goals 

* Form to make booking enquiries in a specific store
* Visually appealing examples that customers can use to select the style they want when making a booking 
* Easy and intuitive navigation on all screen sizes 
* Form to join the membership to receive deals

## User Stories 

* As a visitor, I want to understand the purpose of the website, which is that the barbers offers very cheap chops 
* As a visitor, I want to understand the main services on offer, including their cost
* As a visitor, I want to see examples of the styles I can request
* As a visitor, I want to easily find the different locations 
* As a visitor, I want to intuitively navigate through the content 
* As a first-time visitor, I want to join the newsletter so that I can avail of offers 
* As a visitor, I want to make enquires to book a service in a specific store 

## Site Owner Goals 

* Highlight the cheap prices 
* Increase the number signups to the newsletter
* Promote the different stores 
* Increase the search ranking on search engines

# Requirements and Expectations 

## Requirments 

* Easy to navigate on different screen sizes
* Clear information on the price of services
* Good quality images of the hair styles that are available 
* Encourage booking enquiries  
* Visuals of shop locations 
* Enquiry form that allows users to select options such as the store location, the barber, and the style 

## Expectations 

* I expect to know that my booking enquiry was submitted successfully 
* I expect that links to all of the social media open in a new tab
* I expect all content to be accurate and without grammar mistakes
* I expect to receive a discount code for joining the waitlist 
* I expect the site to be responsive and for the quality not to be impacted by the different screen sizes 
* I expect to be able to navigate to all of the pages via the navigation bar i.e., links work correctly 

# Design Choices 

## Inspiration 
 
1.  https://samsbarbers.com/ 
* The fixed nav bar will be used to allow users to access pages at any point of the site, but the background colour will be solid and not transparent so the text is always visible 
* The social media icons will be included in header 

2. https://www.area9.ie/
* The sections on the page store will be similar to the sections used to provide examples of the different styles 
* Fixed nav bar with solid background colour so text is always visible 

3. https://www.waldorfbarbers.shop/
* Parallax on the hero image will be used as seen on this site 
* The colour scheme will be like this site 

## Fonts

I have used google fonts to select a font type that best supports the goals of the website, to provide users with cheap haircuts. For the main text I have selected [Comfortaa](https://fonts.google.com/specimen/Comfortaa "Comfortaa") because the rounded edges portray a less serious, more fun, and approachable brand compared to a font with sharper edges such as [Cinzel](https://fonts.google.com/specimen/Cinzel "Cinzel"). To make the headers and the navigation bar stand out form the text, I decided to use [Valera Round](https://fonts.google.com/specimen/Varela+Round "Valera Round").

## Images

It is important that the large background image used in the hero section portrays a happy customer to align with the fun, vibrant and approachable brand. 

Again, a less serious image portrays a more approach, less premium brand and with those lower costs. 

## Icons

The font awesome library will be used throughout the site for social media links, to provide visual aides for section headers, contact links, navigation links, and more. All icons will be consistent with the fun, approachable design of the brand. 

## Colours 

The inspiration for the colours was taken from the red, white, and blue of a traditional barber’s bar. I used the website colourmind to aid me with the selection of the specific colour scheme. I tested the colours I originally selected on the WebAIM contract checker, and it failed the test, this can be seen here. To improve the contrast ratio, I adjusted the colours manually until the test past, the final colours which passed the test can be seen here. 

* FFFFFF - Background colour and font colour for inverted styles                          
* 708FFB - Used for content with an inverted colour scheme i.e form, steps to book etc.
* DA1818 - Used for buttons and to highlight active links
* 1295DC - Not used
* 3071F7 - Not used  

![Cheap Chopping Chops logo](assets/images/readme/color-scheme.png)

## Structure

I will be building my website with a mobile first mindset using the iPhone 5/SE (320px) as the smallest screen size for styling to look good on. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap breakpoints").

| Screen Size | Breakpoint |
| ----------- | ---------- |
| x-small     | <576px     |
| small       | => 576px   |
| medium      | => 768px   |
| large       | => 992px   |
| x-large     | => 1200px  |

# Wireframes 

I have used [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") to develop my wireframes for my website. I initially created the desktop version of the wireframes and then scalled it up down for both tablet and mobile versions. 

Because it is both a requirement and a site owner goal  to encourage booking enquires I have added two CTAs in the intial sections of the site. Furthermore, because this is a one-page website the user is forced to scroll through all of the site content before they reach the booking form at the bottom of the page. Therfore, they are more likely to make a booking after consuming all of the information on the site.  

The wireframes are below:

### [Desktop Wireframe](assets/css/wireframes/Desktop.pdf "Desktop wireframe")
### [Tablet Wireframe](assets/css/wireframes/Tablet.pdf "Tablet wireframe")
### [Phone Wireframe](assets/css/wireframes/Phone.pdf "Phone wireframe")

# Features 

## Existing Features 

### Navigation Bar 

The navigation bar includes a logo which will have an embedded link to the home page, and a menu for users to navigate throughout the site. 
The navigation bar will be fixed so it is always visible on screen. The navigation bar will be fully responsive on different screen sizes. 

Large Screens and up

* Full width of the screen with the menu items aligned to the right of the screen (Home, Price, Gallery, Locations and Book Now)
* A line will be visible on hover so that it is clear to the user which link they are going to click 
* To help the user identify which page they are currently on the text for that page will change colour 

![Nav bar large screens and up](assets/images/readme/navigation-bar/nav-bar-large-screens.png)

Small to Medium

* A hamburger menu will replace the listed menu items on smaller screens to optimize screen space 
* The menu items will be visible after the hamburger menus is expanded by a user clicking it 
* Both the logo and the brand name will also be visible at these screen sizes

![Nav bar small to medium screens](assets/images/readme/navigation-bar/nav-bar-medium-%26-small-screens.png)

Extra Small 

* Only the logo and the hamburger menu will be visible at this screen size 

![Nav bar extra small screens](assets/images/readme/navigation-bar/nav-bar-extra-smalls-screens.png)

### Hamburger Menu


### Book Now Button

* The book now button was styled so that it appears as if it illuminiscent or glowing. For large screens and up when a user hovers over the button it expands in size and a shadow effect before the button is applied. These features are applied by default on screens that are medium and below.

Button without hover effect on large and above screen sizes:

![Button without hover effect](assets/images/readme/button/button-without-hoever-large-plus.png)

Button with hover effect on large and above screen:

![Button with hover effect](assets/images/readme/button/button-with-hover-large-plus.png)

Default button on medium and below screen sizes:

![Default button](assets/images/readme/button/button-default-medium-and-below.png)


### Hero Image 

* The main image on the landing page will portray the main concepts of the website. The image will be coloured and show a smiling customer who has recently had their hair cut. The image is clearly displaying a customer happy with the service and it is also immediately clear to a visitor what the purpose of the website is. 

![hero-image](assets/images/readme/hero-image-readme.png)

### Gallery tiles 

* The gallery section includes rectangular tyles with images that display example hair cuts that were submitted by customers
* The tiles are include two sections:
    * An image of the customers haircut
    * A description of the style 

![gallery-tile](assets/images/readme/gallery-tile.png)


### Location information 

The location section consists of information on the three stores overlaying an image. The sections provide an address, opening days and times for each store 

Large Screens and up

* The locations are listed as individual rectangular sections horizontally across the width of the screen 

![locations-large-plus](assets/images/readme/locations/locations-large-plus.png)

Mediun screens and below 

* The locations are listed as individual rectangular sections vertically

![locations-medium-below](assets/images/readme/locations/locations-medium-below.png)

### Booking Form  

* The form on this page includes radio buttons so that users can either make a general query or a booking enquiry for a specific store 
* The fields are all required fields and the email field requires the user to enter a value that follows a valid email format
* There is also a map with a pin for each of the four stores 
* A confirmation page is displayed after the user submits the form successfully 

### Footer Section 

* The footer contains icons which are clickable links for social media platforms 
* There is also a page list so users can access the various pages from the footer 

## Features to be implemented 

### Hamburger menu exit button

### Embeded google map with multiple pins 

### Hamburger menu exit button

### Online booking system 

# Technologies 

## Languages 

## Libraries 
