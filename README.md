# The Dreadhunter Website

![](assets/images/mockup.png)


A live demo of the website can be found [here](https://dvcoffey.github.io/Milestone-Project-1/)

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

### User Stories

#### As a potential fan, I want to find out more about the band. I am directed to the website. 

Potential fans are greeted with the homepage image and band logo to confirm they are in the right place.

#### Now that I am on the website I would like to see some of the band's material

A media page will allow access to music/music videos from the band.
I can listen to the material and gain a feel for the bands presenece.

#### As an existiting fan, I want to find out when the next concert is. 

I will go to the website and check for upcoming tour dates near me.

#### An existing fan might also want further ways to interact with the band and the fanbase.

The fanclub page provides acces to the fanclub.

All users should also expect to find links to each social media platform the band is active on.
These will be available in the footer section of the site.


## Strategy
This site is primarily B2C focused, in this case the business is the band and the customer is the fan.
The goal is to provide the user with an experience of the bands overall presence and ways to interact with the band and the community.
This includes information about the band itself, information about upcoming shows, along with access to some of the bands material as well as the fanclub.  

## Scope
New visitors and potential fans should be provided with enough information to determine if this is a band they like (or dislike).
Fans can then use this site as a hub to access the fanclub, the various social media platforms that the band are present on and see the new songs/music videos that have been released. 

## Structure
The navigation bar will always be available across the site which will provide clear directions for which page the user wants to access.
The brand is clearly visible in the Navbar accompanied by the hero image on the homepage so that the user knows they are in the right place
The footer will be available at the bottom of every page which will provide acces to the band's Youtube, Facebook and Twitter profiles.
The site consists of 4 pages:
1. The Home page 
2. The Tour page
3. The Media page
4. The Fanclub page

## Skeleton
The following skeleton was created using Balsamiq
(https://dvcoffey.github.io/Milestone-Project-1/assets/dreadhunter-wireframe.pdf)

## Surface
The color scheme mainly consists of red black and white, these colors are appropriate for the heavy metal theme.
The presence of red was toned back significantly later on in development as it was distracting and made certain sections difficult to look at.
It is still present however in the hover effects.
All buttons have a consistent shape accross the site and are silver with black text.

## Features

#### Navbar
The navbar exists across all pages, fixed to the top, it does not take up a large amount of space and provides the user with an obvious link to any page on the site.

#### Footer

The footer also exists on all pages if the user scrolls to the bottom. The footer provides the links to whichever social media platforms the band are present on.

#### Homepage

This opens with a band picture (hero image). Beneath the hero image and band history exists a container with the lateset updates from the band, in this case it is an embedded music video for the latest single.

#### Tour Page

The Tour page occupies a bootstrap grid which will scale across all devices. This section allows the user to scroll through the upcoming concerts. If a tour link is clicked on, the user will be brought to the ticketmaster website in a new page.

#### Media Page 

The Media page allows users to listen to or watch the band's releases. Currently these exist as links to youtube which open in a new page, however these can also be embedded to keep the user on site.

#### Fanclub 

The Fanclub. The fanclub page allows the user to gain access to the band's fanclub. When the members login button is clicked, a modal will appear allowing the user to input their email address and password. Currently this feature will redirect the user back to the homepage. In the future this could bring th user back to the homepage with the added features of being signed in.

## Future ideas

- A merchandise store, which could be a link to an external site (the band's merch store provider for instance). It could also exist as a page on the site accessible through the navbar.
- A sign up page. On the fanclub page there should be a sign up button on the fanclub page, which will redirect the user to a new window where they can input all the relevant information to become a member. This was partially implemented in the early stages of the project but was later removed to keep things tidy. There is also no data manipulation at this point so it would serve little purpose.
                
## Technologies used

This site is constructed primarily in HTML and CSS. 
Bootstrap 4.5.0 is utilized along with bootstrap CSS and JQuery to simplify dom manipulation.
https://getbootstrap.com/

Font Awesome 4.7 is used to provide the icons for the navbar button and the social media links.
https://fontawesome.com/v4.7.0/
There are later versions of Font Awesome. But the social media and nav icons required for the project were available here.

Google fonts is used to provide the Anton and Oswald fonts that are present across the site.
https://fonts.google.com/

## Testing

This site was tested on gitpod during the early stages of construction. As changes were made they were checked at different screen sizes using the element inspector in the browser. This was done in both chrome and firefox.
Later on the site was deployed to Github pages.
At this stage the site was tested on mobile phones, tablets and laptops.
I recognised that the navbar button and social media links were too small, while they looked okay on a larger screen and so they were enlarged from a font size of 24px to 32px.

### Issues Encountered

Footer behaviour was an issue for a large part of development. I wanted the footer to stay at the bottom of the page
even if there was not enough content. At the same time I wanted the footer to be at the end of the content if there was
more than the page would fit. A solution was found using bootstrap flexbox and setting the minimum height of the body to 100% of the view height.

### Code Validation

#### HTML 
Validated at https://validator.w3.org/

#### CSS
Validated at https://jigsaw.w3.org/css-validator/

#### Vendor Prefixes 
Added using https://autoprefixer.github.io/

## Sources

### Images
- The hero image on the homepage depicts the real band "immortal" and was sourced from Wikipedia
https://en.wikipedia.org/wiki/Immortal_(band)

- The album artwork was created using public domain images from the NASA website 
https://www.nasa.gov/multimedia/imagegallery/index.html

### Text

The list of reasons to join the fanclub was copied from the Iron Maiden Official Website and minor alterations were made.

## Acknowledgements

Research was conducted before the project was started to see how a band website should be laid out. 
One in particular which I found visually appealing was the Kid Rock Website https://kidrock.com/
The inspiration for the navbar was found here. 

Many of the band websites contained the social media links in the header of the page. With everything else I felt that this was too busy and decided to keep the social links contained in the footer.



