# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe Page Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

The goal of this project was to create a recipe page that displays a recipe for an omelette. The challenge was to design a visually appealing and user-friendly layout that works well on both desktop and mobile devices.

### Screenshot

![Recipe Page Screenshot](./docs/recipe-webpage.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Google Fonts
- Media queries for responsive design
- Developer tools for testing and debugging

### What I Learned

Working on this project helped me understand the importance of semantic HTML5 elements and how to use them effectively. Additionally, I gained more experience with CSS custom properties, responsive design using media queries, and using developer tools to test and debug my code.

One key aspect I learned was how to use the `@media` rule to make the layout responsive. The `@media` rule allows you to apply different styles depending on the screen size, orientation, or other conditions. This ensures that the webpage looks good on both desktop and mobile devices.

Here's an example of how I used media queries to adjust the layout for different screen sizes:

```css
/* Default styles for larger screens */
.recipe-card {
	background-color: hsl(0, 0%, 100%);
	width: 50%;
	margin: 10vh auto;
	padding: 2rem;
	border-radius: 10px;
	font-size: 16px;
	font-family: "Outfit", serif;
	font-weight: 400;
}

/* Styles for smaller screens */
@media (max-width: 767px) {
	.recipe-card {
    	width: 100%;
    	max-width: 100%;
	}
}
```

Throughout the process, I spent a significant amount of time using developer tools to inspect elements, test styles, and debug issues. This was crucial in ensuring the page worked correctly on various screen sizes.

### Continued Development

In future projects, I want to focus more on:
- Advanced CSS techniques
- JavaScript interactivity
- Enhancing accessibility

### Useful Resources

- [The Markdown Guide](https://www.markdownguide.org/) - This guide helped me understand markdown better and structure my README file more effectively.
- [CSS-Tricks](https://css-tricks.com/) - An amazing resource for CSS techniques and best practices.

## Author

- Frontend Mentor - [@Denilson15](https://www.frontendmentor.io/profile/Denilson15)

## Acknowledgments

I’d like to thank the Frontend Mentor community for their support and feedback throughout this project. Their guidance and insights were invaluable.
