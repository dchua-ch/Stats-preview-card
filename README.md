# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Solution Screenshot](#solution-screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Solution Screenshot
![Mobile Stats Preview Card](images/stats-preview-mobile.png)  
*Mobile layout of stats preview card*


![Desktop Stats Preview Card](images/stats-preview-desktop.png)
*Desktop layout of stats preview card*





### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I marked up and styled the mobile layout first. The mobile layout consists of an image and a div with text wrapped in a containing div, with class ".text-container". I then turned .text-container into a flexbox container. The desktop layout was implemented by using a media query and changing the flex-direction.  

### Built with


- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
As mentioned earlier, this is my first time I've implemented a design in HTML/CSS. As such, I've managed to learn and practice many of the basics for the first time. It is also my first time using Git and GitHub to manage the version control of a project.  

I struggled with getting some parts of the design correct. Most notably the positioning of the elements. I highlight some of the challenges I overcame below.

To see how you can add code snippets, see below:

1. Responsive layout using FlexBox
The responsive layout was achieved by changing the flex-direction from column in mobile mode to row-reverse in desktop mode.
```css
.flex-container {
    /* Mobile layout */
    display: flex;
    flex-wrap: nowrap; 
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width:70%;
    min-width: var(--mobile-min-width);
}

@media screen and (min-width: 922px){
    .flex-container{
        flex-direction: row-reverse;
        width: 100%;

    }
    ...
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
