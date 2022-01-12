# HOME PHITNESS

(Developer: Jae Phillips)

![Responsive mockup image](docs/features/amiresponsive.png)

> [Live Page](https://jusjae.github.io/CI_MS1_HomePhitness)

## Table of Content

- [HOME PHITNESS](#home-phitness)
  - [Table of Content](#table-of-content)
  - [User Experience (UX)](#user-experience-ux)
  - [Project Goals](#project-goals)
    - [First Time User Goals](#first-time-user-goals)
    - [User stories](#user-stories)
      - [First-Time User](#first-time-user)
      - [Returning User](#returning-user)
      - [Frequent User](#frequent-user)
  - [Design](#design)
    - [Typography](#typography)
    - [Colour Scheme](#colour-scheme)
      - [_Palette_](#palette)
  - [Wireframes](#wireframes)
    - [Web view](#web-view)
    - [Mobile view](#mobile-view)
  - [Features](#features)
    - [Logo and Navigation Bar](#logo-and-navigation-bar)
    - [Footer](#footer)
    - [About Us](#about-us)
    - [Workout categories](#workout-categories)
    - [Exercise cards](#exercise-cards)
    - [Contact Form](#contact-form)
    - [Information](#information)
  - [Technologies Used](#technologies-used)
  - [Testing](#testing)
  - [User Feedback](#user-feedback)
    - [User Feedback Example](#user-feedback-example)
    - [Features Testing](#features-testing)
  - [Future Features](#future-features)
  - [Validation Testing](#validation-testing)
    - [W3C Jigsaw CSS](#w3c-jigsaw-css)
    - [W3C HTML Validator](#w3c-html-validator)
    - [WAVE Web Accessibility Evaluation Tool](#wave-web-accessibility-evaluation-tool)
    - [A11y Color contrast Accessibility Validator](#a11y-color-contrast-accessibility-validator)
  - [Deployment](#deployment)
  - [Credits](#credits)
    - [Images & Videos from Unsplash and Pexels](#images--videos-from-unsplash-and-pexels)
    - [Exercise Information](#exercise-information)
  - [Acknowledgements](#acknowledgements)

## User Experience (UX)

---
---

## Project Goals

---

### First Time User Goals

When the user initially enters the site they are greeted with an clearly labelled navigation menu  to all pages. This is followed by a welcoming hero image with text overlay that includes the slogan that explains the name and objective if site.

There is then a call to action button to "Start…".  
At this point the user can click the call to action button or continue scrolling down, both options will take the user to information the exercises that they will be able to get information from the site.

The user will find three cards that each link to the exercise section it reflects.
This is designed to help the user have easy access to the exercise content.

The site has been designed to have styling and usage ease and this is represented through
The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

The user has access to a call to action button at the bottom of the pages barring the home page, where it located below the hero image.
This helps the user move freely throughout the site and not feel restrained to just that page.

When a user complete the user form on the contact page they will be returned to the home page.

On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

### User stories

---
 A person who is interested in getting in shape at home, but does not know what type of workout they would like to do. They would come to this website to find a workout to do at home and be able to get in contact with a personal trainer to book in the next remote workout session.

#### First-Time User

As a first time user:

1. I want to know what exercises I can get support to do at home to improve my fitness
2. I want to know the different exercise categories and workouts
3. I want to easily be able to find out any further information and services offered.
4. want to be able to easily be able to navigate throughout the site to find content
5. I want to be able to contact you with any further questions I may have on the exercises or workouts.
6. I want to be able to find you on social media in order to do further research on the company to determine legitimacy and following, in addition to the desire to want to become part of the community.

#### Returning User

As a returning user:

7. I want to see the exercises available to complete at home
8. I want to know what exercises are new
9. I want to know when the new exercises re being released
10. I want to find Home Phitness on social media
11. I want to leave a message or suggestion to the company
12. I want to know who is putting together the workouts

#### Frequent User

As a frequent user:

13. I want to log on to find out what new exercises have been released for the month.
14. I want to get in contact to recommend exercises/ workouts.
15. I want to get in contact with you directly with a query.

## Design

---

### Typography

Exo | Lato | Oswald

The fonts that were used throughout the site are 'Exo', 'Lato' and 'Oswald'.  

Exo was used for heading and sub headings as it has a bold standout style that looks digital but welcoming to reflect the digital workout tool.
'Lato' was used for buttons and call to action and menu for its ease of readability.
Oswald was used for the body of text.

### Colour Scheme

#### _Palette_

![Colour scheme](./docs/palette.png)

I used a simple black and white base to the site with vibrant yellow  and blue accents to match the brand theme.
These colours contrast very well for users who may struggle colour differentiation.
The colours also allow for dark mode filters to easily changed the colours the user.

The exercise cards are colours based on their category, using red for 'Burn'exercises, yellow for navigation bar menu and buttons and the 'Build' exercises and blue for 'Stretch' exercises and active menu tab when dropdown selected.

## Wireframes

Wireframes were designed at the start of this project to map out the site but the site has slightly changed since it its original conception to simplify the layout and add different elements and remove unnecessary elements for current features such as a music player.

In addition to not having originally planned to have a custom 404 page but adding it in during the project.

### Web view

<details>
<summary>Web View Wireframes</summary>

Home Page
![Wireframe Home Web View](./docs/wireframes/wireframe-web_view.png)

About Us Page
![Wireframe About Web](./docs/wireframes/wireframe-about_us.png)

Exercises Page
![Wireframe Exercises Web](./docs/wireframes/wireframe-exercises.png)

Contact Us Page
![Wireframe Contact Web](./docs/wireframes/wireframe-contact_us.png)

</details>

<br>

### Mobile view

<details>
<summary>Mobile View Wireframes</summary>

Mobile Home Page
![Wireframe Home Mobile](./docs/wireframes/wireframe-mobile_view.png)

Mobile About Us Page
![Wireframe About Mobile](./docs/wireframes/wireframe-m-about_us.png)

Mobile Exercises Page
![Wireframe Exercises Mobile](./docs/wireframes/wireframe-m-exercises.png)

Mobile Contact Us Page
![Wireframe Contact Mobile](./docs/wireframes/wireframe-m-contact_us.png)

</details>

<br>

## Features

---------
---------

The page consists of four pages and nine features

### Logo and Navigation Bar

- The navbar featured on all pages is fully responsive and changes to a toggler (hamburger menu) on smaller screens and includes
links to the Homepage, About page, Exercises and Contact us page
- The link for the page the user is currently on is highlighted and bold text on active page tab.

<details>
<summary>Navbar Toggle Dropdown Images</summary>

![Navbar web](docs/features/f-menu-dropdown.png)

![Navbar mobile](docs/features/f-menu-dropdown-m.png)

</details>
<br>

### Footer

- Featured on all five pages and consists of Home Phitness slogan, contact information and social media link and copyright.

<details>
<summary>Footer Image</summary>

![Footer](docs/features/f-footer.png)

</details>
<br>

### About Us

- Gives a description of the hone workout company and the trainer that provides the exercises.
  
<details>
<summary>About Us Image</summary>

![About Us](docs/features/f-about.png)

</details>

### Workout categories

- Gives an overview of the different workout categories available on the site, which have ben broken down in to fat burning, building muscles and stretches.

<details>
<summary>Workout Categories Image</summary>

![Workout Categories](docs/features/f-workouts.png)

</details>

### Exercise cards

- Provides the information on what the exercise is and how long the user should be doing the exercise for, giving them a video hint or picture of exercise.

<details>
<summary>Exercise Card Image</summary>

![Exercise Card](docs/features/f-exercise-card.png)

</details>

### Contact Form

- A way for user to get in contact with the company in order find out more information or get questions answered.

<details>
<summary>Contact Form Image</summary>

![Contact Form](docs/features/f-contact-form.png)

</details>

### Information

- Provides the user with information about the company including phone number, email and social media links.

-
<details>
<summary>Contact Info Image</summary>

![Information](docs/features/f-contact-info.png)

</details>
<br>

## Technologies Used

---

- Bootstrap v4.2.1:
    Bootstrap has been used for overall responsiveness of the website, and for the layout to include navigation, cards, and footer within the relevant sections of the website.

- MD Bootstrap 4:
    MD Bootstrap was used to get help in designing the footer and responsive content throughout the project.

- Visual Studio Code/GitPod:
 I used GitPod/Visual Studio Code as the IDE application with Git for version control of this project.

- GitHub:
    GitHub has been used to create a repository to host the project and receive updated commits from Visual Studio Code.

- Balsamiq:
    I used Balsamiq to create the wireframes for the site to help me with the basic structure the layout and have a guide to design the project with.

- Coolors:
    This online colour palette selector tool was used to see what colour would work well on the site.

- Canva:
  Used to design the logo and 404 error page image.

- Pexels 
    Pexels was used throughout the site as they are copyright and royalty-free stock images and videos. 

- Google Fonts:
    The fonts where selected from and imported to style the text on the site.

- Font Awesome:
    Font Awesome was used to apply icons in the Exercises page and Footer section.

- W3C HTML Validation Service:
    The W3C HTML Validation Service was used as a validation tool to check for issues within the project's HTML documents code.

- W3C CSS Validation Service:
    The W3C HTML Validation Service was used as a validation tool to check for issues within the project's CSS document code.

- WAVE Web AIM Accessibility Evaluation Tool:
    This tool was used to test errors in accessibility such as the color contrast, ARIA for this project.

- A11Y Color Contrast Accessibility Validator:
    This online checker tool was used to check the contrast level opf the content of each page.

- Image Compressor
    This online tool was used to compress the image file to optimize the sites loading time.

- Am I Responsive:
    Am I Responsive was used to create the header image for the README file to show the site in its responsive format.

## Testing

---
---
The 'Home Phitness' website was tested through on the following browsers:

- Firefox
- Google Chrome
- Safari
- Opera

## User Feedback

---
I asked my peers to review the site when it was completed to give me their honest feedback, in order to make adjustments to the site based on real-time feedback.

### User Feedback Example

>"Home Phitness is a really straight forward and clear to use.
I kind of struggle using websites as i have dyslexia sometimes find it quite difficult to read. Home Phitness  did it for me i was really intrigued at how clear everything was. I found that the about us page was very clear and straight to the point giving me the options to select what i’m interested in and sending it through.
My favourite part of the website was that you can find your own comfort of exercising at home this highlighted everything for me and i was more drawn in as finding the time to go gym is really long after a long day at work and having to travel.
I loved how  the “exercise” and  “build”  and “stretch” sections, demonstrated how to do the exercise  followed by pictures and small video clips of how to do it, also the fact it had minimal writing and just set out how many to do and for how long really encouraged me.
Overall fantastic website and look forward to seeing more workouts to add to my routine. I will definitely recommend to anyone who wants to start a journey in fitness at home."

### Features Testing

I have looked at the features that the site offers and how it works in anticipation of user wants and expectations.

| Feature                         | User Story     | Expected Outcome                                        | Actual Outcome                                          |
|-------------------------------- |------------    |-------------------------------------------------------- |-------------------------------------------------------- |
| Navigation bar/Toggle dropdown  | 4, 13, 14      | To navigate through the sites pages easily              | Feature worked as expected for user                     |
| Workout Category Cards          | 1, 2, 6, 7, 13 | Locating desired workout category                       | Feature worked as expected for user                     |
| Exercise Cards                  | 3, 6, 7        | To know what exercise, how to do it and how long for.   | Feature needed further detail on how to do it for user  |
| Contact Form                    | 5, 10          | To be able to get in contact with company               | Feature worked as expected for user                     |
| Footer                          | 5, 6           | To scroll to the bottom of any page to find the footer  | Feature worked as expected for user                     |
| About Us                        | 3, 9, 12       | To gain insight on the company                          | Feature worked as expected for user                     |
| Contact Information             | 6, 10          | Find details to be able to get in contact directly      | Feature worked as expected for user                     |

## Future Features

---

- Exercise cards have instructions on exercise and all cards to have videos where possible - User Story: 3, 6, 7
- Sign up form feature to join a community newsletter to find out when new exercises are released - User Story: 8, 9, 13

## Validation Testing

---
The website was tested through W3C validator for HTML and CSS, WAVE Web AIM Accessibility Tool.
I ran the site through the validation tools to check for errors whilst creating the project and to fix them within the code.
The site was found ot have no errors in either HTML or CSS when using the validation tools as well as no contrast issues as shown when using the checker.

<details>
<summary>W3C Validation</summary>

### W3C Jigsaw CSS

![Jigsaw CSS](./docs/validation/jigsaw-css.png)

### W3C HTML Validator

Home
![W3C HTML Homepage](./docs/validation/w3c-html-home.png)

About Us
![W3C HTML About](./docs/validation/w3c-html-about.png)

Exercises
![W3C HTML Exercises](./docs/validation/w3c-html-exercises.png)

Contact Us
![W3C HTML Contact](./docs/validation/w3c-html-contact.png)

404
![W3C HTML 404](./docs/validation/w3c-html-404.png)

</details>

<details>
<summary>WAVE Web AIM </summary>

### WAVE Web Accessibility Evaluation Tool

Home
![WebAim Homepage](./docs/validation/webaim-home.png)

About Us
![WebAim About](./docs/validation/webaim-about.png)

Exercises
![WebAim Exercises](./docs/validation/webaim-exercises.png)

Contact Us
![WebAim Contact](./docs/validation/webaim-contact.png)

404
![WebAim 404](./docs/validation/webaim-404.png)

</details>

<details>
<summary>Color Contrast </summary>

### A11y Color contrast Accessibility Validator

Home
![Color Contrast Homepage](./docs/validation/color-contrast.png)

Exercises
![Color Contrast Exercises](./docs/validation/color-contrast-exercises.png)

</details>

<br>

## Deployment

---

The website has been deployed through Github Pages using the steps below:

1. Click on your repository Settings
2. Scroll to Pages Tab on left hand and select
3. Select source as "Branch: master"
4. Refresh page
5. Upon refresh banner states "Your site is published at <https://jusjae.github.io/CI_MS1_HomePhitness/>"
6. Test the deployment works by clicking on link.

![GitHub Deployment](./docs/validation/deployment-settings-bar.png)

The following steps will guide you to clone the repository:

1. Go to the GitHub repository
2. Locate the Code button above the list of files and click it
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open the CLI
5. Change the current working directory to where you wnt the cloned directory to be located
6. Type `git clone` and paste the URL from the clipboard `$ git clone <https://github.com/jusjae/CI_MS1_Phitness>`.
7.Press 'Enter' to create your locally cloned repository.

You can create a 'fork' of the repository by following these steps:

1. Go to the GitHub repository
2. Click on Fork button in upper right hand corner
3. This will create a copy of that repository within your Github

## Credits

---

### Images & Videos from Unsplash and Pexels

[Pexels](https://www.pexels.com/) 
  - 'MART Production' from their 'Workout at Home' collection
  - 'Thirdman' for his 'Lifestyle' collection.


### Exercise Information

  - Exercise card information was designed calculated by experienced Personal Trainer (Me!)

## Acknowledgements

---
Thanks to the following people for your help and support in completing this site for the Milestone Project 1 in completion of the Web Application Developmental Diploma delivered by the Code Institute.

- Mentor - Mo
- Slack CI Community
- Code Institute Staff

_Home Phitness is a fabricated company for the purposes of this project._
