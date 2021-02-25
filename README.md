
![](https://img.shields.io/badge/Microverse-blueviolet)

# HTML-CSS-Capstone-Project
## About the Project 
This is HTML/CSS Capstone project to design a website by personalizing an archived conference website deisng of 'CREATIVE COMMONS GLOBAL SUMMIT 2015' with given client's requirements. 

The website has The home page, the about page and the tickets page. Responsive design is applied for small screen and large screen with min-width of 768px, a single breakpoint.

![screenshot](assets/images/screencapture-henatan99-github-io-HTML-CSS-Capstone-Project-2020-11-02-14_06_12.png)

![screenshot](assets/images/screencapture-henatan99-github-io-HTML-CSS-Capstone-Project-about-html-2020-11-02-14_59_59.png)

![screenshot](assets/images/screencapture-chrome-extension-fdpohaocaechififmbbbbbknoalclacl-capture-html-2020-11-02-15_01_20.png)

### Home Page 
The home page has navbar, front section, main events section, artists section and footer section
  - Navbar has repsonsive feature. The small screen nav bar has only the dropdown menu elment, 
  which displays the bavigation links with hover action. The navbar for larger screen has two sections. The first navbar displays the social media links, user and logout icons. 

  - Front section has the concert title, concert info, date and conert place. The concert title is displayed with big font. 

  - The main events section has articles which gives general information about the program types. The article elements are have 100% width in small screen, where as they are layed out in display flex in 
  larger screens within the parent class. Each article has the same feature with self-descriptive icon, article header and description. The elements are layed out in display-flex with flex-direction row in 
  small screen and column in larger screens. 

  - Artists section has the articles of similar features with artists photo, name, affiliation and about info. The child elments inside the articles are flex-displayed the photo and a div element wrapping the other child elements. The articles have 100% width in small screen and are displayed flex row wrap in bigger screens with 50% width each. The photo has a custome behind-decoration element which is made by absolute-positioned image element of less z-index than the main image. 
  
  - The footer has two sections, which are the partners and the copyright section. The partner section has the logos of partner organizations. The copyright has the concer logo and copyright statement. 

 
  ### About Page 
  The about page has navbar, front section, contact section, logo section, upcoming-events section and teh footer section.
  - Navbar is exactly the same as teh home page

  - The front section is almost similar to the front section in the home page with little more detailed description about the concert.  

  - The upcoming section is a guide to the upcoming concerts. It has upcoming-header, upcoming-info and articles which has descriptive background images and the upcoming conert date and place. The articles have 100% width in small screens and they are flex-displayed with 50% width each in larger screens. 

  - The footer is the same as that of the home page with little different in spacing. It has responsive featire in which the partners section is diplayed-none in larger screens.   

  ### Tickets page 
  The ticket page has ticket section and vip services section with down-pointing arrow section between them.
  - The ticket section has the header, a rounded bordered element with description and a table to pick the tickets from. The table has Ticket for differnt days and with a category of normal, student and VIP.  
  - The vip services section has a rounded border element with description and another bordered elemetns with service menu to pick from. 
  - The submit button has a variable color, $color-red background. 

  ### Stylings 
  SASS and Bootstrap freameworks are used for the stylings of different sections and elements of the page. 
  Partial scss files are used for color, fonts and @mixin collections
   - color partial scss file defines three color variables based on the client requirement 
   - Font partial scss files defines 9 font sizes defined as ratios of a single variable font-size. Seven font weight variables are also defined. 
  The mixins partial scss element defines @mixin abstractions for custom fonts, custom boxes, custom buttons, and custom borders. Math and logic functions are employed to define some of the @mixin abstractions. 

  ### Cool features 
  This website design incorporates a responsive typography by mathematcally define all the font-sizes in terms of few variables which can be easily manipulated, which simplifies maintainance and deisgn flexibilty greatly. 
  The design also has a dedicated partial scss file for slider background which gives the pages a descriptive and visually attractive element. 
  Background images for the slider background and the front section are custom-created using online vector design tool. 
  Icons used in the events sections of the home page are also purely developed vector images using online vector design tool. 
  
## Built With

- HTML5
- CSS3
- SCSS 
- Bootstrap4

## Live Demo

[Live Demo Link](https://henatan99.github.io/HTML-CSS-Capstone-Project/) 


## Getting Started

**Just clone this repo and open index.html file in your browser then you are good to go.**


**To get a local copy up and running follow these simple example steps.**

### clone the repo.


## Authors

👤 **Henok Mossissa**

- GitHub: [@henatan99](https://github.com/henatan99)
- Twitter: [@henatan99](https://twitter.com/henatan99)
- LinkedIn: [Henok Mossissa](https://www.linkedin.com/in/henok-mekonnen-2a251613/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Some icons used from [iconify](https://iconify.design/)

## 📝 License

This project is [MIT](./LICENSE) licensed. 
