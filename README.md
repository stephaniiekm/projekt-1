# **ADHD** - Website

This **ADHD** - website presents a little information about this hidden disability.

The purpose of the page is to spread knowledge about the basics of ADHD,
and give an idea of ​​what it is like to live with ADHD.
To make it easy and more fun to learn the page has a YouTube-clip insted of images.

![How the webpage looks on different devices](assets\pic-README\responsivedesign-ADHD.png)

Users will be able to find interesting content in a easy and simple way.

This project is for educational purposes and can not be used as a template for a business use.
Main is to build user friendly and responsive website with HTML and CSS only. I will use Bootstrap framework to keep website consent.

---

## View live website in [github pages](https://stephaniiekm.github.io/projekt-1/)

---

# Table of contents

- [UX](#ux)
  - [Website owner goals](#website-owner-goals)
  - [User goals](#user-goals)
    - [New user goals](#new-user-goals)
    - [Returning user goals](#returning-user-goals)
    - [Website owner goals](#website-owner-goals)
  - [User stories](#user-stories)
  - [Structure of the website](#structure-of-the-website)
  - [Wireframes](#wireframes)
  - [Surface](#surface)
- [Features](#features)
- [Technology](#technology)
- [Testing](#testing)
  - [Functionality testing](#functionality-testing)
  - [Compatibility testing](#compatibility-testing)
  - [Code Validation](#code-validation)
  - [User stories testing](#user-stories-testing)
  - [Issues found during site development](#issues-found-during-site-development)
  - [Performance testing](#performance-testing)
- [Deployment](#deployment)
- [Credits](#credits)
- [Screenshots](#screenshots)

# UX

## Website owner goals

The main reason to create this website is to help spread awareness of a disability.
Page owner can easy show text in list layout to make it easier to understand and create space for a YouTube-film, which can give the owner the flexibility to replace their material.
And since the site is also aimed at those who have difficulties with focus, concentration, and motivation to be able to read, this website is made with this in mind.

## User goals

### New user goals:

- user can find information about ADHD.
- user can watch and read to create a first understanding of what ADHD is.
- user can also form an idea of the importance of support.

### Returning user goals:

- user can learn more about how it is to have ADHD.
- user is able to find link to an external page with more information.
- user can easily navigate around through the page with internal links.

## User stories

### As a page owner:

- I would like to present brief information about ADHD.
- I need easy navigation as my target audience is primarily
  those with disabilities and their relatives.
- I want my users to be able to learn how to use my website intuitively and easily.

### As a new customer:

- I wish to find information about ADHD.
- I would like get possibility to look at something instead of reading.
- I want read about someone who has ADHD.

### As a returning customer:

- I want the opportunity to possibly be able to see new material.
- I want to be able to get tips and support functions.
- I would like to be able to show my close brief information about ADHD.

## Structure of the website

The website is designed to be easy and user-friendly on all type of devices.
On desktop, tablet or mobile device there should be no difference for a user to have a fantastic experience. All parts are designed to achieve maximum user satisfaction. User will get some interaction from the interface as links and buttons will have a hover effect.

## Wireframes

I used Balsamiq Wireframes to create the most basic wireframes.

![Wireframes](assets\pic-README\Wireframe-ADHD2.png)
![Wireframes](assets\pic-README\wireframe-aDHD1.png)

## Surface

### Colors

Color is picked to not get destracting and to much.

- background color: Light
  Navbar:
  background-color: rgb(156, 172, 189)

### Fonts

Main fonts is Bootstrap

- font-family: var(--bs-body-font-family)
  --bs-font-sans-serif: system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","Liberation Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";

### Images

- I used image for intro-background from [Pexels.com](https://www.pexels.com/) and there are credited in [credits](#credits) section.

[Back to Table of contents](#table-of-contents)

---

# Features

The website is a one page website, and is divided into sections.

The website has below features:

## Navigation bar

- #### Navigation bar is visible on the top of website. It is responsive and will adapt to mobile devices by a change into a burger menu.
- Navigation scheme:

  - On left side there is a logo. It can be used as navigation link to the main page.
  - On right side there are four links or burger menu when the website is in smaller devices.
    It contains:
    - INFORMATION
    - FILM CLIP
    - SUPPORT
    - ABOUT ME

## Top -intro

     * Has a heading and a blockquote
     * Background-image
     * A intro message- Which gives the user a hint

## Information

    * Provides information on what ADHD means
    * What ADHD is
    * How you get it
    * Symptoms

## Film clip

    * Have a YouTube-clip about ADHD

## Support

    * Gives a hint of how to provide support
    * Useful tips

## About me

    * What is it like to live with ADHD

## Footer

- Footer has a ADHD-link so the user can get up to the top, on left side and social links on right side.
  Each link will open in a separate tab in a browser.

[Back to Table of contents](#table-of-contents)

---

# Technologies used

### HTML5

- As a structure language.

### CSS

- As a style language, also used to create media quarie.

### Bootstrap

- Bootstrap@5.1.3 as a CSS framework to keep responsive, mobile first aproach.

### Bootstrap icon

- As an icon library for a social links.

### Google fonts

- As a font resource.

### GitHub

- As a software hosting platform to keep project in a remote location.

### Git

- As a version-control system tracking.

### Microsoft VS Code

- As a development hosting platform.

### Balsamiq Wireframes for Desktop

- As a wireframe tool.

[Back to Table of contents](#table-of-contents)

---

# Testing

## Functionality testing

I used Microsoft Edge developer tools and Chrome developer tools throughout the project for testing and solving problems with responsiveness and style issues.

## Compatibility testing

Site was tested across multiple virtual browsers, smaller screen (ipad), and mobile devices. I checked all supported devices in both Chrome developer tools and Microsoft Edge developer tools.
Most of the testing has been doing on a Laptop- Hp with Windows 10 – With screen connecting to tv and larger screen, to look at the responsiveness.

## User stories testing

### As a page owner:

- I would like to have a simple webpage with sections.

- I need to make sure that my current and new users will find it easy to navigate around the web page

  > Users can easy navigate because of the fixed navbar and link in the footer.

- I would like to have a alternative to not having to read.
  > Users are able to find a Youtube-film clip.

### As a new customer:

- Easy to understand the information.

  > User can read sections of text and have an alternative to be able to watch on YouTube film clip

- Want to hear from someone who has ADHD.
  > User can find it in the section: About me.

### As a returning customer:

- I need to have easy information.
  > User can get that because of the layouts structure.

---

## Issues found during site development

- #### Footer on the bottom of the screen – ADHD link text would not get in line when I changed devicer.
  I then used Bootstrap class styling to change margin-bottom (=mb) and it did get better.
  > After I gain more experience with bootstrap I found that I could achive this by [Bootstrap -cheat](https://bootstrapcreative.com/resources/bootstrap-5-cheat-sheet-classes-index/) class.

## Performance testing

I run [Lighthouse](https://developers.google.com/web/tools/lighthouse/) tool to check performance of the website.
I had to do couple of changes to improve performance

Final results:
![Lighthouse](assets\pic-README\Lighthouse-ADHD.png)
![Lighthouse](assets\pic-README\Lighthouse.png)
I noticed that this tests scores vary from time to time and depends on external libraries as well.

## Code Validation

At the end of the project I used two websites to validate a code

- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS
- [Nu Html Checker](https://validator.w3.org/) to test HTML

[Back to Table of contents](#table-of-contents)

---

# Deployment

The project was deployed on GitHub Pages. I used Microsoft VS Code as a development environment where I commited all changes to git version control system.
I used push command in VS Code to save changes into GitHub.

To deploy a project I had to:

- Log in to GitHub and click on repository to deploy ([Project-1](https://github.com/stephaniiekm/projekt-1))
- select `Settings` and find GitHub Pages section at the very bottom of the page
- from source select `none` and then `master` branch.
- click `save` and page was deployed after auto-refresh.
  > Your site is published at https://stephaniiekm.github.io/projekt-1/

To run localy:

- Log in to GitHub and click on repository to download ([Project-1](https://github.com/stephaniiekm/projekt-1))
- select `Code` and click Download the ZIP file.
- after download you can extract the file and use it in your local environment

Alternatively you can [Clone](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
or [Fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)
this repository ([Project-1](https://github.com/stephaniiekm/projekt-1)) into your github account.

[Back to Table of contents](#table-of-contents)

---

# Credits

- Ideas and knowledge library:

  - [w3schools.com](https://www.w3schools.com)

  - [css-tricks.com](https://css-tricks.com/)

  - [getbootstrap.com/docs](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
    I used code for navbar, footer and css-classes from Bootstrap.

### Content:

- General content: comes from one experience and google serching when I found the linked page.

[Back to Table of contents](#table-of-contents)

---
