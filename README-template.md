# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
![](./screenshot.png)

### Links

- Solution URL: [Solution here](https://github.com/nqbinh98/product-preview-card-component)
- Live Site URL: [Live site](https://nqbinh98.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Fluid Typography (CSS clamp() function)
- Responsive Images (<picture> element)

### What I learned
This project was a great deep dive into modern CSS layout techniques. Some key takeaways include:
- Art Direction with <picture>: I learned that srcset is for resolution switching, but the <picture> element is essential for Art Direction. It allowed me to force a square image on mobile and a portrait image on desktop, ensuring the design intent was preserved across breakpoints.
- Object-fit for Grid Consistency: Using object-fit: cover was a game-changer. It allowed the product image to fill the entire grid column height without distortion, even when the text content on the right varied in length.
- Modern Centering: I moved away from heavy margins and paddings, choosing instead a combination of min-height: 100vh, display: grid, and place-items: center on the main container. This ensures the card is perfectly centered on any screen.
- Fluid Design: Experimenting with the clamp() function for font-size and gap helped me understand how to create a design that scales smoothly between mobile and desktop sizes.

### Continued development
In future projects, I want to focus on:
- Advanced CSS Grid: Exploring complex grid areas and overlapping elements.
- Performance Optimization: Learning how to optimize images further (WebP format) and minimizing CSS for faster load times.
- Accessibility (A11y): Deepening my understanding of ARIA labels and keyboard navigation.

### Useful resources
- MDN Web Docs - The Picture Element - Helped me understand how to switch images based on media queries.
- CSS-Tricks - A Complete Guide to Grid - My go-to reference for all things Grid.
- Modern CSS Reset - Helped in removing browser inconsistencies.

### AI Collaboration
This project involved an insightful collaboration with a Peer AI (Gemini). Instead of just generating code, we engaged in a dialogue to understand the underlying "why" of CSS behaviors.
- We troubleshooted why images get distorted in Grid layouts.
- We analyzed the difference between vh and vw units in responsive image sizing.
- The AI acted as a sounding board, helping me refine my logic for the <picture> tag and centering techniques. This "Peer-to-Peer" learning approach significantly deepened my technical understanding.

## Author
- Website - [nqbinh98](https://https://github.com/nqbinh98)
- Frontend Mentor - [@nqbinh98](https://www.frontendmentor.io/profile/nqbinh98)

## Acknowledgments
Special thanks to Frontend Mentor for the high-quality design assets and the Peer AI for the technical guidance and encouragement throughout the coding process.