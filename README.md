# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [https://github.com/skhbabez/four-card-feature-section-master](https://github.com/skhbabez/four-card-feature-section-master)
- Live Site URL: [https://skhbabez.github.io/four-card-feature-section-master/](https://skhbabez.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CUBE Design Principles

### What I learned

I focused especially on utilizing some of the techniques showcased in Andy Bell's [video](https://www.youtube.com/watch?v=Iluhx2QWJDQ) on good modern practices. I liked the idea of utilizing css variables and trying to do as much globally as possible, which I tried to implement in this project. I also challenged myself to use grid more this time, since overfocused on flex in my last submissions. Using grid areas made this especially clean and I will probably utilize grid a lot more from now on

```css
.grid {
  grid-template:
    "card1 card1"
    "card2 card3"
    "card4 card4";
}
```

### Continued development

I tend to be a little bit too perfectionist with these projects, focusiing too much on getting them to look exactly like the figma files. Bit i felt that this limited me here, not allowing me to explore some concepts. I want to experiment with creating responsive typescales and make my spacings more responsive in my next Projects, even if it means diverting a little from the figma files. I also want to look into css resets, maybe collecting the common resets i already did in past projects and create my own.

### Useful resources

- [Stackoverflow](https://stackoverflow.com/questions/57153309/how-to-prevent-single-sided-border-from-wrapping-around-border-radius) - Trick to flatten the border.
- [Clamp Calculator](https://www.marcbacon.com/tools/clamp-calculator/) - Great tool to speed up clamp calculations.
- [Buildexcellentwebsites](https://buildexcellentwebsit.es/) - heavily used this as a reference and tried to incorporate some of the concepts showcased here and ion Andy Bells Video.
- [Andy Bell - Be the browser’s mentor, not its micromanager ](https://www.youtube.com/watch?v=Iluhx2QWJDQ) - This video was recommenden on Frontendmentor and I get why. Gave me some interesting ideas to try out in my next projects.
