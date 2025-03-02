# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/RoxySash/Single-Price-Grid-Component-CSS--Flexbox.git)
- Live Site URL: [Add live site URL here](https://roxysash.github.io/Single-Price-Grid-Component-CSS--Flexbox/)

## My process

1. Initialized project as a public repository 
2. Configured repository to publish your code to a web address. 
3. Looked through the designs to started planning. 
4. Wrote HTML classes and added divs or sections.
5. Wrote out the base styles for my project, including general     content styles, such as `font-family` and `font-size`.
6. Started adding styles to the top of the page and work down.  Jumped back and forth for a while. 
7. After using dev tools to check responsiveness on various screen sizes I concluded that the project was complete. 
8. Final Push 



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that using clamp feature would be useful to increase the font size when the design adapts to a new device. I opted to use a change of the font size inside the media query instead. Below is how the clamp is used without the media query this would be added to the p or h elements. 

```css
font-size: clamp(1.8rem, 2.5vw, 2.8rem);

```

For the hover and active state I implemented my own as there were no example in the design files. Hover or click the call-to-ation button to see the suttle changes.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
 button:hover {
    background-color: hsl(71, 64%, 48%);
  }

  button:active {
    box-shadow: 2px 2px 1px rgba(0, 0, 0, 0.2);
  }


```


### Continued development

I want to refine using the shortest code or shortening the amount of css used to clean up my css style and readbility.



### Useful resources

- [https://developer.mozilla.org/en-US/docs/Web/CSS/clamp](https://www.example.com) - This helped me for research clamp and how to use it.


## Author

- Frontend Mentor - [@RoxySash](https://www.frontendmentor.io/profile/yourusername)


