# Fleetwood Mac - Milestone Project 1
![mockup_image](assets/images/Wireframe/site_mockup.png)
## An Overview
This website for the band Fleetwood Mac is created for my first milestone project. For my first project I wanted to build a website showcasing my knowledge of how to use HTML, CSS and Bootstrap together and individually. Showcasing not only a mobile first approach but also how it scales to other devices. 
I settled on the idea of building a website for a band because of the current frustration with artist/band websites where as a user/customer, I cannot get everything I want from most sites (including Fleetwood Mac's own site) and most of them are not as easy to navigate (most rely on taking you to external sites for samples, latest news and latest tour details).
So this site was built to be simplistic to use, yet filled with the relevant details a user would want if they're visiting the stie for the first time or if they're coming back for more.
In this document I will go through what I have built and why, including the ideas I want to implement in the future that I have not been able to so far due to the fact that I have not yet learnt certain languages / frameworks that I would need to include ideas into my first project.

## Table of content
   * UX 
   * UI
   * Objectives
      * For The Site Owner
      * For The User
   * Wireframe
   * Scope
      * Start
      * Middle
      * Ongoing
   * Technologies Used
   * Credits

## UX
### The Experience:

For my first project I wanted to focus on building my site to be as user friendly as possible. Making sure differnt elements on the site act as they should and look as they should. 

For example, when a user typically sees an icon on screen (Music streaming icons or social media icons), they would expect for it to do somehting or take them somehwere that is relevant to the content they are looking at, so even the small twitter icons on the latest tweets section would take you to the relevant tweet, not just twitter.com in general. Or how the music streaming icons take you to the relevant site on desktop or how on mobile, it will take the user to the correct applicaiton (Apple Music to Music App, Spotify to the Spotify App and YouTube to the YouTube App).

Another part of the site I focused on was the journey between differnt secitons. This lead to always having the navigation bar at the top of the site (by using the `sticky-top` funcitonality) to allow users to jump to differnt secitons no matter what part of the site they're on. This scales over all screen sizes, no matter if youre on desktop or mobile. With this choice, I also made the decision to hide the main logo from the page as you scroll down to let users focus on the content of the site with the most space as possible (meaning mobile/small screen users will not need to worry about a big logo taking up most of the space).

### Journey of the Site:
Following on with the expereince of the site, my main focus of building the site was to ensure I had a clear journey for users when visiting the site. This meant that each section flowed with each other and made sense to be one after the other. 
When someone visits the site ->

   * The navbar is going to always be on top to allow users to easily jump between differnt sections.

   * They are greated with the hero carousel, where they can see the latest albums as well as any news about the band.
   
   * Then as they move down, if they any of the hero carousel catches their attention, they are then greated with differnt options to link to the band's streaming services (which mentioned above take users either to the appropriate website or mobile application via the `_blank` target).

   * Users are then greated with the band's latest tour details, with where and when they're playing. This can help entice users to seek out and hopefully purchase tickets (ticket sales feature to be added in the future) to the band's shows, creating excitment for the user and increases the band's ticket sales.

   * From there if users would like to get a taste of what the band can offer, there is a Sample section right underneath. Allowing users to listen to snippets of the band's latest and greatest hits without having to leave the page.

   * Following on from the Sample section, users can see any latest news via the Band's twitter account (directly on the site, but also with associated links to the corrosponding tweets - again with the `_blank` target to ensure users can come back to the site easily even if they go to the social media page)

   * Second to last seciton on the page encourages users to "Sign Up" for the band's newsletter for more informaiton about upcoming tours and albums. This allows users to keep up to date but also will bring users back to the site as Newsletters / updates will direct users back to the webpage (actual newsletter feature to be added in the future).

   * Finally the footer has the relevant social media and streaming services links to remind users where to find the band's. This acts as a "summary" of sorts to remind users about what they have seen throughout the site.


### Colours:
Part of my focus when thinking about UX was the colour scheme as well. I wanted to create a sense of familiarity for users who have seen the latest albums and to associate these colours into new user's minds to remind them of the site when they eventially see the hero image of the site (which is the latest album).
These colours are also good constrasting colours, so accessibility customers can still navigate through out the site without inturuptions.
Because of the contrast of the colours, it also helps with creating a sense of divition between each section.
The primary colours I used are:
   * Deep Red     : #8E191C   - This is being used for the - Hero Logo, Nav Bar, Text (on light gold background) and Section Blocks on ulternating sections
   * Gold         : #e1c281   - This was chosen specifically to match the borders of the latest "Don't Stop, 50 Years" album and be used as the majority of text that have #8E191C as the background colour.
   * Light Gold   : #fffcea   - This light gold acts as the background colour of the entire page. It offers a nice contrast to the Deep Red (#8E191C) and also is easy on the eyes, so even if you're viewing this page on a mobile device with high brightness, it stays soft on the eyes in comparison to standard white.


## UI 
### The Interface:
The site has been built to be modern and mobile first.
This is shown in differnt areas of the site:

   * The Header / Nav bar are rounded off with corner radius and shadow to create a layer sort of effect, where the areas that are Deep Red (#8E191C) are floating ontop of the background (#fffcea). This is also seen with the alternating sections (Tour dates and latest tweets) where they have all four corners rounded off as well.

   * When the user scales up from mobile view, they don't just see a larger image in the hero carousel, they are given a similar image but with more content where possible (differnt style album artwork or differnt image entirely). This is done so the images are not just "larger" more stretched out versions of the ones seen on a mobile site.

   * Nav bar also expands when going from a small screen to medium screen to large screen, expanding the hidden sections from the dropdown menue to be on the navbar itself to utilise the larger space on larger screen devices (desktops, laptops or suitable tablets).

   * Smooth scrolling is enabled for the entire page, mobile and desktop. However Safari does not support this feaures without extra javascript (a feature that I wish to add in the future).

   * Colums also change depending on screen size, on mobile most sections unitlist `col-12` to make sure not too much is on screen at one go. Then on tablet and desktop they respectably change to `col-6`, `col-4` or `col-3` dpending on the content. (seen on Tour section, Music Sample section and Twitter section).


## Objectives
### For the Site Owner:
These are some of the considerations I have taken as a site owner:
   * Making sure that the site is easy to navigate and caters to all people (with and without accessibility needs)
   * To have a website that has colours in which are memerable and easily identifiable as the band's latest colours. As well as being easy on the eye and not too jarring
   * To stand out compared to other bands, by being modern and:
      * To offer a one stop shop for everything related to the band, meaning that the customer does not need to go to differnt websites to get differnt information (tour details, social media and music all under one site)
   * To increase traffic on the site itself (with re-visiting options like Newsletter and the first place to showcase latest music samples etc)
   * To increase traffic on the band's streaming services (which help bring revenue in)
   

### For the User:
And for the user:
   * The user can expect to have a easy to navigate site with clear sections. So that they can easily identify when they're going from one section to another
      * This is also backed by the navbar being always on top
   * The Hero Carousel shows the user the band's latest albums, allowing the user to find out and see what the latest albums look like
   * Streaming services links allow users to easily add and listen to music in popular streaming services, taking them directly to the app on mobile and taking them to the corrosponding site on desktop
   * Tour section is a clean and easy to understand when and where the band will be performing next
   * Music sample section showcases the band's latest and greatest hits wihtin the site, allowing users to explore new music without having to leave the website
   * Tweet section shows that the band is on social media and shows latest tweets to help keep users up to date
   * Newsletter section provides a clear and straightforward signup process (minimal amount of details needed, meaning that users wont feel like they have to give up alot of privacy just to sign up to a newsletter)

## Wireframe:
For my wireframes, I used balsamiq Wireframes to mockup and create the site in differnt device sizes. Shown below are the differnt wireframes for Mobile, Tablet and Desktop. I started with the mobile site and worked from there to scale up the deisgn. You can click on each image for a larger size.
<img src="assets/images/Wireframe/Phone_Small_Screens.png" alt="Small Screen Wireframe" width="43" height="389" /> <img src="assets/images/Wireframe/Tablet.png" alt="Medium Screen Wireframe" width="61" height="198" /><img src="assets/images/Wireframe/Large_and_Medium_display.png" alt="Large Screen Wireframe" width="130" height="382" />
