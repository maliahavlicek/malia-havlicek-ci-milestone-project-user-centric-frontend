## Personal Portfolio Milestone Project 1
This website is for recruiters and future employers to browse the work history, professional goals, and skills of a future employee, Malia Havlicek in the role of a full stack web developer. It was designed to present a resume to recruiters as an intuitive website both on mobile devices and desktops. 

The home page provides future employers with a brief overview of my beliefs concerning software development. They can read up on my education, browse
my skill set, link to code examples, see recommendations, and link to social media profiles. This information will help provide recruiters and future employers with a feel to my personality as well as my qualifications as a fullstack web developer.

## Author
Malia Havlicek

## UX 
To best highlight a software developer's competence, a personalized portfolio website provides information similar to a standard resume with the
added bonus of being built with the skill set the candidate wishes to demonstrate experience in. It should present nicely on phones and laptops.

### Mockups
The first stage of the portfolio website was determining a design and what information to present. The following sketches were drawn:
- [About Me](https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/images/Mockups/Mockup-AboutMe.jpg)  - landing page with mission statement, education and awards
- [Experience](https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/images/Mockups/Mockup-Experience.jpg)  - provide work history summary
- [Skills](https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/images/Mockups/Mockup-Skills.jpg)  - graphs and lists highlighting skills, aptitude, and depth of knowledge
- [Navigation](https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/images/Mockups/MockUp-More.jpg)  - layout of navigation

### User Stories
From the design stage, the following user stories were created:
- <strong>Mission Statement: </strong>As a recruiter, I want to know my candidate's mission statement so I can determine if the candidate is a good fit culturally for the company I'm recruiting for.
- <strong>Education Summary: </strong>As a candidate, I want my future employers to know that I am dedicated to pursuing knowledge so they know I am not picking up coding as an ad hoc career.
- <strong>Awards and Recognition: </strong>As a candidate, I want recruiters to know that my peers and past employers thought I a good employee so that future employers know I am worthy of being hired.
- <strong>Navigation: </strong>As a website user, I want to easily and intuitively move throughout the profile both on desktop and small devices so I do not have to scroll through tons of information to find what I am looking for.
- <strong>Footer: </strong>As a candidate, I want my contact information to be readily available to recruiters and future employers so they can contact me without searching or clicking to other pages.
- <strong>Experience: </strong>As a recruiter, I want to see that a candidate has practical experience in the field I am hiring for so that I find qualified candidates fast.
- <strong>Skills: </strong>As a recruiter, I want to see the skills a candidate possesses so that I know they meet the requirements for the position I am trying to fill.
- <strong>Recommendations: </strong> As a candidate, I want to highlight the good things past co-workers have said about me so that future employers know I am a great find.


## Features
This portfolio consists of 4 distinct pages: About Me, Experience, Skills, Recommendations and a header and footer. The pages will be rendered such that they look and function well on mobile phones, tablets and laptops.

1. <strong>About Me: </strong>This is a landing page for the portfolio. It provides a first glimpse at a candidate. The mission statement provides a look at the candidate's personality and what they hope to provide to a future employer. There is an education summary section which links to the education institution's website and documents the degree  obtained and graduation date. The awards and recognition section provides a quick list highlighting past employer recognition.

![image](https://user-images.githubusercontent.com/23039742/129377856-e553e2cb-7e6e-4fc4-bead-5d2c124ce910.png)

1. <strong>Experience: </strong> This page provides a work history of the candidate as a list of positions. Each section summarizes a position held by the candidate along with the duration and a description of what the candidate did while in that role.

![image](https://user-images.githubusercontent.com/23039742/129381530-05912ef3-4528-4893-861c-23865eb5fe67.png)

1. <strong>Skills: </strong>The skills page provides insightful graphical interpretations of the candidate's skill set. It has four sections: Current Job Focus, Front End Skills, Skills Most Recently Used and Past Experience. The unique representation of skills in this manner shows the progression of skills overtime as technology changes.

![image](https://user-images.githubusercontent.com/23039742/129381604-ef059c6f-97ce-4353-833b-cbb922b0d51f.png)

1. <strong>Recommendations: </strong>The recommendations page highlights past co-workers praise from all sorts of roles. This section highlights the candidate's ability to present information highlighting their CSS proficiency. 

![image](https://user-images.githubusercontent.com/23039742/129381764-d6d5f0ed-219f-4120-a1d4-2a7155272b1a.png)

**note** full page screenshot has a bit of a quirk so sometimes there are white gaps that are truely not on the page.

1. <strong>Header: </strong>The header provides navigation links and a graphic header to represent what page the user is currently on. It is responsive and has a different presentation for small devices to ensure that important information is displayed above the page fold on small devices as well as desktops.

![image](https://user-images.githubusercontent.com/23039742/129381323-60aa01fd-f573-41c9-8814-150c34c871d2.png)


1. <strong>Footer: </strong>The footer provides consistent quick links to the candidate's email, phone and social media accounts so that recruiters do not have to navigate to contact her.

- mobile 

> ![image](https://user-images.githubusercontent.com/23039742/129381928-9a9c318e-16c0-4399-bd09-97a01004a8c4.png)

- desktop 

> ![image](https://user-images.githubusercontent.com/23039742/129382084-605ba9f1-1f59-422b-a851-7af863ad609e.png)
  

### Features Left to Implement
- <strong>Code Examples Page:</strong> Rather than a link to github, update to an individual page that includes a picture of past sites developed and links to them a well as well as code pen.
- <strong>Photo Gallery:</strong> Provide a photo gallery with work snapshots to show that candidate works hard and has fun doing it.

## Technologies Used
- [CSS](https://www.w3schools.com/w3css/default.asp) The project uses **CSS** to define DOM appearance. 
- [HTML](https://www.w3schools.com/html/default.asp) The project uses **HTML** to define DOM elements.
- [colors.co](https://coolors.co/) I used a colors.co's color pallet tool to help pick complementary colors.

## Testing

### Validation Testing
Used the following validation websites to test the code:
- [CSS Validator](https://jigsaw.w3.org/css-validator/) Note, any error associated with root: color variables were ignored.
- [HTML Validator](https://validator.w3.org/)

### Cross Browser and Cross Device Testing
For device testing, I would ideally have access to browser stack and derive a list of iOs devices and versions to test with from 
[David Smith's site](https://david-smith.org/iosversionstats/). Likewise, I would make use of stats from [android](https://developer.android.com/about/dashboards) 
to handpick android devices and versions to test with.  Then I'd test top browsers on PC's and Macs using the statistics from [w3Counter](https://www.w3counter.com/globalstats.php). 

Since I don't have a handful of devices or a proper testing tool suite at my fingertips, I'm going to rely on Chrome Dev tools and my windows PC.  

Below are the scenarios I picked to test my website:
* Windows 10, Edge
* Windows 10, Chrome
* Chrome Emulator iphone 6
* Chrome Emulator iPadAir
* Chrome Emulator Pixel 2
* Chrome Emulator Galaxy S5

### Accessibility Testing
I used the AXE chrome plugin to test the accessibility of the website. https://www.deque.com/axe/ 


### Testing Results
During testing I saw that a few of the text styles were too large for small devices. The h1.logo class, .skills-header,hero-text and .quote-author needed the most
finessing. The styling for the recommendations also required restructuring such that a two column to one column collapse had to occur at the tablet
breakpoint versus small devices. 

I also discovered that the font difference on small devices for the logo text was too low in contrast to pass accessibility testing so I adjusted the font to be darker.


## Deployment

- This site is hosted using [GitHub](https://maliahavlicek.github.io/malia-havlicek-ci-milestone-project-user-centric-frontend/) pages, deployed directly from the master branch. The deployed site will automatically update when new commits are made
to the GitHub repository.
- To run locally, you can clone this repository into the IDE of your choice by pasting <strong git clone https://github.com/maliahavlicek/malia-havlicek-ci-milestone-project-user-centric-frontend.git</strong into your
terminal.

** gitpod **
1. In terminal run `python3 -m http.server`
2. click Open Browser

## Credits

### Content
The content for this website was derived from my peronsal resume and graphics I created on googlesheets. Recommendations came from past emails, direct messages and rewards received throughout my career.

### Media
The photos used in this site were obtained as follows:
- background image saved as BlueJeanBackground  - https://wallpapersafari.com/w/V2nSAh
- graphics on skills page were created from googlesheets by Malia Havlicek.
- Picture of Malia Havlicek, taken by Malia Havlicek.
- Social media icons were found using [iconfinder](https://www.iconfinder.com/social-media-icons?price=free).

### Acknowledgements
- Color variables idea from [Daniel's post](https://codeburst.io/css-variables-explained-with-5-examples-84adaffaa5bd). This feature is in  my reset.css file.
- Small devices navigation was derived from [Mark Caron's post](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793). You can find the navigation styles in my styles.css file.
- Grid based CSS was inspired from: [Tania Rascia's pen](https://codepen.io/taniarascia/pen/rOLEGe/). You can find the grid defined in my styles.css file.
- CSS reset/breakdown was inpsired from :[Elad Shechter's post]( https://medium.com/@elad/normalize-css-or-css-reset-9d75175c5d1e)
