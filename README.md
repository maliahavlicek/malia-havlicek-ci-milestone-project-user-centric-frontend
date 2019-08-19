# User Centric Frontend Milestone Project
This website was built as part of my program with ACC's <a href="https://courses.codeinstitute.net/program/FullstackWebDeveloper" target="_blank">Fullstack Web Developer</a>
course in partnership with Code Institute.

You can check out the published version of this project <a href="https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/" target="_blank">here.</a>

## Author
Malia Havlicek ![Picture of Malia, a talented and hopeful web developer.](images/malia.jpg)

## Project Description
This project was created in order to highlight Malia's newly revamped skills with HTML and CSS. 

The project is aimed at meeting these core requirements:
1. <strong>Demonstrated use of the technologies taught:</strong> Write custom HTML5 and CSS3 code to create a website of at least 3 pages, or (if using a single scrolling page), at least 3 separate page areas.
1. <strong>Structure:</strong> Incorporate a main navigation menu and structured layout (you might want to use Bootstrap to accomplish this).
1. <strong> Documentation:</strong> Write a README.md file for your project that explains what the project does and the value that it provides to its users.
1. <strong>Version Control:</strong> Use Git & GitHub for version control.
1. <strong>Attribution:</strong> Maintain clear separation between code written by you and code from external sources (e.g. libraries or tutorials). Attribute any code from external sources to its source via comments above the code and (for larger dependencies) in the README.
1. <strong>Deployment:</strong> Deploy the final version of your code to a hosting platform such as GitHub Pages.

## Technology
This project was written in HTML & CSS using Cloud9 hosted by AWS. GitHub was used to manage the code and is currently hosted on GitHub pages.
The code repository can be found at <a href="https://github.com/maliahavlicek/malia-havlicek-ci-milestone-project-user-centric-frontend">https://github.com/maliahavlicek/malia-havlicek-ci-milestone-project-user-centric-frontend</a> 

### CSS Philosophy
Since I have worled with Bootstrap in the past, I decided I should really learn more about lighter weight solutions. This project doesn't require all the dialog boxes or even the 4 breakpoints of bootstrap so I'm going to try 
to make a light weight grid solution so I can better understand grid and flexbox. I broke my CSS down into 3 files:

- <strong>colors.css: </strong> Color theory is not me. I know I end up swapping colors often so I decided it would be best to define these in one spot and have the CSS refer to them. I'm hoping this will save me a lot of refactoring. I got the idea from https://codeburst.io/css-variables-explained-with-5-examples-84adaffaa5bd. I used https://coolors.co/ to help find complementary colors.
- <strong>grid.css: </strong> I need responsive CSS and I like the grid stuff so I'm trying a minimal setup, focusing on naming the classes in a logical manner and using media queries when needed to define breakpoints between desktop and small devices. I looked at https://codepen.io/taniarascia/pen/rOLEGe/ and 
- <strong>styles.css: </strong> Houses my css for the pages, more like your traditional css file.

## Navigation for small devices
The small devices navigation was derived from [Mark Caron's post](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793)

### Browser Testing
For device testing, I would ideally have access to browser stack and use sites from [David Smith's site](https://david-smith.org/iosversionstats/) to determine a list of what devices and iOS versions to test with. Likewise, 
I'd also use stats from [android](https://developer.android.com/about/dashboards) to handpick android devices.  Then I'd test top browsers on PC's and Macs. Since I don't have a handful of devices or a proper testing tool,

Without corporate dollars to fund testing initiatives, I'm going to rely on Chrome Dev tools and my windows PC.  Below are the scenarios I picked to test my website:

- These are the scenarios I tested:
    * Windows 10, Edge
    * Windows 10, Chrome
    * Chrome Emulator iphone 6
    * Chrome Emulator iPadAir
    * Chrome Emulator Pixel 2
    * Chrome Emulator Galaxy S5

