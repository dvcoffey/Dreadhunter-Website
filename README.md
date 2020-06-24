# The Dreadhunter Website

This website exists as an online presence for the fictional heavy metal band 'Dreadhunter'
Its primary purpose is to provide information about the band. 
It contains features such as: 

- Latest updates
- Concert announcements 
- Access to the media 
- Access to the fanclub.


## UX

This website is designed with two main users as the focus:
1. The Fans
2. The Potential Fans

-As a potential fan, I want to find out more about the band. I am directed to the website. 
![Homepage](/assets/images/wireframes/homepage.png)
Potential fans are greeted with the homepage image and band logo to confirm they are in the right place.

Now that I am on the website I would like to see some of the band's material
![Mediapage](/assets/images/wireframes/mediapage.png)
A media page will allow access to music/music videos from the band.
They can listen to the material and gain a feel for the bands presenece.


- As an existiing fan, I want to find out when the next concert is. 
![Tour](/assets/images/wireframes/tourpage.png)
I will go to the website and check for upcoming tour dates near me.

-As an existing fan might also want further ways to interact with the band and the fanbase.
![Fanclubpage](/assets/images/wireframes/fanclubpage.png)
The fanclub page provides acces to the fanclub.

## Features

- Feature 1
The navbar exists across all pages, fixed to the top, it does not take up a large amount of space and provides the user with an obvious link to any page on the site.
- Feature 2 
The footer also exists on all pages if the user scrolls to the bottom. The footer provides the links to whichever social media platforms the band are present on.
- Feature 3 
The Homepage update section. Beneath the hero image and band history exists a container with the lateset updates from the band, in this case it is an embedded music video for the latest single.
- Feature 4 
The Tour page occupies a bootstrap grid which will scale across all devices. This section allows the user to scroll through the upcoming concerts. If a concert div is clicked on, the user will be brought to the ticketmaster website in a new page.
- Feature 5 
The Media page allows users to listen to or watch the band's releases. Currently these exist as links to youtube which open in a new page, however these can also be embedded to keep the user on site.
- Feature 6 
The Fanclub. The fanclub page allows the user to gain access to the band's fanclub. When the members login button is clicked, a modal will appear allowing the user to input their email address and password. Currently this feature will redirect the user back to the homepage. In the future this could bring th user back to the homepage with the added features of being signed in.

## Future ideas

- A merchandise store, which could be a link to an external site (the band's merch store provider for instance). It could also exist as a page on the site accessible through the navbar.
- A sign up page. On the fanclub page there should be a sign up button on the fanclub page, which will redirect the user to a new window where they can input all the relevant information to become a member. This was partially implemented in the early stages of the project but was later removed to keep things tidy. There is also no data manipulation at this point so it would serve little purpose.
                
## Technologies used

This site is constructed primarily in HTML and CSS. 
Bootstrap 4 is utilized along with bootstrap CSS and JQuery
Font awesome is used to provide the icons for the navbar button and the social media links.
Google fonts is used to provide the Anton and Oswald fonts that are present across the site.

## Testing

This site was tested on gitpod during the early stages of construction. The port was open in a separate window and as changes were made they were checked at different screen sizes using the element inspector in the browser. This was done in both chrome and firefox.
Later on the site was deployed to Github pages which can be done in the settings section of the Github repsitory.
At this stage the site was tested on a number of mobile phones, tablets and laptops.
It was at this point I recognised that the navbar button and social media links were too small, while they looked okay on a larger screen and so they were enlarged from a font size of 24px to 32px.

## Sources

### Images
The hero image on the homepage depicts the real band "immortal" and was sourced from https://en.wikipedia.org/wiki/Immortal_(band)
The album artwork was created using public domain images from the NASA website https://www.nasa.gov/multimedia/imagegallery/index.html

### Text

The list of reasons to join the fanclub was copied from the Iron Maiden Official Website and minor alterations were made.

## Acknowledgements

Research was conducted before the project was started to see how a band website should be laid out. 
One in particular which I found visually appealing was the Kid Rock Website https://kidrock.com/
The inspiration for the navbar was found here. 

Many of the band websites contained the social media links in the header of the page. With everything else I felt that this was too busy and decided to keep the social links contained in the footer.



