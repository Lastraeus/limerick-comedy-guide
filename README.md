# Limerick Comedy Guide


Limerick Comedy Guide is a website that aims to make it easy for Stand-up Comedy fans in and around Limerick City to keep abreast of the various comedy gig offerings in Limerick City. To accomplish this the site serve as an introduction to the comedy scene in Limerick for those who have a newer or more casual interest in seeing Stand-up. It will also serve as a handy directory for booking links and gig listings across the whole Limerick comedy scene for those who wish to save time looking up the myriad avenues of sourcing the information from traditional sites.

A secondary goal is to support the Comedy Groups, Venues and most importantly Comedians that provide the gigs that users of the site would give their patronage to, given sufficient awareness.

## Research

__Audience Stories__

Sourced from fellow local Limerick Comedy “aficionados”.

“It can be hard to keep track of all the different places for comedy, I never know what’s on till it’s too late.” – S. M.

“I could really do with a website or app or something that just has all the different comedy. I didn't even know there was anything beyond entertainment.ie and Ticketmaster for the bigger gigs if you don’t already know the local venues.” C. N.

“Limerick really needs something to tie the comedy together, that you can look at if you aren’t networking with other people and learning about the gigs by word of mouth”.  J M



## Features

As of the latest version, Limerick Comedy Guide is a four page website divided between;

1. __Homepage__ (index.html) to introduce users to the site and to get straight into highlighting the most pertinent information one would need, in general, to get comedy fans sitting in front of the stage. This includes;

    * An Animated Hero Image

    * "A Regular Comedy Nights In Limerick City" Section

    * "A Featured Gigs" Section

![Landing Page]()

2. __Comedy Links__ a Directory/External link page (comedy-links.html) to introduce users to the site and to get straight into highlighting the most pertinent information one would need, in general, to get comedy fans sitting in front of the stage. This includes;

    * The Comedy Links Directory page (comedy-links.html) is primarily a curated list of previously disparate links to do with booking and keeping abreast any comedy gigs in Limerick City.

    * This section would ideally be bookmarked by users for easy access, whenever they want to peruse what's on in Limerick in the Stand-up/Comedy sphere.

![Comedy Links]()

3. __Contact Page__ This page (contact.html) will allow the user to send a message to Limerick Comedy Guide regarding any comments they may have regarding the site subject or whatever they feel is relevant. This could be used theoretically;

    * by fans/comedians to inform the site runner of any gigs/venues that have been overlooked.
    
    * As an inital contact point for businesses to reach out about exposure for their comedy nights etc.
    
    * To increase potential engagement with the site audience.
    
Currently forms submitted simply redirect the user to a placeholder confirmation page. See next section regarding same.
![Contact page]()

4. __Confirmation Page__ This page (confirmation.html) is currently where forms submitted on the contact.html page redirect redirect to. It provides a message to acknoledge the users action. This keeps the user on-site while using/testing the Contact Form.

![Confirmation Page]()

### __Existing Features__

- __Navigation Bar__

    Featured on all pages there is a full responsive navigation bar. This includes a home page link on the top logo and three separate button links displayed together at the top of the screen near the logo. These links are;

    * Home page
    * Comedy-Links
    * Contact. 

    These are the same on each page for easier more-intuitive navigation.

    This feature allows the user to confidently navigate the website and allows the avoidance of using the back button, thereby enhancing the users experience.

    Due to varying screen sizes and associated limitations, these buttons will alternate between Icons and text-buttons dynamically depending on the screen width. The Main Logo will also adjust to Initials instead of words depending on available space.

    ![Nav Bar]()

- __The Landing Page Cover Image__

    The initial landing/home page (index.html) includes a "hero" image, with a cover text. The image is animated for the first few seconds upon loading the site, creating a pleasing zoom effect.

    The cover text gives the user a indication of the sites function and hopefully helps to set a more jovial tone given that this is a website revolving around Comedy.

    This Cover image is also reused on the confirmation.html page.

    ![Cover Image]()

__Regular Comedy Nights Section__
    
    The Regular Comedy Nights Section will be the first section the user scrolls down to from the header.
    This is due to the desire to prioritize the most key information provided by the site; where one can reliably find comedy gigs within the confines of Limerick City. Given their reliable monthly frequency they are by far the most approachable yet overlooked way to see stand-up comedy in Limerick.

    ![Regular Comedy Gigs]()

__Upcoming Gigs Section__

    This section will allow the user to see a curated list of upcoming Comedy Gigs in Limerick, with direct booking links for the user's convienience if they want to book one of the highlighted gigs.

    This section could be updated periodically to keep the content fresh.

    ![Featured Gigs]()

__The Footer__

    The footer section includes (fictional) links to the relevant social media sites for Limerick Comedy Club. The links will open to a new tab to allow easy navigation for the user.

    This would hopefully allow the user to keep engaged with the overall Limerick Comedy Guide initative and goals.

    ![Footer]()

__The Wrapping Grid Column(s) of Comedy-Links AKA The Directory__



![Card Grid]()

__The Custom Google Map of Limerick Comedy Venues__



![Map]()
![Map-Icon-mode]()



### Features Left to Implement

- Possibility to automate some section of the upcoming gig listings sections, sourcing from the linked pages via automated web-scraping script. Can revist with additional python experience etc.

- A media/Gig Videos page - to showcase videos (available youtube clips embedded) and or images from limerick gigs, to enhance audience interest via givnig samples or providing a repository/collection of Limerick Comedy Gigs. Not enough immediately available (/copyright free) media, at present.

## Testing

Primary testing through development process was done via Gitpod python server command to host a browser window of the site. Upon saving changes in gitpod, refreshing the relevant browser window to see updated changes live.

Tested to see that changes reflected design intent.

Resizing browser with CTRL-SHIFT-M on firefox to see responsive-design-mode. Checked down to 320px.

Inspecting any unexpected or hard to diagnose bugs with the inspect source feature in firefox/chrome.

Result of testing is:
    - confirmation that the site layout is as design intended. 
    - confirmation that the site features are fully functional. 
    - confirmation that the site layout adapts as designed dynamically based on the screen size.
    - confirmation that the site content is appropriate to higher organizational goals.

Browsers checked with: 
* Firefox (Windows Desktop 1440p)
* Chrome (windows Desktop 1440p)
* Firefox Mobile on a Samsung A5 2017
* Virtual Browsers via firefox responsive-design-mode assorted mobiles with small (<500px) screen sizes.
* Virtual Browsers via Chrome responsive-design-mode assorted mobiles down to extremely small (280px) screen size. (Galaxy Fold)

### Validator Testing

HTML

- 2 warnings were returned when passing through the official [W3C validator For index.html page](https://validator.w3.org/nu/?doc=https%3A%2F%2Flastraeus.github.io%2Flimerick-comedy-guide%2Findex.html).

Heading 1 use as section headings on home page was a stylistic choice which I felt was necessary for the overall look and design for the page. The limited number of sections and priority of this information was deemed acceptable for the priority a screen reader would give those 2 "Heading 1"s.

[W3C validator For comedy-links.html page](https://validator.w3.org/nu/?doc=https%3A%2F%2Flastraeus.github.io%2Flimerick-comedy-guide%2Fcomedy-links.html) - No Errors


[W3C validator For contact.html page](https://validator.w3.org/nu/?doc=https%3A%2F%2Flastraeus.github.io%2Flimerick-comedy-guide%2Fcontact.html) - No Errors


- CSS

- No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator) - Code was maunally copied from css file for direct input submission.

### Unfixed Bugs


I am currently not aware of any outstanding bugs. The paucity of features was due to this project scope and the early stage of my coding experience.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:

- In the GitHub repository, navigate to the Settings tab

- Navigate to the pages tab. https://github.com/Lastraeus/limerick-comedy-guide/settings/pages

- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://lastraeus.github.io/limerick-comedy-guide/

## Credits

### Content

- Refferences for dates and other details of upcoming gigs were sourced directly from all links showcased on the site.
- Blurbs for gigs and all other misc text was written by me.

- Background image blend mode tutorial from  [Keep Coding Youtube](https://www.youtube.com/watch?v=wfaDzSL6ll0) used on Regular Gigs Section.

- Grids Tutorial for comedy-links page from [Envatotuts on youtube](https://www.youtube.com/watch?v=XHCMvEfFp2I) used on comedy-links page.

- Flexbox Tutorial for index page from [Envatotuts on youtube](https://www.youtube.com/watch?v=t_I4HWMEtyw) used on index page.

- The icons used in the Nav Bar, Footer and Social Media Links are from [Font Awesome](https://fontawesome.com/)

- [Code Institure - Love Running Example Project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/7f2597d68d214acab1fe134e40ad3a9c/w) used for overall guidance and structure to the project/README etc.

- Misc reference for many property settings
https://www.w3schools.com/css/


### Media

- The photos used on the home and sign up page are from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/)

hero.jpg                https://www.pexels.com/photo/close-up-photography-of-microphone-144429/

mic-pass.jpg            https://www.pexels.com/photo/hand-metal-music-musician-33779/

orange-mic.jpg          https://unsplash.com/photos/zoG585VYsV8

orange-stage.jpg        https://www.pexels.com/photo/microphone-stand-on-the-dark-stage-6324813/

small-audience.jpg      https://www.pexels.com/photo/people-sitting-on-chairs-clapping-12432817/