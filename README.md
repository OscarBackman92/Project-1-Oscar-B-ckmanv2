# The Waffle Truck
![mock up](assets/readme_images/mock-up-readme.png)
Welcome to The Waffle Truck, your ultimate destination for delicious waffles in Stockholm, Jakobsberg!

## Introduction
The Waffle Truck is a food truck based in Stockholm, Jakobsberg, specializing in serving delicious waffles for breakfast and brunch.

## Features

### Existing Features

#### Navigation Bar
![navbar mobile](assets/readme_images/navbar-mobile.png) ![navbar](assets/readme_images/navbar-larger-screen.png)
The navigation bar provides easy access to different sections of the website, including the home page, our menu, and about us page. Value it provides is accessobility on all screensizes.

#### Landing Page
The landing page features a captivating hero image and headings that introduce The Waffle Truck and its offerings.

#### Hero Image and Headings
![Hero Image](assets/readme_images/theperfectloaf_my_best_sourdough_waffles-7-1080x720.jpg)
The hero section showcases an enticing image related to waffles along with descriptive headings to attract visitors.

#### Lower Navigation
![lower nav](assets/readme_images/lower-nav.png)

* At the bottom of each page, there is a lower navigation section providing contact information, opening hours, and a newsletter subscription form, and updates on today's truck location. All with Aria-labels for screenreaders.


#### Footer
![Socials bar](assets/readme_images/social-bar.png)

- The footer contains icons as links to all our social media websites, and will open in new tabs as you click on them. And for the visually impaired waffle fanatics using a screenreader the aria-labels will help with navigation.


## Testing

### Responsiveness

All pages have been tested to ensure responsiveness on screen from 320px to 1920px

Steps i went through for testing

1. Open browser and head over to https://oscarbackman92.github.io/Project-1-Oscar-B-ckmanv2/
2. Open Google devtools (right click inspect)
3. Set dimensions to responsive and width to 320px
4. Zoom 50%
5. Click and drag window edges to max width

Expected outcome:

The site is responsive on all screensizes. Hero image not being pixelated/blurry
Some horizontal is present and that's the idea.

Result:

As expected. The website is responsive to screensizes and images is working and elements is not compromized.

Tried the website on and Iphone 13 and Iphone 11 with no issues.


### Accesibility

[Wave Accessibility](https://wave.webaim.org/) tool was used in the later stages of development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused on accesibility everyone

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
- Color that enhance the elements on the website and instigates a hunger for waffels.
- That all headings have apporopiate and meaningfull content
- HTML page lang has been set
- Aria labels been implemented correctly and appropriately
- That there is an alt text to images on the website
- WCAG 2.1 Coding best practices being followed

### Lighthouse Testing

![lighthouse](assets/readme_images/lighthouse-test.png)
## Deployment

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully. 

The live link can be found here - https://oscarbackman92.github.io/Project-1-Oscar-B-ckmanv2

### Clone the Repository Code Locally

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now of been cloned on your local machine for use.


## Credits

- My Wife Josefine for the contents in About us and items in our-menu.
- Daisy_mentor for tips and tricks.
- [Gareth Mc](https://github.com/Gareth-McGirr/tacos-travels) for readme inspiration.
- CI for boilerplate and basic structure.


### Content
- Text content was written by [Oscar Bäckman and Josefine Bäckman].

### Media
- Images and videos were sourced from [Image Source](https://www.theperfectloaf.com/my-best-sourdough-waffles/).

### Code
- HTML and CSS code were developed by [Oscar Bäckman] based on design requirements.
- CI for Boilerplate and structure.

### Focus Group
- Feedback and suggestions from focus group participants contributed to the refinement of the website design and features. None other than Oscar Bäckman and Josefine Bäckman and our craving for waffles.
