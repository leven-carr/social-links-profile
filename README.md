# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Set up steps: Create styles.css, link it in the head of the html, link the font in the head as well. Move the provided styles to styles.css and delete the style tag. Write the custom variables and the universal reset in styles.css.

Working on the HTML: Create a main element to hold the content, and give it the flex-container class in order to position the card. Create a section element for the card, and give it the flex-container class. Add the image, the h1, paragraph elements for the location and bio text, and a ul for the links. Give the ul the flex container class as well. Inside the ul, add five li elements, each one with an a tag inside of it, and fill in the name of the social media sites.

Styling: Set some overall styles on the body, including font-family, background-color, color, font-weight, and text-align. Write the .flex-container rules for the elements acting as flex boxes. Set the height of the main element to 100vh so that the card will be vertically centered. Then style the card width, background-color, border-radius, and padding. From there, work down the card styling the elements from top to bottom. As in the previous challenge, I waited until the end to do the margins to create spacing. I finished by creating the :hover and :focus states for the links.

### Built with

HTML and CSS (including flexbox); no CSS frameworks or JS

### What I learned

I had a little bit of trouble getting the hover and focus states of the a tags to behave as I wanted them to for styling purposes. I figured out I needed to set their display property to block in order to make their width take up their respective parent li, so that the whole rectangle of each link is targetable rather than just the text and its immediate space.

I also added a media query, which I had not done on the previous two challenges.

### Continued development

In the future I want to work on adding CSS transitions for states such as hover and focus.

## Author

- Frontend Mentor - [@leven-carr](https://www.frontendmentor.io/profile/leven-carr)
- GitHub - [@leven-carr](https://github.com/leven-carr)
