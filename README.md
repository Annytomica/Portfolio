![hero banner](assets/readme/readme_hero-banner.png)
# Portfolio website for Anny Devoy

This portfolio website was developed to showcase the two complementary roles of Anny Devoy, who is a Neuroscientist and Full Stack Developer. Dr Devoy has led and worked on a diverse range of projects. The focus of the website is to highlight this wide range of experience. It communicates the details of each project in a clear and easy to understand way to make the information accessible to those without technical expertise in these areas. The goal of the site is to expand Dr Devoy’s work opportunities by enabling potential employers, recruiters, and collaborators to recognise her unique skillset.

The live portfolio website can be accessed [here](https://annytomica.github.io/portfolio/index.html) 

![Site Mockup](assets/readme/readme_site-mockup_homepage.png)

## Technologies
- HTML – for basic site structure
- CSS – for visual appeal and responsive design features
- GenAI – creation of hero image and logo
    - ChatGPT 3.5 – visual concept creation and prompt development
    - MidJourney – Image generation
- Figma – visual concept development, colour palette selection
- Balsamic – site map and wireframe creation 
- Adobe Photoshop – Adjustment of image sizing and pixel density, modification of hero banner for each page.
- Canva – Midjourney logo modification – background colour adjustment and circular crop
- Pixelied.com – conversion of jpeg and png image files to webp for efficient loading
- Favicon.io – generation of favicon from logo design.
- UI.dev – amiresponsive was used to test each page responsivity to screen size and create site mockup images.

## Site Design Process
### Goal

### Site Map

### Visual Identity
#### Logo
#### Hero
#### Colour Palette
#### Design concept - research
### Wireframe
### Development process

## Features
### Existing features
#### Logo
The logo was generated using MidJourney, using the initials AD as starting point, with clean lines and simplicity as theme. It was linked to the hero banner through requested colour palette – although this did not match perfectly for all colours and may be edited in future.

![Logo](assets/readme/readme_logo.png)

The logo background shape and colour were altered using [Canva](https://www.canva.com/)

A matching favicon was generated from the logo using [Favicon.io](https://favicon.io/favicon-converter/)

#### Navigation bar
The Navbar is featured on all pages of the site and its structure and functionality is based on the navbar from the ‘love running’ walkthrough project.

It has links to all pages – home, portfolio, publications and contact plus the logo on the left side of the nav bar is also a link to the homepage.
![Navbar large](assets/readme/readme_navbar_largescreen.png)
The active page is highlighted by colour change to #C74E24 plus presence of underline. The color contrast of navbar background and active colour scores badly for normal font sizes that are below 14pt. However, as the font in the navbar is never below 14pt and is a heavier weight than normal it was kept.

Hovering over the links in the nav bar changes them to #9E9E7B with underline. This color passed contrast testing. 

On screens sizes of tablet and below the page links are a dropdown menu, indicated by using the three stacked bars icon from font awesome.

![navbar small](assets/readme/readme_navbar_smallscreen.png)

#### Hero banners
The original hero artwork created in MidJourney was designed to represent the interplay between neuroscience and AI development– the area of tech that Anny is aiming to become part of. See below.
![original hero image](assets/readme/readme_hero_full.png)

However, the image was quite wide and limited the possibilities for overlaying page titles. Therefore, the image was modified in Adobe Photoshop such that each page had a hero banner with different elements of the original artwork to provide a continuity of theme across pages but with increased capacity for functional page titles.

The portfolio and contact pages have different hero images for small and large screens to avoid issues of page title crowding.

#### Homepage
The Scientist and Coder titles provide a succinct summary of who Anny Devoy is and immediately piques the interest of the site visitor.
![homepage](assets/readme/readme_homepage.png)
Very simple and clean layout of four thumbnail images for latest projects that link to the relevant sections in the portfolio page

The design has thumbnails with drop shadow, to attract attention and create the impression they are hovering on the page and highlight they are individual elements.

#### Portfolio
This is the largest page. It showcases all the projects. 
Each project has 2-4 images or video that best summarise the project. This is accompanied by one paragraph that provides a clear and succinct description of the project. Care is taken to not assume technical knowledge of the topic so that the information is accessible to everyone.
![portfolio]()
The Big Data and Neuroscience projects have youtube videos embedded that help summarise the information.

The Genome Engineering and Front End projects have a mix of large and small images on large screens. The large images are replaced with small format images on small screens to enable efficient viewing.

On large screens the images are presented in a row but as the screen size decreases they are stacked in columns, first at small laptop (992px) and then again at mobile (400px).

#### Publications
This is a simple yet visually boring page. Its importance is that it allows linking the portfolio projects to the relevant publications plus a general overview of Anny Devoy’s research output.
![publications](assets/readme/readme_publications.png)
All publications are open access, which means anyone can access and read the papers without being blocked by a paywall. External links to access the full paper are provided for each publication.

On smaller screens the authors list is contracted to just the first four authors, the remainder being replaced by et al. , to limit the screen space each publication takes up and reduce scrolling.

#### Contact
The purpose of this page is to allow the visitor to contact Anny Devoy and to find out more about her.
![contact]()
The main feature of this page is a contact form, where the user inputs name, email and company as well as the message. 

The contact form takes half the page, with the other half taken up with a dramatic image of a motor neuron imaged by electron microscopy. As screen sizes decrease the form stacks on itself and then at mobile screen size the image stacks above the form.

#### Footer
As this site is for professional purposes the focus was put on having professional media links rather than social media, of which Anny Devoy is not a big user.
![footer](assets/readme/readme_footer.png)

The links provided are:
- Linked In – professional profile and online CV
- Github – to allow visitors to see Anny Devoy’s code and development processes.
- Research Gate – access to additional data from projects as well as professional Research Scientist profile and impact statistics – funding, citations, science engagement.
- Figma – additional visual projects and visual development processes for portfolio site.

### Features for the future
#### About Me
The About Me page is important to introduce Anny Devoy to the site visitor beyond her professional capacity. It introduces Anny as a real person and humanises the visitor’s perception increasing the likelihood of positive outcomes. This page is not required to fulfil the requirements of Project 1 assessment for the Diploma in Full Stack Development at Code Institute and so, in the interests of keeping the assessed project manageable, was excluded from the original development. Once all assessment has been completed this page will be added and the site deployed to a real domain – annydevoy.com – hosted by Hostinger.

#### Professional Media links on contact page hero banner
On the hero banner the professional media links from the footer will be presented, in larger size than footer, to highlight them as another way to find out more about Anny Devoy’s projects.

##### Features for when the number of portfolio projects increases:
-	Singular pages for each portfolio project – hidden from navbar but linked to via the portfolio page. This would allow reduction of the number of images used on the portfolio page and thus limit the scrolling required on small screens.
-	Make the Scientist and coder on homepage active links to the correct section on the portfolio page.
-	Hide the publications page – this is a really boring looking page and while its important to link to relevant publications from the portfolio page and be available as a general reference, having it accessible from a different menu in the footer and removing from navbar would be a cleaner approach in the long-term as it is only relevant for the scientist half of the portfolio.

## Testing
### General Strategy
The site was deployed very early on github pages, when just the basic structure of each page plus the nav bar were ready. This allowed daily assessment of functionality of the deployed site and helped identify any issues quickly so they could be fixed before moving on to new features. Gitpod was used as the IDE and the site was run on a server live during development so code could be assessed immediately. Chrome Devtools were actively used during gitpod sessions to test responsive features for different screen sizes as they were developed. Using this strategy most bugs and functionality issues were identified and resolved quickly, before they became a major issue for the site.

### Devices and Browsers
#### Web Browsers
Chrome (primary), Firefox , Edge and Brave

#### Devices
- Phones: Pixel4a, iPhone x, Galaxy x
- Tablets: iPad 9.5”, Surface 12”
- Laptops: Dell Inspirion 13”, MacBook Air 13”, MacBook Pro 17"
- Desktop screens: BenQ PD series 27”

### Final Validation
HTML – all pages passed validation with no errors detected using the official [W3C HTML validator](https://validator.w3.org/). The summary of results can be found [here]()

CSS – all pages passed validation with no errors detected using the official [W3C CSS validator](https://jigsaw.w3.org/css-validator/). The summary of results can be found [here]()

Accessibility and functionality – all pages showed high accessibility, high functionality and SEO optimisation using Chrome [Lighthouse DevTools](https://developer.chrome.com/docs/lighthouse/). The summary of results can be found [here]()

## Bugs
### Fixed
-	The original concept for the contact page had the form overlayed on a background image. The contrast was not acceptable and the background image sizing on different screen sizes was erratic. These issues were resolved by replacing the design concept with one that has the form beside the image.
-	Contact page image loading speeds on small screens was poor – identified from lighthouse assessment – so a new image for small screens was introduced to overcome this issue.
-	Youtube videos would not work. The tutorial from [W3schools](https://www.w3schools.com/html/html_youtube.asp) helped me identify that the original links used lacked the correct /embed/ action within the link.

### Unfixed

## Deployment
The site was deployed to GitHub pages using the recommended process <link>. 
In Summary:
1.	Within the GitHub repository for this project <link>, the settings tab at the top of the page was accessed.
2.	From settings, the Pages tab was selected from the menu on the left side of the screen, within the Code and Automation section of the menu.
3.	From Pages, the Source was set to ‘Deploy from a Branch’, and the Branch was set to ‘main’, using the dropdown menu with default label of ‘none’ before selection.
4.	Once main branch is selected, hit the save button (ignore the folder/(root) menu).
5.	Once saved, the link to the active site will appear at the top of the page.
6.	Alternatively, from the main repository page, within the menu on the right a ‘Deployments’ will now have appeared. This section provides a link to the active site as well as summarizes the number of updates the site has received since initial deployment.


![GitHub deployments](https://img.shields.io/github/deployments/Annytomica/portfolio/github-pages)
![GitHub language count](https://img.shields.io/github/languages/count/Annytomica/portfolio)
![GitHub top language](https://img.shields.io/github/languages/top/Annytomica/portfolio?color=yellow)

## Credits
I would like to acknowledge and thank the following people and resources used in the creation of this site.
### Content
-	[W3schools.com]() was used repeatedly for tutorial guidance on responsive design, CSS flex properties, html character entities and insertion of youtube video.
-	[Medium.com]() was used for guidance on image swapping for small screens and cool features to use in README.md <links>
-	Code for responsive nav bar was taken from the Code Institute [Love Running]() walkthrough project. <link>
-	Code for hiding text on small screens - used for publications page to hide authors - was taken from [W3schools.com]() <link>
-	The icons in the footer and navbar are from [Font Awesome]()
-	The form content submission validator was taken from Code Institute course content

### Media
-	The youtube video that explains ALS used on portfolio page was created by ….
-	The illustration in the genome engineering project was created by Megan Abel – iammeganabel.com. Megan granted permission for use.
-	The Github summary bar used in README.md is from [shields.io](https://shields.io/badges/)
-	All other media used is property of Anny Devoy

### Acknowledgements
Design inspiration was taken from:
- blogs about portfolio site design at [Hostinger](https://www.hostinger.co.uk/tutorials/web-developer-portfolio), [freecodecamp](https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/) and [careerfoundry](https://careerfoundry.com/en/blog/data-analytics/data-analytics-portfolio-examples/) <link>
- The portfolio sites of [Tim Hopper](https://tdhopper.com/), [Ger Inberg](https://gerinberg.com/)and [Denise Chandler](https://denisechandler.com/)
- [Adham Danaway](https://www.adhamdannaway.com/), whose portfolio website concept was simple, beautiful and many design concepts translated perfectly for the two split roles of Anny Devoy

My mentor, Medale Oluwafemi, for his invaluable guidance and feedback.

My wife, Megan Abel, whose experience as a designer and illustrator helped guide the development of the visual design concept. Statements such as ‘wow, that looks terrible, you need to change that’ and ‘that looks like a site from the early 2000’s’ were particularly helpful.












