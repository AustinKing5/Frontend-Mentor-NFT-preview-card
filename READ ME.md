# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

The challenge is to build out this preview card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![.\Frontend Mentor NFT preview card\images\Web capture_14-9-2022_16916_.jpeg](./images/web capture_14-9-2022_16916_.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Figma (Re-designing work)
- Mobile-first workflow
-


### What I learned

The Most important learning experience was how to correctly create an overlay and implement the pseudo-class :hover {}. This required some level of research and understanding what css properties (opacity: 0;) to apply.

To see how you can add code snippets, see below:

```css
.overlay {
  overflow: hidden;
  opacity: 0;
  background-color: hsla(178, 100%, 50%, 0.5);
  width: 100%;
  height: 100%;
  position: absolute;
  top: 50%;
  left: 50%;
  border-radius: 10px;
  transform: translate(-50%, -50%);
}

.view {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

### Continued development

Taking more challenges is the sure way of improving my knowledge in HTML and CSS custom properties. I intend to work on two more challenges with purely HTML and CSS codes


### Useful resources

- [Google Fonts](https://fonts.google.com/specimen/Outfit?query=outfit) - This helped me for generate the required font for my work.

## Author

- Github - [Augustine Asare](<https://github.com/AustinKing5>
/Frontend-Mentor-Challenges)
- Frontend Mentor - [@AustinKing5](https://www.frontendmentor.io/profile/AustinKing5)
- Twitter - [@aryetehasare](https://www.twitter.com/aryetehasare)
