#The Dreadhunter Website


##UX

Who this website is designed for.
-1 fans
-2 potential fans

Fans who want further ways to interact with the band can do so by joining the fanclub
Fans can listen to the music, check for upcoming tour dates and check for new releases

Potential fans are greeted with the homepage image to confirm they are in the right place, can listen to the material and gain a feel for the bands presenece.
Existing fans can check for new releases on the homepage, check for upcoming tour dates on the tour page, listen to the media and join the fanclub if they have not done so already.
![Homepage](/assets/images/wireframes/homepage.png)
![Tourpage](/assets/images/wireframes/tourpage.png)
![Mediapage](/assets/images/wireframes/mediapage.png)
![Fanclubpage](/assets/images/wireframes/fanclubpage.png)

##Features

Feature 1 The navbar exists across all pages, fixed to the top, it does not take up a large amount of space and provides the user with an obvious link to any page on the site.
Feature 2 The footer also exists on all pages if the user scrolls to the bottom. The footer provides the links to whichever social media platforms the band are present on.
Feature 3 The Homepage update section. Beneath the hero image and band history exists a container with the lateset updates from the band, in this case it is an embedded music video for the latest single.
Feature 4 The Tour page occupies a bootstrap grid which will scale across all devices. This section allows the user to scroll through the upcoming concerts. If a concert div is clicked on, the user will be brought to the ticketmaster website in a new page.
Feature 5 The Media page allows users to listen to or watch the band's releases. Currently these exist as links to youtube which open in a new page, however these can also be embedded to keep the user on site.
Feature 6 The fanclub. The fanclub page allows the user to gain access to the band's fanclub. When the members login button is clicked, a modal will appear allowing the user to input their email address and password. Currently this feature will redirect the user back to the homepage. In the future this could bring th user back to the homepage with the added features of being signed in.

##Future ideas

A merchandise store, which could be a link to an external site (the band's merch store provider for instance). It could also exist as a page on the site accessible through the navbar.
A sign up page. On the fanclub page there should be a sign up button on the fanclub page, which will redirect the user to a new window where they can input all the relevant information to become a member. This was partially implemented in the early stages of the project but was later removed to keep things tidy. There is also no data manipulation at this point so it would serve little purpose.
                
##Technologies used

This site is constructed primarily in HTML and CSS. 
Bootstrap 4 is utilized along with bootstrap CSS and JQuery
Font awesome is used to provide the icons for the navbar button and the social media links.
Google fonts is used to provide the Anton and Oswald fonts that are present across the site.

##Testing

This site was tested on gitpod during the early stages of construction. The port was open in a separate window and as changes were made they were checked at different screen sizes using the element inspector in the browser. This was done in both chrome and firefox.
Later on the site was deployed to Github pages which can be done in the settings section of the Github repsitory.
At this stage the site was tested on a number of mobile phones, tablets and laptops.
It was at this point I recognised that the navbar button and social media links were too small, while they looked okay on a larger screen and so they were enlarged from a font size of 24px to 32px.

##Sources

###Images
The hero image on the homepage depicts the real band "immortal" and was sourced from https://en.wikipedia.org/wiki/Immortal_(band)
The album artwork was created using public domain images from the NASA website https://www.nasa.gov/multimedia/imagegallery/index.html

###Text

The list of reasons to join the fanclub was copied from the Iron Maiden Official Website and minor alterations were made.

###Acknowledgements

Research was conducted before the project was started to see how a band website should be laid out. 
One in particular which I found visually appealing was the Kid Rock Website https://kidrock.com/
The inspiration for the navbar was found here. 

Many of the band websites contained the social media links in the header of the page. With everything else I felt that this was too busy and decided to keep the social links contained in the footer.



