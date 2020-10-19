# MSP-1
For my first Milestone project, I have created a website for the band Fleetwood Mac

## The Site
This website show cases the latest and greatest albums from the band Fleetwood Mac. The site is built with my current knowlegde of web developement from the Code Institute, which includeds HTML, CSS and Bootstrap.

The site is deisgned to be mobile first and is fully responsive across all screen sizes.
A live version of the site [here](https://owebster.github.io/MSP-1-Fleetwood_Mac/)
Github Repo [here](https://github.com/owebster/MSP-1-Fleetwood_Mac.git)

## Table of content
* UX & UI
* Objectives
* Wireframes
* Scope
* Technologies used
* Credits

## UX & UI
### UX
The main goal for the user exeprience is to offer an easy way for fans and new potential fans to view the latest news, latest tour dates and to be able to easily hear samples of the Band's most popular songs. This is also the place to find links to streaming services to listen and download our music.
### UI
The main goal for the user interface is to provide a simplistic yet intuitive website for users to navigate. Based off the colour scheme of the latest tour poster, gives a sense of familiarity for people who have seen advertisement in real life.
## Objectives
### For the site owner
* To increase streams/downloads on albums on streaming services
   * This is done by having differnt streaming services in multiple areas of the site
* Increase awareness to latest news by collating our social media and latest tour details within one site
   * Increase sales of tours by having those details within the website
### For the user
* A place to see latest news on:
   * Tour details
   * Latest albums
   * Latest songs
* Listen to samples (aimed at people new to the site)
* An easy place to link to and find social media details and streaming services details

## Wireframes
<img src="assets/images/Wireframe/Phone_Small_Screens.png" alt="Small Screen Wireframe" width="43" height="389" />
<img src="assets/images/Wireframe/Tablet.png" alt="Medium Screen Wireframe" width="61" height="198" />
<img src="assets/images/Wireframe/Large_and_Medium_display.png" alt="Large Screen Wireframe" width="130" height="382" />

## Scope
### Current Fetures
* Site navigation designed for both mobile, tablet and desktop.
   * Navigation bar replacing main header on mobile devices to focus the content and to reduce how much space is taken up
   * Different sized photos to suit screen sizes
   * Tour date section scales to screen sizes
      * One colum style for mobile devices & 2 colum layout for tablet and/or larger
* Soundcloud intergration for samples of greatest hits
* Twitter feed show casing latest tweets
* Responsive carousel sizing accordingly to differnt device sizes
   * Album carousel show casing latest & most popular albums, showcased with high quality images
* Newsletter sign up option to keep up to date with latest band news, including:
   * Latest albums
   * Tour details
   * Merchandise updates
   * New site features

### Fetures to add in the future
- A sign up / sign in option for users to create an account to keep track of concert ticket orders.
- Merch store that show cases and sells the band's merchandise
- Hover states on tour dates that shows either sold our or avaliable shows and directs customers to ticketing website
- Newsletter sign up for latest news from the band (curretly there but not active)

### Structure
The site is built as a one page design with multiple page anchors. It is designed to create a story like layout for the band where the user starts off with:
   * The greatest hits / latest album section
   * Immediatly after that, it gives an option for users to go straight to latest streaming services.
   * Following the exploration of the band's streaming services, users are taken to the band's latest tour details, enticing users to look for shows near their areas
   * From the tour dates, you are taken to the music sample section to explore more of the band's hits directly from the website
   * This is followed by some social media content and an option to keep upto date with the band with a news letter sign up to notify users on new tour dates, new music and potentially new merchandise to purchase

I decided to build the site in this way to offer the user a clear and fluid layout, suiting well as a mobile first site as it gives the feeling of an app like website. 
On the desktop, the site offers a nice continuation between differnt sections.

## Technologies used
These are the languages, framework and resources that I used to build this website:
- HTML
- CSS
- Bootstrap
- Fontawesome
- Github (Web and desktop app)
- Visual Studio Code (VS Code)

## Credits
- [Bootstrap] (https://getbootstrap.com/)
- [ColorTools] (https://www.colortools.net/color_complementary.html) for picking complenmentary and contrasting colours
- Tutor support from Code institute
- [w3schools] (https://w3schools.com) for learning and improving code
- [Css-Tricks] (https://css-tricks.com/snippets/css/css-box-shadow/) Shadowing code for nav bar and seperate sections: 
```
.shadow {
-moz-box-shadow:    inset 0 0 10px #000000;
-webkit-box-shadow: inset 0 0 10px #000000;
box-shadow:         inset 0 0 10px #000000;
}
```
- [Stackoverflow] (https://stackoverflow.com/questions/54597965/how-do-i-get-nav-menu-to-collapse-on-mobile-but-not-on-desktop) Nav bar auto closing toggle 
- [Stackoverflow] (https://stackoverflow.com/questions/4617872/white-space-showing-up-on-right-side-of-page-when-background-image-should-extend) Spacing issue on   site
- [Web.dev] (https://web.dev/font-display/) Used `font-display: swap;` to improve lighthouse score