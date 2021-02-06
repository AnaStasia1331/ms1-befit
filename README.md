## Contents
- [Befit gym website](#befit-gym-website)
- [UX](#ux)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)


# Befit gym website
Befit gym website is a responsive web application built using HTML and CSS. It was created to demonstrate my front-end skills for Milestone Project 1 of Code Institute’s Full Stack Developer course.

![screen shots on various devices](assets/images/readme-images/amIResponsive.JPG)

# UX

## Who is this website for?
The target audience are gym members or potential members.

## What it is that they want to achieve?
There are 2 main purposes for visiting the website:
- learn more about the gym and its service
- be able to sign up for one of the options the gym offers.

## How does the project fulfil the users’ needs?
By providing all necessary information and features. Implemented user requirements are listed below in the User Stories section.

## Wireframes
Before starting the actual development, the [wireframes](https://github.com/AnaStasia1331/ms1-befit/tree/master/assets/images/readme-images/befit-wireframes.pdf) were created using Balsamiq tool. They give an initial idea of how the structure and content for the Home and Timetable pages would look like.

## User Stories 
As a website user, I want to:

1. navigate throughout the gym site with intuitive web design and clearly defined main sections.
2. learn about gym's purpose/goals and main features.
3. familiar with the activities the gym offers.
4. be aware of prices asked for the gym offers.
5. be able to sign up for gym membership or just a single visit.
6. be able to look up the schedule of the group classes.
7. know about the gym working hours, contact information and location.
8. access the gym's social media links so that I can see their followings and subscribe to the news.  
9. be able to come back to the Home page from any other website page.
10. use the website on mobile, tablet or desktop with equally good experience on all devices.
11. be able to understand the content of the site using a screen reader.
12. the website pages are loaded without significant delays.

# Technologies Used

The below list includes all of the languages, frameworks, tools, learning platforms and stock image websites I have used to construct this project. 

- [HTML](https://en.wikipedia.org/wiki/HTML5)
    - The project used **HTML** to structure the web pages and its content.
- [CSS](https://en.wikipedia.org/wiki/CSS)
    - used to style the website.
- [Bootstrap 4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - used Bootstrap components to design the responsive website faster.
- [Git](https://git-scm.com/)
    - used as a version control system that makes it easier to track changes to files.
- [GitHub](https://github.com/)
    - used as a web-based platform to store and share the project.
- [Gitpod](https://www.gitpod.io/)
    - used as a cloud-based integrated developer environment.
- [Font Awesome](https://fontawesome.com/)
    - used to add icons on the web pages.
- [Google fonts](https://fonts.google.com/)
    - used to import 'Montserrat' font.
- [Balsamiq](https://balsamiq.com/wireframes/)
    - used to create the wireframes before writing any code.
- [Unsplash](https://unsplash.com/s/photos/gym)
    - used to get free high resolution photos for the project.
- [Photopea](https://www.photopea.com/)
    - used as an online photo editor to make the Bitfit logo.
- [ColorPick Eyedropper](https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg)
    - a Chrome plugin that was used to get a desired color code from web pages.
- [Chrome dev tools](https://developers.google.com/web/tools/chrome-devtools)
    - used to debug issues, modify the pages on-the-fly, test responsiveness.
- [Freepik](https://www.freepik.com/free-icon/dumbbell_729503.htm)
    - used to find and insert the dumbell image in the head title.
- [Stack Overflow](https://stackoverflow.com/)
    - used to find answers to tough coding questions.
- [CSS Divider Examples](https://blog.avada.io/css/dividers/)
    - took the divider example called 'FreeCodeCamp style dividing line' by Jeffrey thomas and restyled it to fit my site design idea.
- [Code Institute learning platform](https://codeinstitute.net/)
    - used to revise the theory of CSS/HTML/User Centric Frontend Development.
- [W3schools](https://www.w3schools.com/)
    - used to revise the theory of CSS/HTML and find solutions for code issues.

# Testing

Testing environments:
- *Laptop HP ENVY x360 Convertible 15-cn0xxx*, 1920x1080-pixel screen resolution, Google Chrome & Firefox browsers.
- *Iphone XR* with 1792 x 828-pixel screen resolution, Safari browser.

| Test Name                                               | Test Steps                                                                                                                                                                                                                       | Expected Result                                                                                                                                                                                                                                                                                                            | Actual Result | Test Evidence |
|---------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------|
| UI testing. Home page.                                  | 1. As a laptop user navigate to the website Home page.                                                                                                                                                                           | 1. The website is opened on the Home page with the following main parts displayed: navigation bar with the logo and links, the hero image, About Us, Gym Offers, Membership Options sections, Sign Up form, footer. UI doesn't look broken: stretched/shrunk/overlapped.                                                   | PASS          |               |
|                                                         | 2. As a mobile user navigate to the website Home page.                                                                                                                                                                           | 2. All UI elements mentioned in the expected result of step 1 are also visible on the mobile device, however they can be resized/reorganized on the page to fit the mobile screen resolution. The navigation links are hidden and navbar toggler (button) is shown instead. The images from Gym Offers section are hidden. | PASS          |               |
| UI testing. Timetable page.                             | 1. As a laptop user navigate to the website Timetable page.                                                                                                                                                                      | 1. The website is opened on the Timetable page displaying the navigation, gym timetable, footer. UI doesn't look broken: stretched/shrunk/overlapped.                                                                                                                                                                      | PASS          |               |
|                                                         | 2. As a mobile user navigate to the website Timetable page.                                                                                                                                                                      | 2. All UI elements mentioned in the expected result of step 1 are also available on the mobile device, however they can be resized/reorganized on the page. The navigation links are hidden and navbar toggler (button) is shown instead. The table shows partially.                                                       | PASS          |               |
| Test the website links.                                 | 1. Click the About Us link in the nav bar: a) from the Home page and b) from the Timetable page.                                                                                                                                 | 1. User user is redirected to the Above Us section.                                                                                                                                                                                                                                                                        | PASS          |               |
|                                                         | 2. Click the Gym Offers link in the nav bar a) from the Home page and b) from the Timetable page.                                                                                                                                | 2. User user is redirected to the Gym Offers section.                                                                                                                                                                                                                                                                      | PASS          |               |
|                                                         | 3. Click the Prices link in the nav bar: a) from the Home page and b) from the Timetable page.                                                                                                                                   | 3. User is redirected to the Membership Options section.                                                                                                                                                                                                                                                                   | PASS          |               |
|                                                         | 4. Click the Sign Up link from the a) navbar of the Home page b) navbar of the Timetable page c) About Us section d) Group classes paragraph of the Gym Offers section e) Personal Training paragraph of the Gym Offers section. | 4. User is brought to the Sign Up form.                                                                                                                                                                                                                                                                                    | PASS          |               |
|                                                         | 5. Click the Timetable link from the a) navbar of the Home page b) navbar of the Timetable page c) Group classes paragraph of the Gym Offers section.                                                                            | 5. a) and c) User is brought to the Timetable page. b) The page is reloaded.                                                                                                                                                                                                                                               | PASS          |               |
|                                                         | 6. Test the Home page link a) from the Timetable page by pressing Befit logo b) from the Timetable page by pressing 'Home' link c) from the Home page by pressing Befit logo d) from the Home page by pressing 'Home' link.      | 6. a) and b) User is redirected to the Home page. c) and d) The page is reloaded.                                                                                                                                                                                                                                          | PASS          |               |
|                                                         | 7. Click the Facebook icon a) from the Timetable page footer b) from the Home page footer.                                                                                                                                       | 7. Facebook sign in page is opened in a separate browser tab.                                                                                                                                                                                                                                                              | PASS          |               |
|                                                         | 8. Click the Instagram icon a) from the Timetable page footer b) from the Home page footer.                                                                                                                                      | 8. Instagram sign in page is opened in a separate browser tab.                                                                                                                                                                                                                                                             | PASS          |               |
| Test the Sign Up form. First and Last name text fields. | 1. Leave the First name field blank and try to submit the form.                                                                                                                                                                  | 1. The field is required to fill in.                                                                                                                                                                                                                                                                                       | PASS          |               |
|                                                         | 2. Leave the Last name field blank and try to submit the form.                                                                                                                                                                   | 2. The field is required to fill in.                                                                                                                                                                                                                                                                                       | PASS          |               |
|                                                         | 3. Check that alphanumeric and special characters are accepted in First name and Last name fields.                                                                                                                               | 3. User is allowed to use alphanumeric and special characters in First name and Last name fields.                                                                                                                                                                                                                          | PASS          |               |
| Test the Sign Up form. Email address.                   | 1. Leave the Email field empty and try to submit the form.                                                                                                                                                                       | 1. The form cannot be submitted without an email address entered.                                                                                                                                                                                                                                                          | PASS          |               |
|                                                         | 2. Type invalid email address a) omit the @ symbol b) incomplete test@                                                                                                                                                           | 2. Invalid email address is not accepted. User cannot submit the form.                                                                                                                                                                                                                                                     | PASS          |               |
| Test the Sign Up form. Options dropdown.                | 1. Click the Options dropdown.                                                                                                                                                                                                   | 1. The dropdown menu appears and displays the following options: disabled 'Select an option', off-peak, standard, premium, free group lesson, free personal training, extra personal training.                                                                                                                             | PASS          |               |
|                                                         | 2. Try to select the disabled option from the dropdown.                                                                                                                                                                          | 2. The disabled option cannot be selected.                                                                                                                                                                                                                                                                                 | PASS          |               |
|                                                         | 3. Select any other option except the disabled one.                                                                                                                                                                              | 3. The dropdown menu is collapsed. Correct option is selected in the dropdown.                                                                                                                                                                                                                                             | PASS          |               |
| Test the Sign Up form. Message text box.                | 1. Check that alphanumeric and special characters are accepted in the Message text box.                                                                                                                                          | 1. User can type any alphanumeric or special characters in the text box.                                                                                                                                                                                                                                                   | PASS          |               |
|                                                         | 2. Add a large text, at least 1000 characters.                                                                                                                                                                                   | 2. The text is accepted (it wasn't cut). The vertical scroll bar becomes available to be able to see the full text.                                                                                                                                                                                                        | PASS          |               |
|                                                         |                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                            |               |               |

Known issues:

# Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


# Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X