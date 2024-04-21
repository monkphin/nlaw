# **N/L/A/W - Newton Local Area Wargamers**

A website created for the first milestone project for Code Institutes full stack developer course. 

[The deployed website can be found here.](https://monkphin.github.io/nlaw/)

<img src="docs/mockup.png">

# Contents

* [User Experience](#user-experience)
    * [The Clubs Goals](#hobby-club-goals)
    * [A Visitors Goals](#visitor-goals)

* [Design](#design)
    * [Wireframes](#wireframes)
    * [Colour Palette](#colour-palette)
    * [Typography](#typography)
    * [Images](#images)
    * [Icons](#icons)

* [Features](#features)
    * [Header](#header)
    * [Footer](#footer)
    * [Modal](#modal)
    * [Home Page](#home-page)
    * [Club Page](#club-page)
    * [Contact Page](#contact-page)
    * [Response Page](#response-page)
    * [404 Page](#404-page)
    * [Sticky Nav](#sticky-nav)
    * [Carousel](#carousel)
    * [Future Features](#future-features)

* [Bugs and Issues](#bugs-and-issues)
    * [Index Page](#index-page)

* [Technology](#technology)
    * [Languages](#languages)
    * [Frameworks and Programs](#frameworks-and-programs)

* [Testing](#testing-and-validation)
    * [HTML Validation](#html-validation)
    * [CSS Validation](#css-validation)
    * [Accessibility](#accessibility)
    * [User Testing](#user-testing)
    * [Performance](#performance)
    * [Responsiveness](#responsiveness)

* [User Stories](#user-stories)

* [Deployment](#deployment)

* [Credits](#credits)

# User Experience

N/L/A/W is a local tabletop wargames group that started life as a small afterschool club in a local autism college. 

The club would like to have a presence online outside of standard social media to allow other hobbyists and wargame enthusiasts to find out more about the club and what they do, as such they opted to commission someone to develop a website to allow them to do this. 


## Hobby Club Goals: 

* To inform other hobbyists in the Newton-le-Willows area that there is a club space available for like minded hobbyists so that we grow our membership. 
* Provide essential information on the club such as meeting times and location.
* To show images of the club to potential guests and members
* Ideally sign post some of the games that we commonly play
* The website should have a simple and easy to navigate structure that reacts to the type of device it's being viewed.
* Visitors should be able to contact the club to be able to enquire about joining us, as well as ask any questions they may have before first visiting. 
* For social channels to be signposted 
* To be designed in a way that's sympathetic to our user base's accessibility requirements. 

## Visitor Goals: 

* To find some information about the club such as what games are commonly played. 
* To know when and where the club meet
* To be able to see pictures of the club so that I know what to expect when I visit. 
* To know what the club offers, such as available gaming spaces, places to hobby and to know what facilities are onsite. 
* To be able to contact the club to ask any questions I may have before visiting 
* To be able to easily navigate the site irrespective of device


# Design 

The design process needed to factor in the club's history, since many of its members are autistic, thanks to its roots in a local autism college. 

The following sites were used to help research requirements for autism friendly design elements: 

* [Horlix - Making your autism friendly website](https://www.horlix.com/making-your-autism-friendly-website) 
* [Overlay Facts - Digital Accessibility for Autism](https://overlayfacts.org/blog/digital-accessibility-web-design-for-autism)
* [UX Design - Designing for Autistic People](https://uxdesign.cc/designing-for-autistic-people-overview-of-existing-research-d6f6dc20710e)

Due to this, several iterations of the site were wireframed before a look was settled on with attempts to work to the UK Department of Health guidelines for ASM friendly design as outlined [here](https://file.scirp.org/pdf/JSEA_2014022510055814.pdf)

While the final design breaks some of the Department of Health recommendations, steps have been taken to assist where potential for confusion may occur such as the inclusion of bounding boxes. Examples of this method were observed from several other websites that have been lauded for ASM focused design. 

* [Autism Advocacy](https://autisticadvocacy.org) 
* [Sesame Street](https://sesameworkshop.org/topics/autism) 

Overall I feel this finds a balance between a clean design and an autism friendly one. 

## Wireframes: 

Wireframes were created with Balsamiq software to provide rough mockups for layout. 

<details>
<summary>Wireframes</summary>



<details>
<summary>Desktop</summary>

<details>
<summary>Homepage Desktop</summary>
<img src="docs/index-desktop.png">
</details>

<details>
<summary>Club Desktop</summary>
<img src="docs/club-desktop.png">
</details>

<details>
<summary>Contact Desktop</summary>
<img src="docs/contact-desktop.png">
</details>

<details>
<summary>Response Desktop</summary>
<img src="docs/response-desktop.png">
</details>

<details>
<summary>404 Desktop</summary>
<img src="docs/404-desktop.png">
</details>
</details>

<details>
<summary>Mobile</summary>

<details>
<summary>Homepage Mobile</summary>
<img src="docs/index-mobile.png">
</details>

<details>
<summary>Club Mobile</summary>
<img src="docs/club-mobile.png">
</details>

<details>
<summary>Contact Mobile</summary>
<img src="docs/contact-mobile.png">
</details>

<details>
<summary>Response Mobile</summary>
<img src="docs/response-mobile.png">
</details>

<details>
<summary>404 Mobile</summary>
<img src="docs/404-mobile.png">
</details>

</details>
</details>

## Colour Palette. 

The colours were selected to be sympathetic to the user base, using [Paper Heart Designs peaceful pallettes](https://paperheartdesign.com/blog/color-palette-peaceful-palettes) to help pick out soothing and low contrast colour palettes that could work for some of the user base. Of those presented, I feel the 'Blueberry Bliss' selection gives a reasonable range of tones and colour options. 

<img src="docs/blueberries.jpg">

## Typography. 

As with the other design elements, some care was needed around font usage, specifically using sans-serif fonts. 
To this end, after browsing fontpair and google fonts I finally settled on Inter and Barlow, both of which fit guidelines of being clear and sans-serif while looking good. Inter is used for the header and footer, with Barlow being used for the main content. 

<img src="docs/fonts.png">

Future features that would allow for better levels of support include the ability to pick and choose fonts, font background and  colour options, font size and other similar customisation options. 

## Images

Images were sourced primarily from Games Workshop's website, as well as other hobby club pages, credits for these will be provided at the end of the readme. 

## Icons

Icons were provided by [FontAwesome](https://fontawsome.com)

# Features
The website consists of 4 pages, a **home page**, a **club page**, a **contact page** and a **response page** which loads when the contact form is successfully submitted. The footer of each page also includes a modal, allowing information about the location of the club and its opening times to be available anywhere on the site. Their is also a **custom 404** in case a visitor finds themselves trying to access a nonexistent part of the website, allowing them to head back to the main content. 


## Header
The header allows for simple, responsive navigation so that visitors can utilise its function regardless of the device in use. On larger screens it will expand to take the full space of the browser, while on mobile or narrow screens the menu will collapse down into a hamburger toggle and the additional subheading will vanish to ensure the menu remains uncluttered. 

The menu items show an underline and change to #0b385f to show the current page. They and all other text based links also change colour to #3373b0 on hover to provide feedback . 

<img src="docs/full-nav.png">
<img src="docs/mobile-nav.png">
<img src="docs/hamburger.png">
<img src="docs/desktop-menu.gif">
<img src="docs/mobile-menu.gif">

## Footer
The footer provides constant access to key information concerning the location and operating hours of the club. This modal responds to changes in screen size with both the opening hours and contact information shifting from horizontal to vertical layout as the amount of visible space decreases. The footer also contains links to various social media platforms where the club has some presence, allowing site visitors to interact with the club through other methods and see any other pictures of the venue and any hobby activities that may not be present on the website. 

<img src="docs/full-footer.png">
<img src="docs/mobile-footer.png">

## Modal 
The modal as previously mentioned provides a quick and easy way to find the club's address and opening hours. The base template for this was taken from an example provided by bootstrap and features some of my own minor amendments to styling and CSS to make it fit the site more closely. There is also a clickable phone number, which will open your device's default phone system and auto fill the number allowing a user to call the club with minimal effort. 

<img src="docs/full-modal.png">
<img src="docs/mobile-modal.png">

## Sticky Nav
Since the site can get potentially quite long on smaller screen sizes the navbar is configured to remain in view at all times, allowing the user to easily move from page to page if they want to read information on a different page, or perhaps have a question they want to ask of the club while it's in mind. 

<img src="docs/sticky-menu.gif">

## Carousel
Due to the index page becoming overly long when showing the list of games the group enjoys, the design was tweaked slightly to shift this list to the bottom of the main content and replace it with a carousel. The carousel was sourced from Bootstrap with some customisation being done to ensure it fit the site's designs, this meant using some fonts from FontAwesome to replace the left and right arrows since the default icons were proving difficult to format correctly. Grow from Hover.css is also used so that the images will zoom slightly on mouse over to show some interaction to the user when moving to tap/click on the image. 

<img src="docs/carousel.gif">

## Home Page
The site's homepage provides some of the clubs history, as well as information about the wider tabletop gaming hobby and some of the possible benefits it can bring to those partaking in it. This page also features a list of game systems the club members enjoy the most to allow visitors to understand what games they may expect to be able to easily play if they visited in person. Early testing of the site showed some issues with how this was positioned when using mobiles and other smaller screened devices, where the main content was pushed quite far down the page. To resolve this Bootstrap ordering was used to move the games list to the bottom of the page on smaller screens. However this also proved less than ideal since it just created an overly long vertical scroll. To mitigate this, the list is hidden on smaller screens and replaced by a carousel.

The page as a whole uses bootstraps grid positioning to allow for positioning and responsive design, with stacked rows to allow for a column containing the list of games to be rendered on the left when on a desktop with the hero image to the right in another column directly above the three columns providing the clubs background, information on tabletop gaming and some information about the club and its members. These will re-order depending on the size of the device, with the hero image showing the main room of the club always remaining at the top of the page. 

<img src="docs/indexpage-desktop.png">
<img src="docs/indexpage-mobile.png"><img src="docs/indexpage-bottom-mobile.png">

Finally, much like on the carousel the images will expand slightly thanks to Hover.css's grow function, to show the user that the image they're interacting with when mousing over it. 

<img src="docs/hover.gif">

## Club page
This page provides more specific information on the club itself, concerning its gaming facilities and what food and drink options are available and some basic information regarding costs to access, again the hero image, showing the main room of the club is carried over. This page also features a list of club rules and also the address and phone number for the club, and its opening hours and a google map to aid people in visiting. Much like the home page this uses bootstraps grid positioning system with various columns and rows and some nesting of these to help ensure a clean and responsive layout irrespective of the device that the site is accessed from. Much like with the modal, the opening times shifts between horizontal and modal depending on the device screen size that the site is accessed from. LIke in the modal, the phone number is clickable and will open the users default calling application with the number pre-populated. 

<img src="docs/clubpage-top-desktop.png">
<img src="docs/clubpage-bottom-desktop.png">

<img src="docs/clubpage-top-mobile.png"><img src="docs/clubpage-bottom-mobile.png">

## Contact Page
The contact page is a simple form asking for name, email and a message. This has an action to call response.html, so it doesn't just error out and instead provides feedback to the user that an email has been sent. With further development this would send an email to the clubs email on submission. 

All fields will highlight as they're clicked into to show the user which field they're working on and all fields require data to submitthe form. The form is configured to be aware of if the email field has been filled in with normal text, rather than an email. 

<img src="docs/contactpage-desktop.png">
<img src="docs/contactpage-mobile.png">

## Response Page
This page exists purely to provide feedback on submitting the form, rather than just erroring out. 

<img src="docs/responsepage-desktop.png">
<img src="docs/responsepage-mobile.png">

## 404 Page
A custom 404 error page was added, to keep the user on site in the event of them somehow trying to load a none existing page. This is built using the stock layout to allow users to easily navigate to any part of the site, rather than just leaving them with no route back or simply sending them back to the home page. 

<img src="docs/404page-desktop.png">
<img src="docs/404page-mobile.png">

## Future features
As mentioned earlier in the document, it would be ideal to allow for a degree of personal customisation at the user level to allow for further improvements to accessibility. Adding a calendar that the club can update would also be a useful feature so they could show events that they may have coming up that may be of interest to visitors, this could potentially tie into a mailing list, which would require a database to store user details. Additionally a gallery page could also be of use to show more pictures of the venue or projects the club are working on without visitors having to leave the site and visit the clubs social pages. 
<br><br>
Since I am using an older version of Bootstrap I have already created a development branch with the intention to migrate this over to Bootstrap 5, this will also give me a chance to refactor the HTML and CSS a little, since simply porting over to Bootstrap 5 presented a lot of rendering issues which need to be resolved.  

# Bugs and issues. 

## Index Page
index.html has some issues with its three content boxes, where they don't auto size to match each other's vertical lengths; this is due to having to place them within divs to allow for margins to function without causing the content to overflow to a new row. As a work around, all three text boxes have roughly similar amounts of text so that they're mostly the same height, depending on the screen width. 
<br><br>
 The content boxes are also slightly wider than expected when on mobile, resulting in them filling the horizontal space, rather than having some breathing room around the edges. These issues are being investigated but may not be resolved by the time the project needs to be handed in. 

index.html has some minor positioning issues that don't directly impact site functionality for the hero text on the hero image. On some smaller screens it is not aligned in a way that looks neat or inline with the rest of the site layout. This should be an easy fix with media queries, but I suspect there may be a more elegant way to do this. 

## Site Wide
Their are some off overflow issues on mobile views, which have required me to hide overflows in the CSS on the footer of all pages featuring the main site template and the main content of the index page. I suspect this is due to how I'm nesting bootstrap containers, which may be resolved when moving to Bootstrap 5.  

To be fixed. 
index.html - the carousel misrenders on screen widths of 913 to 991 pixels, causing it to overlap over the footer. This can easily be fixed via an additional CSS media query. 



# Technology. 

## Languages
The site was built with HTML and CSS, any javascript in use is provided via Bootstrap, which was needed for the carousel and nav toggle. 

## Frameworks and Programs. 
* Bootstrap 4.2.1
    * Used for layout and positioning, and the navbar, modal and carousel. 

* W3Schools
    * Used for help with CSS. 

* HoverCSS
    * Used to provide 2D transitions on the games images. 

* Git
    * Used for version control, storage and deployment. 

* GoogleFonts
    * Used to import fonts to the stylesheet. 

* VSCode
    * IDE of choice. 

* Balsamiq
    * Wireframing program. 

* WAVE
    * Used to assist with accessibility checks. 

* Techsini 
    * Mockup generator.

* Fireshot
    * Chrome PLugin for screenshots. 

* Google Dev Tools
    * Used to help with troubleshooting.

* Pixelmator
    * Users for editing and resizing images.

* TinyPNG
    * used for image compression. 

 * Favicon.io
    * Used to generate a Favicon.

* Quicktime
    * Used to record footage of parts of the website for documentation 

* Convertio
    * Used to convert .mov files to .gif files for the readme.md file. 

# Testing and Validation
## HTML Validation
[W3Schools HTML Validator](https://validator.w3.org/)
All pages passed with 0 errors. 

<details>
<summary>Homepage</summary>
<img src="docs/home-validate.png">
</details>

<details>
<summary>Club Page</summary>
<img src="docs/club-validate.png">
</details>

<details>
<summary>Contact Page</summary>
<img src="docs/contact-validate.png">
</details>

<details>
<summary>Response Page</summary>
<img src="docs/response-validate.png">
</details>

<details>
<summary>404 Page</summary>
<img src="docs/404-validate.png">
</details>

## CSS Validation
[W3Schools CSS Validator](https://jigsaw.w3.org/css-validator/)
Some errors were detected with the CSS when testing against the URL. However these were all with external sheets provided by Hover.css or bootstrap due tot hem using vendor specific extensions. The websites CSS file passed with 0 errors. However a warning was presented due to the imported stylesheet for the fonts not being checked by the service. 

<details>
<summary>Full site CSS</summary>
<img src="docs/full-css-validate.png">
</details>

<details>
<summary>CSS File</summary>
<img src="docs/file-css-validate.png">
</details>

<details>
<summary>CSS File Warning</summary>
<img src="docs/file-css-warning.png">
</details>


## Accessibility
[WAVE](https://wave.webaim.org) was used to check to ensure the site conforms to accessibility standards. Several pages show redundant links - specifically contact.html, and response.html due to both the site logo and the home link in the nav bar both linking to the index page. Additionally club.html shows two redundant links, one due to the aforementioned duplication on the navbar and also due to the telephone number link in the contact modal being a duplicate of the link on the contact section. Other than this, no issues are reported. 

<details>
<summary>Homepage</summary>
<img src="docs/wave-home.png">
</details>

<details>
<summary>Club Page</summary>
<img src="docs/wave-home.png">
<img src="docs/wave-redundant.png"><img src="docs/wave-club-redundant.png">
</details>

<details>
<summary>Contact Page</summary>
<img src="docs/wave-home.png"><img src="docs/wave-redundant.png">
</details>

<details>
<summary>Response Page</summary>
<img src="docs/wave-home.png"><img src="docs/wave-redundant.png">
</details>

<details>
<summary>404 Page</summary>
<img src="docs/wave-home.png">
</details>

## User Testing. 
Since the site is designed with ASM users in mind, I reached out to several friends who I know are diagnosed with ASM who provided feedback and suggestions. 
Comments included that the colour choice was calming and easy on the eye and that the site was easy to use, read and navigate with minimal issues. 

## Performance
Overall loading times and performance were tested using Google’s lighthouse tool within Chrome's Developer Tools. 


## Responsiveness

# User Stories. 


# Deployment. 



# Credits
Images were sourced from a few locations, the details of which are below. No creator credits were able to be located when checking these websites. 

* Hero Image - [Wargames Reading](https://wargamesreading.co.uk/)

* Main body section images on index.html - [Warhammer](http://warhammer.com)

* Games logos on index.html - 
    * Warhammer 40,000 [Warhammer](http://warhammer.com)
    * Age of Sigmar [Warhammer](http://warhammer.com)
    * Necromunda [Warhammer](http://warhammer.com)
    * Warcry [Warhammer](http://warhammer.com)
    * Kill Team [Warhammer](http://warhammer.com)
    * Horus Heresy [Warhammer](http://warhammer.com)
    * The Walking Dead [Mantic Games](https://www.manticgames.com/)
    * Bolt Action [Warlord Games](http://warlordgames.com)
    * Star Wars Legion [Fantasy Flight Games](https://www.fantasyflightgames.com)
    * Dungeons & Dragons [Wizards of the Coast](https://dnd.wizards.com/)

* Main body images on club.html - [Warhammer](http://warhammer.com)

* 404.html image  [Warhammer](http://warhammer.com)

* Main body image on response.html - [Goonhammer](https://www.goonhammer.com/the-belated-vadinax-week-9-update/)

* Text was adapted from copy found on [Exploding Dice](https://www.explodingdicetabletop.com/)


