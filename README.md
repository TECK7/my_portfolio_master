# My Perosnal Webpage

## Webpage Design Documentation Contents

1. [Webpage Building Intent](#webpage-building-intent)
 
2. [Webpage Building Approach](#webpage-building-approach)

3. [Webpage Design Approach](#webpage-design-approach)

	3.1. [Style Guide](#style-guide)
	
	3.2  [Personal Logo and Navigation Bar](#personal-logo-and-navigation-bar)
	
	3.3  [Carousel Container and About Myself Section](#carousel-container-and-about-myself-section)
	
	3.4	 [Background Image Container and Experience Section and Portfolio Section](#background-image-container-and-experience-section-and-portfolio-section)
	
	3.5  [Future Section and Contact Section and Footer Section](#future-section-and-contact-section-and-footer-section)
	
4. [Bootstrap Responsive Framework and Other Plugins](#bootstrap-responsive-framework-and-other-plugins)

	4.1 [Navigation Bar](#navigation-bar)
	
	4.2 [Carousel Container](#carousel-container)
	
	4.3 [About Myself Section](#about-myself-section)
	
	4.4 [Background Image Container](#background-image-container)
	
	4.5 [Experience Section](#experience-section)
	
	4.6 [Portfolio Section](#portfolio-section)
	
	4.7 [Future Section](#future-section)
	
	4.8 [Contact Section](#contact-section)
	
	4.9 [Footer Section](#footer-section)
	
5. [HTML and CSS Files](#html-and-css-files)
	
	5.1 [HTML File](#html-file)
	
	5.2 [CSS File](#css-file)

6. [Folder Structure](#folder-structure)

7. [Challenges and Difficulties](#challenges-and-difficulties)

8. [Summary](#summary)

9. [Reference Lists](#reference-lists)

10. [Live Webpage via Github](#live-webpage-via-github)

11. [What's Up Next?](#what's-up-next)

### Webpage Building Intent

The core intention of building this personal website is to promote myself to prospective employers. 
The website would contain 5 main sections. These sections are “About Myself”, “Experience”, “Portfolio”, “Future” and “Contact”. 

It is critical to allow interested audience to view my personal webpage on their mobile gadgets. Therefore, the website layout is 
designed around mobile first philosophy. Moreover, it is important to create a webpage that is functional on browsers such as Safari, 
Chrome, Firefox and Internet Explorer because targeted audience may have different browser installed on their mobile gadgets. 

---

### Webpage Building Approach

At the start, I had considered three different approaches building my webpage. The first approach is by using free and ready available 
themes from popular websites / blogs. The second approach is to start from scratch by writing completely new HTML 5 and CSS 3 files. 
The third approach is to use popular frameworks such as Bootstrap or Zurb Foundation.  All these approaches have its advantages and disadvantages.

| Approaches       | Advantages                                                          | Disadvantage                                                                                           |
| :--- |:---|:---|
| **Free Themes**  | - Desktop / mobile layout is setup properly                         | - Need to understand how the theme is built before adding or modifying features / effects              |
|				   | - Browser compatibility coverage is broad	                         | - Limited flexibility                                                                                  |
|				   | - Modify existing contents easily			                         |                                                                                                        |
| **From Scratch** | - Great flexibility on generating contents / features / effects     | - More time and effort needed to layout responsiveness for both desktop and mobile screens             |
|                  | - Maintain all contents easily                                      | - All areas of browser compatibility need to be tested                                                 |
| **Framework**    | - Tested and reliable                                               | - The files generated for the project may be larger overall due to additional custom css and js files  |
|                  | - Enable developer to focus more on producing contents              |                                                                                                        |
|                  | - Use ready available JS plugin embedded within the framework to add in special features / effects |                                                                         |

**Table 1** : Personal opinion on different approaches for building website

Eventually, I had decided to use Bootstrap 3.3.7 framework to build my personal webpage. The short duration permitted and the mobile first 
requirements for this project are the reasons that influence my final decision. By using this framework, it allows me to concentrate on generating
contents that are responsive. Secondly, it would allow some valuable time to research and implement better mobile user experience features. 


[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### Webpage Design Approach

Before starting any codes on HTML and CSS file, I had opted to perform some wireframe exercises. This exercise had saved me extra time since the 
wireframe outcome instantly gives me an idea how my website would look like in both desktop and mobile screens. After this exercise, I created a 
personal logo based on my first name. At this stage, I only had finalised the shape and pattern of my logo. 

From here, I started to think how I should put my contents which is engaging and readable on mobile gadgets. So, I started to think of what features
and effects I would need to include into my webpage. Please refer to following figure for the markups performed.

![fig 4](https://cloud.githubusercontent.com/assets/22834712/24225536/1fb33586-0fb5-11e7-912c-8082a5855043.jpg)

**Figure 1**: Webpage Features / Effects Markups

#### +Style Guide+

During the wireframe process, I had chosen to limit the number of colours used for the webpage because I only wanted to promote my contents but 
not my front-end UX/UI skills. In fact, I had tested out a few sets of different colours combination. In the end, I had only used dark blue (#0B1625), 
yellow (#ECE833), white (#FFF) and grey (#808080) colours. At this stage, I decided to insert yellow (#ECE833) colour on my logo. 

As for the font, I only used a single Google font-style across the webpage. The font-family 
chosen is Lato and the fallbacks are "Helvetica Neue", Helvetica and Arial. The font size and weight are adjusted accordingly to suit various screen 
sizes display. Paddings between text and paragraphs are also applied where necessary. Please refer below for the wireframe exercise accomplished.

![figure 1 md](https://cloud.githubusercontent.com/assets/22834712/24224818/69f3afb2-0fb1-11e7-85c5-dc64e533d713.jpg)

**Figure 2**: Desktop and Mobile Wireframe Layouts Part 1

#### Personal Logo and Navigation Bar

The personal logo is located on the left hand side of the fixed navigation bar. This logo position is similar to where a business logo or a brand 
would normally be located.  The links for each main section of the webpage would be floated towards the right hand side of the navigation bar. All
the links would be clearly shown at breakpoint width more than or equal to 768px. The section links would be consolidated into a burger style button
at breakpoints width less than 768px.  

 
#### Carousel Container and About Myself Section

The subsequent container is a Bootstrap carousel container that contains three different images and its respective image caption. This container
is not declared as a main section but a brief opening section at the start once the page is loaded. “About Myself” section would be the following
container right after the carousel container. The container contains an underlined heading and three paragraphs. 

![figure 2 md](https://cloud.githubusercontent.com/assets/22834712/24225064/99191fa6-0fb2-11e7-94ab-435efe8db98a.jpg)

**Figure 3**: Desktop and Mobile Wireframe Layouts Part 2

#### Background Image Container and Experience Section and Portfolio Section
The next container would be used to store images and a “read more” button. The “Experience” section is followed on with an underlined heading
and three paragraphs as well. Subsequent container is for containing “Portfolio” section. This section has a total of three separate individual 
heading, three toggle buttons, three separate individual sub-heading, three separate individual paragraphs and three separate individual images.

#### Future Section and Contact Section and Footer Section
The second last section is the “Future”. It has a total of two individual blocks of containers. The first container has a heading, four paragraphs 
and a logo slider. The second container has an underlined main heading. This is followed by three separate images and thumbnails at the bottom of 
each image. The final section is the “Contact”. The container contains an underlined heading and two paragraph, a form input field, a send button 
and three different social icons. A footer section is included which has all the main section links and a back to top arrow link.


![figure 3 md](https://cloud.githubusercontent.com/assets/22834712/24225172/341f6ffa-0fb3-11e7-8aff-df5d01e25391.jpg)

**Figure 4**: Desktop and Mobile Wireframe Layouts Part 3

[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### Bootstrap Responsive Framework and Other Plugins
As mentioned earlier, Bootstrap 3.3.7 framework is used to build this webpage. Hence, most of the container responsiveness is handled by the 
in-built CSS classes for various screen sizes (i.e. col-lg-x / col-md-x / col-sm-x / col-xs-x) where x is ranging from 1 to 12. These values are
specified in different container tags to suit both desktop and mobile wireframes design layout. However, there are few elements that do not rely
on Bootstrap responsive theme. The main reason is due to the addition of non-bootstrap feature/effects implemented into the webpage. All the 
features/effects added in are to enhance user browsing and navigating experience.

#### __Navigation Bar__
The navigation section is fixed at the top of the page using class navbar-fixed-top. This also means that the navigation bar will always appear at 
the top of the screen wherever the user scrolls downward. In order to save some screen estate, I had included a headroom.js plugin combined with 
some jquery script to hide the navigation bar as the user scroll downward to other contents. The navigation bar will be shown as the user scroll upward. 
This headroom.js plugin is hosted by WickyNilliams on Github. The jquery script can be referred inside the HTML body tag under `“(!-- For Hiding and Showing Navbar onScroll --)”`.

The burger toggle button will also slide in a menu bar from the left when is clicked. This menu slide in feature is a non standard Bootstrap feature and is 
implemented using Bootstrap-Offcanvas plugin contributed by Phil Hughes on Github. The reason for this implementation is to adopt current mobile menu design trend.


#### __Carousel Container__
In the carousel container section, Bootstrap carousel.js is used. In fact, left (i.e. previous) and right (i.e. next) controls has been left out. 
This action was taken because of two main reasons. The first is not to allow these controls to further impede the view of the images in mobile layout. 
Secondly, the carousel indicators would be sufficient for the user to cycle through the carousel. TouchSwipe j.query plugin hosted by Matt Bryson on Github 
is included onto the carousel container. This plugin allows user to swipe through the carousel images. Additional JavaScript would be needed and can be referred
at script outside the HTML body tag `“//For Carousel Swipe Touch Function (Refering to Jquery Mobile Touch-gesture JavaScript)”`. In reality, this is a standard 
feature on mobile gadgets if carousel images are to be added. 

Special effects have also been added to the first image of the carousel and the image captions. These effects are implemented using Animate.css plugin 
hosted by Daniel Eden on Github combined with some JavaScript written by Maria Antonietta Perna at Sitepoint. User can notice that once the page is loaded, 
the first carousel image will zoom in from out. This is accomplished by JavaScript found inside the HTML body tag under `“(!-- For Carousel Image ONLY animation --)”`.
The image caption will slide upward from the bottom instantaneously at every cycled image. This effect is to spice up the caption appearance. 
Final effect in this section is the caption would fade away gradually as the user scroll down using simple JavaScript. This effect is worthwhile because it
actually inform the user that he/she is leaving the current container and should be focusing the contents on the upcoming container. Please refer to script outside
the HTML body tag `“//Fade Carousel Caption when Schroll down”` for details.

When the screen resizes, the carousel images also resize. This responsive feature on the image is needed since Bootstrap carousel default is override by other
CSS properties.  Please refer to script outside the HTML body tag `“//For Responsive Carousel Images when screen resizes”` for details.

#### __About Myself Section__
In “About Myself” section, the container `(i.e. #about-wrapper)` have higher index value than the carousel container `(i.e. #carousel-img)`. 
This setup is to enable parallax effect over the carousel images. The real purpose of including a parallax effect is to create an illusion of depth 
in a 2D scene and adding to the immersion. This effect would not work if JavaScript is not added. Please refer to script inside the HTML body tag 
`“(!-- For Parallax Effect over Carousel --)”` for details. The contents within the container would slide in from the left as user scroll towards the viewport. 
As the user leaves the viewport, the contents would disappear. This is the combination of JavaScript and CSS written by Simon Codrington at Sitepoint. 
The benefit of this is to provide an interesting and interactive experience to engage the user. Please refer to script inside the HTML body tag `“(!--For About Myself Contents --)”`
for details.

#### __Background Image Container__
In this container `(#"experience-sec0)`, parallax effect over the background images has been implemented. The script details can be found script inside the HTML
body tag under `“(!-- For Parallax --)”`. This effect is added not only create an illusion similar to “About Myself” section but also encourage user to view more 
of the image when scrolling upward and downward. Unfortunately, this plugin does not work on Android and IOS devices. The image would static without any degradation. 
A hover effect has been introduced to the “read more” button although hover does not really work well on mobile gadgets. However, the user would still be able to appreciate 
the effect because the CSS pseudo-class :focus is applied with same attributes. This means that if user clicked on the button the effect could still be seen. 

#### __Experience Section__
Contents within this container `(i.e. #experience-sec)` would slide up from the bottom as user scroll towards the viewport. As the user leaves the viewport, the contents 
would disappear. This is the combination of JavaScript and CSS written by Simon Codrington at Sitepoint. Please refer to script inside the HTML body tag `“(!-- For Experience Contents --)”` 
for details.

#### __Portfolio Section__
In this container `(i.e. # portfolio-sec)` would slide in from the left as user scroll towards the viewport. As the user leaves the viewport, the contents would disappear. 
This is the combination of JavaScript and CSS written by Simon Codrington at Sitepoint. Please refer to script inside the HTML body tag `“(!-- For Portfolio Contents --)”` for details.

Once the user is in the viewport, user could toggle on so called “button” labelled as 1, 2 and 3 to show different portfolios. It is important to note that the first portfolio 
under “button 1” is always shown once user is in the viewport.  The user can click on button 2 and button 3 to review other portfolios. Each portfolio would slide¬ in from the 
bottom once user clicked on the button 2 and button 3. Again, this is the combination of JavaScript and CSS written by Simon Codrington at Sitepoint. Please refer to script 
outside the HTML body tag `“(!-- Portfolio Section --)”` for details. The reason for this implementation is to allow more user interaction with my contents and help reduce the user’s 
scrolling footprint.

#### __Future Section__
The contents of this container `(i.e. # future-project-sec)` have two noticeable features. The first one is having a slider container that cycle through all the logos infinitely.
This feature is implemented by using a minified JavaScript file and some scripts within the HTML body tag together with other CSS. The details can be found on 
`“(!-- For Skills Logo/Icon Slider --)”`. The advantage of having this slider is that it could save some space within the container and giving these logo a tidy inline look.

The second feature can be seen on ‘Future Project’ section. The three different projects would bounce in from different angles as user scroll towards the 
viewport. As the user leaves the viewport, the contents would disappear. This is the combination of JavaScript and CSS written by Simon Codrington at Sitepoint. 
Please refer to script inside the HTML body tag `“(!-- Future Project Section --)”` for details. It is a good feature inclusion when user is anticipating your future projects.

#### __Contact Section__
This section is straightforward. All responsiveness used Bootstrap CSS theme. `Formspree.io` is used for email and message input fields. This tool offers 1000 
submissions per email each month and it is sufficient for static webpage. The social links are included using font-awesome icons with some special CSS pseudo 
class :hover and :focus effect.

#### __Footer Section__
This section does not any special features apart from giving each specified section links and the back to top arrow a smooth scrolling effect. 
This is achieved by including a script outside of the HTML body tag which can be found under `“(!-- Script for Individual Section Scroll --)”` for individual section 
and `“(!--Script for Scroll to Top from footer Section --)”` for the back to top button.

#### __Additional Feature__
User may also notice that a floating back to top button would appear on the screen when viewport is 200mm from the top of the screen. This script is 
implemented on the outside of the HTML body tag under `“(!-- Section of Scroll to Top Visible/Invisible Button --)”`.

[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### HTML and CSS Files

#### __HTML File__

The HTML file is written in accordance with HTML 5 standards using English as the HTML language.  `<! DOCTYPE html>` is specified at the 
very beginning so that web browsers can read the HTML file. Within the `'<head>'` tag, several important meta tags are included. These are written as followed; 

* `'(meta charset="utf-8")'`
* `'(meta http-equiv="X-UA-Compatible" content="IE=edge")'`
* `'(meta name="viewport" content="width=device-width, initial-scale=1")'`

Other meta tags such as `<meta name="description" content=" ">` and `<meta name="author" content=" ">` are supplementary. These tags if included, allow web browser 
search engines to capture all information and display below the webpage link of the HTML file. Social media meta tags are included as well. These are written as followed;

* `'(meta property="og:title" content=" ")'`
* `'(meta property="og:description" content=" ")'`
* `'(meta property="og:type" content=" ")'`
* `'(meta property="og:image" content=' ‘)'`

The rest of the HTML file is followed by a <body> tag that keeps all the HTML contents. 

#### __CSS File__
As mentioned in previous sections, a `'(script)'` tag after the closing '(/body)' is created to contain some JavaScript to run some required features / effects. 
These scripts are needed only after the webpage is fully loaded.  Thus, by using style early and script last principle prevails as browsers work top-to-bottom.  
In other words, the principle mentioned here is to prevent unnecessary scripts at the top from delaying or blocking the rest of the page from rendering. 

CSS file is written using CSS3 compliant properties and attributes. There is only one custom CSS file written when building the webpage. It is name custom.css 
which is stored in css folder. This file is linked with the HTML file under `<!-- Custom CSS -->` using stylesheet relation. It is important to point out that the 
navigation bar CSS is stored in bootstrap_offcanvas.css file. This would ensure all navigation related CSS is only managed under a single file. Besides, there are 
several other CSS files are linked to the HTML file due to various plugin implementations into the webpage. All of these CSS files are embedded within the '(head) tag.  

[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### Folder Structure
There are three main folders in this webpage project. The folders are css, images and js. The index.html sitting outside of these folders is the only HTML file for this webpage. 
The css folder contains bootstrap css, font-awesome icons and other plugin css. 

The images folder consists of four sub-folders. These folders’ name is backgrounds, icons, logos, pictures and social. These folders are used to stored images that would be 
appearing on the webpage. The icons folder is used to stored favicons generated for the webpage. These favicons are coloured with dark blue (#0B1625) so that it is displayed clearly on
different web browser tab. 

The robot.txt is created at the root directory. The robot is not allowed to access the js folder, images folder, css/icons folder, css/bootstrap_offcanvas.css file and css/custom.css file.

In general, large webpage with many pages would have a sitemap as a standard. Nevertheless, a sitemap xml file is created to allow the search engines to index a webpage much quicker. 
Once the final project is uploaded to the repository, this webpage link is then submitted to https://www.xml-sitemaps.com (Last visited: 21/03/2017) to generate the sitemap.xml for my personal webpage. 
This xml file is stored at the root of the webpage. In other words, it is locate at the same directory level as index.html and robot.txt.

[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### Challenges and Difficulties 
There are a several challenges and difficulties during the process of the building the webpage. These obstacles arise during the implementation of various features / effects into the 
webpage from third party plugins. Enormous amount of effort and time needed to ensure third party plugins works harmoniously with Bootstrap framework. 

The first real challenge would be enabling the slide in menu. Initially, marcandrews bootstrap-off-canvas-nav plugin is used throughout the webpage building process. This plugin 
works perfectly on Firefox and Chrome browsers. Unfortunately, the slide in menu does not show the sections links in Internet Explorer. The problem could be with the CSS. I had tried 
to do some changes but it couldn’t work. At this point, I made a decision to search for another bootstrap-off-canvas-nav plugin. After spending some time, it finally works across all 
browsers. This demonstrated that not Github plugins are reliable until it’s been tested.

The second difficulty is the research needed to get a solution for implementing a parallax effect on Bootstrap carousel container. Plenty of time is spent to get around the Bootstrap 
framework code base to achieve the parallax effect. Fortunately, this implementation had passed all browser testing. The other challenge is trying to apply some animation on the carousel 
image and the carousel caption. In the end, these features are enabled through using some professional guidance from front end developers that publishes their web building tips and tricks.         

The third difficulty is the parallax effect implementation on to the background images that lies in `'(div id=”experience-sec0”)` under `'(!-- BG Image Container Using Parallax Js--)'`. 
Due to limited time permitted for this project, this plugin is chosen although it does not work on IOS and Android devices. I had chosen to proceed by using this plugin for two reasons. 
Firstly, this plugin is reliable for desktop display across all browsers. Secondly, mobile users may not fully appreciate the parallax effect since the screen is small and as long as the 
images are not subjected to any degradation. 

The other challenge is to find a way to make all contents as compact as possible and as interactive as possible. In order to satisfy both requirements, JavaScript and CSS combination codes are needed. 
Initially, these requirements are met by using guides posted on http://www.web2feel.com/tutorial-for-animated-scroll-loading-effects-with-animate-css-and-jquery (Last visited: 15/03/2017). However, this plugin does 
not work on Internet Explorer when tested. Again, through using some professional guidance from front end developers that publishes their web building tips and tricks, these requirements are met. 

[Webpage Design Documentation Contents](#webpage-design-documentation-contents)

---

### Summary
In summary, wireframe exercise at the start of the webpage building process had helped me to focus what I really want to achieve for my webpage. The style guide, colour scheme, section layouts from 
the wireframe had set me up to code HTML and CSS in a more oraganised way. However, without Javascript skills, it is difficult to implement features and effects into your webpage requirements. 
Thankfully, there are plenty of tutorials, guidance and plugins available to assist my implementation. However, not all sources from the internet are reliable until there are tested out in my project.

To wrap it up, here are a lists of features and effects;

* navigation bar hidden when scroll down and re-appear when scroll up
* first carousel image zoom in once loaded
* carousel image caption slide-up instantaneously at every image cycle
* carousel image caption fade away when user scroll downward to next container
* parallax effect over the carousel images when user scroll down  
* contents in "About Myself" sections slide-in into position from left when scroll to viewport and slide-out when scroll out of viewport
* parallax effect on the background images stored after the "About Myself" section (Effect is static on IOS and Android)
* contents in "Experience" section slide-up into position from bottom when scroll to viewport and slide-down when scroll out of viewport
* contents in "Portfolio" section slide-in from left when scroll to viewport and slide-out when scroll out of viewport
* different portfolio in "Portfolio" section can be view by toggling the labelled buttons
* slider feature for skills/logos, the slider stops when hovered over
* different projects under 'Future Project' heading bounce in when scroll to viewport
* back-to-top button appearing at different sections of the webpage when scroll down, disappear when scroll back to carousel container
* smooth scrolling for all section links and back-to-top links  


### Reference Lists



### Live Webpage via Github

**https://teck7.github.io/teck.github.io**

### What's Up Next?

* Build a landing page that would allow webpage visitor to choose Language version of my web contents
* Make parallax effect on the background image work on IOS and Android system 