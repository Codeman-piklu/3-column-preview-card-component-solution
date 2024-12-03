# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor]. Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process]
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![](./Screenshot%20(4).png)
### Links
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
### Built with
-Semantic HTML5 markup
-CSS custom properties
-Flexbox
-Responsive design
-Mobile-first approach
-Google Fonts for custom fonts
### What I learned
Throughout this project, I focused on:

    Using CSS flexbox for creating a responsive 3-column layout.
    Leveraging CSS custom properties (variables) for consistent color management.
    Creating hover effects for interactive elements like buttons and images.

Here's an example of the CSS I used to create the layout:
#main {
  display: flex;
  flex-direction: row;
  gap: 20px;
}
I also learned how to ensure the layout adapts well to smaller screens, making use of media queries:

@media screen and (max-width: 760px) {
  #main {
    display: block;
  }
}

### Continued development

In the future, I would like to focus on:

    Implementing a more complex grid layout using CSS Grid.
    Adding animations to enhance the user experience.
    Improving accessibility by adding more ARIA attributes.


### Useful resources
MDN Flexbox Guide - This guide helped me understand how to use flexbox effectively.
Google Fonts - A great resource for custom fonts.
Frontend Mentor - The challenge itself was an excellent way to practice my skills.

## Author

- Website - [piklu]
- Frontend Mentor - [@Codeman-piklu]
- github - [@Codeman-piklu](https://github.com/Codeman-piklu)


## Acknowledgments

A big thank you to Frontend Mentor for providing such a fantastic challenge! Also, thanks to the community for sharing their solutions and providing inspiration.

