# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

This project is a solution to the Social Links Profile challenge from Frontend Mentor. The goal was to build a responsive profile card that displays a user's name, location, profile image, and a list of social links. The project emphasizes accessibility, semantic HTML, and modern CSS techniques such as Flexbox. It is designed to work seamlessly across different devices and screen sizes, providing a clean and interactive user experience. Through this challenge, I practiced managing styles and ensuring good usability for all users.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./social-links-profile-desktop.png)
![](./social-links-profile-mobile.png)

### Links

- Solution URL: [https://github.com/remainhumble/-Social-links-profile]
- Live Site URL: [https://remainhumble.github.io/-Social-links-profile]

## My process

I began by carefully reviewing the project requirements and design files provided by Frontend Mentor. I set up the project structure using semantic HTML5 and organized my CSS with custom properties for easy theming. I implemented a mobile-first approach, starting with the layout for smaller screens and progressively enhancing it for larger devices using Flexbox. Throughout the process, I regularly tested the component in two different screen sizes to ensure responsiveness. I also made use of version control with Git to track my progress and manage changes efficiently.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

One key takeaway from this project was learning how to implement accessible hover and focus states for an interactive element. Outside of working on this project, I found out how to use CSS pseudo-classes like `:hover` and `:focus` to provide clear visual feedback for users interacting with interactive elements. This not only improves the user experience but also enhances accessibility for keyboard and assistive technology users. I also learned the importance of ensuring that focus outlines are visible and meet contrast requirements, making the component more inclusive.

```css
li {
  list-style: none;
  background-color: var(--Grey-700);
  padding: 1.071em; /* 15px */
  border-radius: 0.571em; /* 8px */
  font-weight: 600;
  width: 100%;
  color: var(--White);
}

a {
  text-decoration: none;
  color: var(--White);
}

li:hover {
  background-color: var(--Green);
  cursor: pointer;
}

li:hover a {
  color: var(--Grey-800);
  font-weight: 700;
}

a:focus {
  font-weight: 700;
  outline: 0.143em solid var(--Green); /* 2px */
}
```

### Continued development

In future projects, I want to continue improving my skills in the following areas:

- Enhancing accessibility, especially for keyboard navigation and screen readers.
- Deepening my understanding of responsive design techniques for a wider range of devices.
- Refining my use of CSS custom properties and exploring advanced CSS features.
- Improving component reusability and maintainability in my codebase.
- Practicing more with semantic HTML to ensure better structure and SEO.

These focus areas will help me build more robust, user-friendly, and scalable web components.

### Useful resources

- [Bro Code - YouTube](https://www.youtube.com/@BroCodez) - Coding bootcamps HATE him!
  See how he can teach you to code.
  His channel is dedicated to providing free education to those that cannot afford college, bootcamps, and overpriced crap coding gurus try to sell you.
- [Frontend Mentor Community](https://www.frontendmentor.io/community) - Great place to ask questions and see how others approach similar challenges.
- [Google Fonts](https://fonts.google.com/) - Used for selecting and implementing web fonts in the project.
- [GitHub Docs - Getting Started with Git](https://docs.github.com/en/get-started/quickstart) - Useful for managing version control throughout the project.

## Author

- Frontend Mentor - [@remainhumble](https://www.frontendmentor.io/profile/remainhumble)
- X(formerly Twitter) - [@thiflan120699](https://x.com/thiflan120699)
