# Love 2 Cook
Developed by: Conor Gorman
Live site: https://cgplusplus.github.io/CI_MSP1/

## Project Goals
### End-User Goals
•	Finding recipes that can be followed easily
•	Find a website that outlines ingredients as well as instructions in a step-by-step format
•	Variety in recipes available on site
•	Ability to contact site owners and request recipes not on site currently
### Site-Owner Goals
•	Provide easy to follow recipes for end-users to use as they require
•	Ensure users come back to try other recipes having tried their first one
•	Variety in what recipes are offered to users.
•	Community interaction in the form of comments/questions/suggestions

## User Experience
### Target Audience
•	People who use recipe websites
•	People who may want healthy alternatives to what they typically cook
•	People who are looking to budget their spending, looking for recipes with cost attached
•	People looking to learn to cook with easy to follow guides
### End-User Expectations
•	Recipes are easy to read and straightforward
•	Website layout is intuitive easy to navigate
•	Links to social media for further connecting
•	Contacting author possible

## User Stories
### First Time User
•	As a first-time User, I want to understand what Love 2 Cook has to offer
•	As a first-time User, I want to find easy-to-follow recipes that I can reuse
•	As a first-time User, I want to be able to intuitively navigate the website and find what I am looking for
•	As a first-time User, if I can’t find what I need I may want to contact the team involved and query on its availability

### Returning User
•	As a returning User, I want to be able to re-use recipes from before
•	As a returning User, I want to have variety in what recipes I can use
•	As a returning User, I want to be able to contact the team involved 
•	As a returning User, I would like the navigation of the website to remain the same 
### Site Owner
•	As Site Owner, I want User to return to use the site
•	As Site Owner, I want Users to be able to intuitively navigate the website without needing to contact us.
•	As Site Owner, I would like to have communication from End-Users on anything relating to their website experience
•	As Site Owner, I want Users to feel comfortable in reading the recipes

## Design
### Wireframes

<details><summary>Home</summary>
<image src="/assets/docs/home.PNG">
</details> 

<details><summary>Contact</summary>
<image src="/assets/docs/contact.PNG">
</details> 

<details><summary>Recipes</summary>
<image src="/assets/docs/Recipes.PNG">
</details> 
 
<details><summary>Individual Recipes</summary>
<image src="/assets/docs/individual-recipe.PNG">
</details> 
 
<details><summary>About</summary>
<image src="/assets/docs/about.PNG">
</details> 
 
### Structure
The layout of the website is supposed to be familiar and intuitive. Navigation links are set to the top right, where they stand out against the background and the title and logo are to the top right. From the wireframes above, there are 5 pages, although the About page will be merged into the index as I don’t believe it needs its own page. This will leave 4 base pages, with the individual recipe page having the same structure, just different content for each recipe.
1.	The home page has a large hero image and will have information about the website below this in its own section
2.	The recipes page will be the main area where all accessible recipes will be hosted
3.	Each recipe will have its own individual page, consisting of an ingredients list and a step-by-step walkthrough of the recipe
4.	The contact page will have a form where Users can add comments/questions and also suggest recipes that are not currently on the site.
5.	There is also a confirmation page on Submit of a Contact form. This page has got 2 lines of text only.

### Website Layout
The website layout needed to be simple yet contain all the information required.
In order to avoid long pages, the recipes page was split into 3 columns allowing for more utilisation of the available space.
On the individual recipes page, having the ingredients and instructions side-by-side helped to keep all relevant information close together.

### Fonts
Fonts were imported from Google fonts and the 2 used are Open Sans Condensed and Zen Maru Gothic. Both of these fonts are easily read and this was an important consideration for end-users.

## Site Features
### Navigation Bar
•	The navigation bar is on all pages for continuity across the site
•	It is easily read and when user is on either of the 3 main pages, the page will be highlighted.
<details><summary>Navigation Bar</summary>
<image src="/workspace/CI_MSP1/assets/docs/nav-bar.PNG">
</details> 

### Hero Image
•	This image is to highlight that the website is dedicated to food. 
•	There is a Hero overlay that summarises what the website offers in a few lines of text
<details><summary>Hero Image</summary>
<image src="/workspace/CI_MSP1/assets/docs/hero-image.PNG">
</details> 

### Why Us?
•	Sitting below the Hero image, this section highlights what the website offers
•	It gives a brief insight into the ethos behind Love 2 Cook and what Users can expect
<details><summary>Why Us?</summary>
<image src="/workspace/CI_MSP1/assets/docs/why-us.PNG">
</details> 

### Footer
•	The Footer sits at the bottom of each page
•	It contains clickable links to all of the Social sites
 <details><summary>Footer</summary>
<image src="/workspace/CI_MSP1/assets/docs/footer.PNG">
</details> 

### Recipes
•	Recipes page contains a 3 column layout
•	Each column has recipe cards that link out to each individual recipe
•	There is a short blurb on what the recipe is and there is a recipe cost under the image of each recipe
<details><summary>Recipes Main</summary>
<image src="/workspace/CI_MSP1/assets/docs/recipes-main.PNG">
</details> 

### Individual Recipes
•	Each recipe page is simple and to the point
•	There is an image on the right side and to the left of this is the recipe
•	The recipe consists of an ingredients list and a step-by-step guide on how to cook the recipe
<details><summary>Individual Recipes</summary>
<image src="/workspace/CI_MSP1/assets/docs/individual-recipes.PNG">
</details> 
 
### Contact
•	The Contact page is split vertically into two.
•	The left has a text blub on contacting Love 2 Cook and the right side contains a contact form
•	There are some mandatory fields and a test box at the bottom for whatever needs communicating.
•	Also there is a radio button to determine what the contact is for
<details><summary>Contact</summary>
<image src="/workspace/CI_MSP1/assets/docs/contact-form.PNG">
</details> 
 
### Validation
•	Finally, there is a Validation page, that appears once the Submit button is clicked.
•	This is just to provide feedback to the User that their form has been sent.
 <details><summary>Validation</summary>
<image src="/workspace/CI_MSP1/assets/docs/validation.PNG">
</details>

## Technologies Utilised
### Languages
•	HTML
•	CSS
### Tools 
•	Git
•	Github
•	Gitpod
•	Font Awesome v5.15
•	Google Fonts
•	Balsamiq

## Validation
### HTML Validation
The W3C Nu Html Checker was used to validate all of the HTML pages. There were 2 errors over the course of creating the site, both which have been solved.
There is also one warning relating to the use of <h1> tags, but this is a design choice as the text in the <h1> is the only text on the page (validation.html).

### From HTML Validator:
•	Error: Element ul not allowed as child of element span in this context. (Suppressing further errors from this subtree.)
Solution: Changed span to div

•	Error: Element hr not allowed as child of element h2 in this context.
Solution: placed hr outside of h2 element tags
CSS Validation
The W3C CSS Validation Service was used to validate the CSS for all pages. As the CSS is all contained on one stylesheet, only one validation was necessary. There was one error over the course of creating the site, which has since been resolved.
From CSS validator:
•	Error: Sorry! We found the following errors (1)
URI : https://8000-amaranth-stoat-xdo7xikr.ws-eu17.gitpod.io/assets/css/style.css
32 		Value Error : letter-spacing 2% is not a letter-spacing value : 2% 
Solution: changed from % to px

### Performance
Google Lighthouse in Chrome Developer Tools was used to check the website performance indicators. The pages performance readings are below:

<details><summary>Home Performance</summary>
<image src="/workspace/CI_MSP1/assets/docs/home-performance.PNG">
</details>

<details><summary>Recipes</summary>
<image src="/workspace/CI_MSP1/assets/docs/recipes-performance.PNG">
</details>
 
 <details><summary>Contact Performance</summary>
<image src="/workspace/CI_MSP1/assets/docs/contact-performance.PNG">
</details>
 

<details><summary>Individual Recipes</summary>
<image src="/workspace/CI_MSP1/assets/docs/individual-recipes-performance.PNG">
</details>
 

## Issues
•	From the beginning I was under time restraints and due to personal issues this got exacerbated.
•	This did not leave enough time for testing and responsive coding meaning it had to be excluded. The site will work on PC/Laptop browser, but is not responsive for Mobile and Tablet
•	Smaller issues include: 
o	Need to add extra permissions to Gitpod for GitHUB for Write access.
o	Header Menu was back to front - put these elements within a span element.
 
## Deployment

This website was deployed using GitHub Pages following these steps:
•	In the GitHub repository click on the settings tab at the top
•	On the left menu scroll down to ‘Pages’
•	For the source select 'main'. Click Save
•	The page will refresh and display a highlighted section with a message stating: "Your website is published at https://cgplusplus.github.io/CI_MSP1/“

The repository can be cloned by following the below steps:
•	Navigate  to the GitHub repository
•	Click on 'Code' at the top of the repository
•	Select to clone either HTML, SSH or GitHub CLI
•	Go to the working directory you wish to work from
•	Go to Git Bash
•	Type git clone and paste the URL from your clipboard ($ git clone https://github.com/USERNAME/REPOSITORY)
•	Press enter to create your clone

## Acknowledgements
### Media
•	Hero Image: https://www.knorr.com/content/dam/unilever/global/recipe_image/125/12527/125279-default.jpg/_jcr_content/renditions/cq5dam.web.1600.1200.jpeg 

•	Logo Image: https://image.shutterstock.com/image-vector/pan-icon-vector-design-template-260nw-1440283388.jpg

•	Circle-cover-bg image: https://static01.nyt.com/images/2017/09/25/dining/bonebrothchickenstock/bonebrothchickenstock-articleLarge.jpg 

•	Spaghetti Bolognese Image: https://images.immediate.co.uk/production/volatile/sites/30/2017/10/ultimate-spaghetti-bolognese-41bb99a.jpg?quality=90&resize=504,458?quality=90&resize=504,458 

•	Chicken Fajitas Image: https://www.thespruceeats.com/thmb/rrx0sLgbOG71fez9fMlnvcxrfgs=/4600x3067/filters:fill(auto,1)/easy-fajitas-recipe-3052908-hero-01-e4dc09dd6b28488191a9ddf700c7441b.jpg 

•	Icons: Font Awesome - https://fontawesome.com/ 

### Code
•	Code Institute - Love Running project: While creating this website, this tutorial served as an inspiration on some aspects, so there will be some similarities with this project.
