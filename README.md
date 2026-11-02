# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [https://github.com/mth-ani/four-card-feature-section](https://github.com/mth-ani/four-card-feature-section)
- Live Site URL: [https://mth-ani.github.io/four-card-feature-section/](https://mth-ani.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project taught me how to use one HTML source order for both layouts. The cards stay in mobile order in the HTML, and CSS Grid rearranges them on desktop, which keeps the page accessible for screen readers and keyboard users.

I also learned how grid line numbers work. Making a card span two rows and centering it vertically looks like this:

```css
.supervisor-card {
  grid-column: 1;
  grid-row: 1 / 3;
  align-self: center;
}
```

Other things I picked up:

- Using `alt=""` on decorative images so screen readers skip them
- Setting `display: block` on images to remove the extra gap underneath
- Converting px to rem (divide by 16) so sizes respect the user's browser settings
- Using `gap` instead of margins to space items evenly

### Continued development

I want to get more comfortable with CSS Grid placement, especially the line-number syntax, and practise building layouts that work smoothly between mobile and desktop, including tablet sizes.

### AI Collaboration

I used Claude as a mentor while building this project. Instead of asking it to write the code, I asked for hints, explanations and code reviews, then wrote the HTML and CSS myself.

- **What worked well:** getting feedback on my HTML structure (semantic elements, heading levels, alt text), and having concepts like CSS Grid explained step by step.
- **What didn't:** some pixel measurements from the design were only estimates, so I still had to compare my result with the design in dev tools and adjust by eye.

## Author

- GitHub - [@mth-ani](https://github.com/mth-ani)
- Frontend Mentor - [@mth-ani](https://www.frontendmentor.io/profile/mth-ani)
