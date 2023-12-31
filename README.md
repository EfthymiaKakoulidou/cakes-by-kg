# [CAKES BY KG](https://efthymiakakoulidou.github.io/cakes-by-kg)

![GitHub repo size](https://img.shields.io/github/repo-size/EfthymiaKakoulidou/cakes-by-kg?color=orange)

Cakes by KG is a website aiming to provide information about the services Katerina Glykou offers which are designing and baking cakes. Apart from the information, the project hopes to inspire the user in the process of choosing a cake. The target audience is people in the Stockholm region who need to order cakes. With the use of picture and contact information the target audience will be able to be inspired choose a cake and order it.


![screenshot](documentation/responsive-site.jpg)

## UX

My aim was to create an accessible and easy-to-navigate website. I wanted it to invite the user to enter a fun and sweet world.

### Colour Scheme

The choice of colours was based on we typically associate to sweet flavors. I chose pink for sugar, beige for cream, brown for chocolate and white. Because of the background image being so colourful I chose not use any more colours to tone it down and make it more clear.

- rgb 68,33,22 - Dark brown -used for all text.
- rgb 255,182,193 - Lightpink - used for background to the header and as backround for the galleries so that the images can be easily seen.
- rgb 255,228,196 -Bisque - used for the logo and as background to the text having the needed contrast for accessibility.


I used [coolors.co](https://coolors.co/palette/ffb6c1-ffe4c4-8b4513-e0ffff-ffffff) to generate my colour palette.

![screenshot](documentation/pallette.png)

### Accessibility

This site is accessible in the terms that it uses enough contrast between the text and its background, it is using semantics, alt attributes on all images and aria-label attributes where there is no text to define the section.

### Typography

I used 2 font-families for my project. One clean and readable for the whole site and one more graphic to create just the logo and titles.

- [Shadows into light](https://fonts.google.com/specimen/Shadows+Into+Light?query=shadow+) was used for the primary headers and titles.

- [Mako](https://fonts.google.com/specimen/Mako) was used for all other secondary text.

- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the social media icons in the footer, as an indication to the user to click on an image so that they can see more pictures of the same cake, and a burger icon serving the responsiveness needs.

## User Stories

As a user of this site I would like to be able to get inspired and order my cake. 

### New Site Users

- As a new site user, I would like to see pictures of cake, so that I can decide what I want.
- As a new site user, I would like to to have the option to describe my cake of choice, so that I can order a customized cake that will be exactly how I wanted it to be.
- As a new site user, I would like to like to be provided with contact information, so that I can make my order.


### Returning Site Users

- As a returning site user, I would like to see if the site has been updated, so that I can get more cake ideas.
- As a returning site user, I would like to be able to access the contact information, so that I can order again.

## Wireframes

To follow best practice, wireframes were developed for mobile, and desktop sizes. 
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.
Although the final project might differ from the initial wireframes I kept the main concept intact and just added some features along the way where I thought they might be needed. A second video on the about page is the biggest change and I did that to be consistent to the layout of having 3 elements on each page except the gallery pages of course that have a lot more.


### Mobile Wireframes

<details>
<summary> Click here to see the Mobile Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/mobile-home.png)

About
  - ![screenshot](documentation/wireframes/mobile-about.png)

Contact
  - ![screenshot](documentation/wireframes/mobile-contact.png)

Birthday Cakes
  - ![screenshot](documentation/wireframes/mobile-birthday-cakes.png)


</details>


### Desktop Wireframes

<details>
<summary> Click here to see the Desktop Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/desktop-home.png)

About
  - ![screenshot](documentation/wireframes/desktop-about.png)

Contact
  - ![screenshot](documentation/wireframes/desktop-contact.png)

Birthday Cakes
  - ![screenshot](documentation/wireframes/desktop-birthday-cakes.png)

Speciallty Cakes
  - ![screenshot](documentation/wireframes/desktop-speciallty-cakes.png)

Sweet Treats
  - ![screenshot](documentation/wireframes/desktop-sweet-treats.png)

</details>

## Features

The project consists of 7 different pages:
 - The Home page : This is the first page that the user is going to meet. It welcomes the user and sets the tone for the experience he/she is going to have.
 - The About page : This page introduces the owner of the page so that the user gets information about the service-provider.
 - The Contact page : This page provides the contact details of the owner so that the user can easily get in touch with her.
 - 3 gallery pages : These pages display the work of the owner so as to show to user what kind of services they can expect. There are 3 categories from which the user can be directed to more specific areas of interest.
    - The birthday cakes page,
    - The Speciallty cakes and
    - The Sweet treats page.
 - The confirmation page which is not really a part of the project but it is where the user is redirected when he/she fills the form in the contact page.

### Existing Features

- The logo button :

    - The logo button is the expression of the whole graphic language of the site in the header. It has the owners initials on it and directs the user to the home page.

![screenshot](documentation/feature01.jpg)

- The welcome link

    - This feature takes up the center and most important part of the page. It directs the user to the home page and it is an easy way to get to the start from anywhere inside the site.It is seen in all screen sizes.

![screenshot](documentation/feature02.jpg)

- The links to the gallery

    - Since the galleries are the most interesting part of the site I thought it would be nice to have direct links to them that are visible and clear on the home page.

![screenshot](documentation/feature03.jpg)

- The navigation bar with the dropdown menu

    - This feature is essential to the user. It is used to navigate the user to the different pages of the site from any part of the site that he/she are in.

![screenshot](documentation/feature04.jpg)

![screenshot](documentation/feature041.jpg)

![screenshot](documentation/feature042.jpg)


- The videos features

    - These features are used to keep the interest of the user on the about page. The user can see the process of making a cake which I think is very interesting.

![screenshot](documentation/feature05.jpg)
![screenshot](documentation/feature051.jpg)

- The contact form

    - This feature is used to give to the user the opportunity to contact the owner directly from the site without having to leave the page.

![screenshot](documentation/feature06.jpg)

- The google maps i frame

    - This feature is used to show the location of the owner on the map since an address on its own may not provide the same amount of information to all the users.

![screenshot](documentation/feature07.jpg)

- The birthday cakes/speciallty cakes/sweet treats galleries

    - There are all of the images here. The user can click on the preview image of each cake and see it enlarged so they can study the details. Also more pictures of the same cake -hidden behind the preview picture - are provided for more information.

![screenshot](documentation/feature08.jpg)

![screenshot](documentation/feature09.jpg)

### Future Features

In the future and with the scenario that business goes well for the owner it would br helpful to add:

- Prices for the cakes
- Billing feautures:
    - this will give the user the opportunity to pay for the cake online.
- Make your own cake feature:
    - a feature that the user will be able to use his/hers imagination to construct a new cake and then get feedback from the owner. A menu of diffrent flavors can be provided.

## Tools & Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) used for an enhanced responsive layout.
- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod](https://gitpod.io) used as a cloud-based IDE for development.

## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/EfthymiaKakoulidou/cakes-by-kg), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://efthymiakakoulidou.github.io/cakes-by-kg)

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/EfthymiaKakoulidou/cakes-by-kg) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/EfthymiaKakoulidou/cakes-by-kg.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/EfthymiaKakoulidou/cakes-by-kg)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/EfthymiaKakoulidou/cakes-by-kg)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!


### Local VS Deployment

There are no big differences between my local and the deployed version of the project.


## Credits

I used the "Love running" walkthrough material throughout the project to help me construct it.

I got help for troubleshooting my problems from :
https://stackoverflow.com/
https://www.w3schools.com/

I got help to build my gallery from :
http://fancybox.net/

I used :
https://fontawesome.com/  for the icons

I used : 
https://fonts.google.com/ for the fonts

I used :
https://www.google.com in general for every little question that I need a quick answer for.

I got help from my mentor to create the redirect page.


### Content

I got all the content of the site from the owners instagram and she was more than happy to get a site for her work : https://www.instagram.com/cakebykg/

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://github.com/TravelTimN) for their support throughout the development of this project.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support and valuable feedback they provided.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and some project issues.
