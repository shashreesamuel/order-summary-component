# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)



### Links

- Solution URL: [Check out the code here](https://github.com/TheCoderGuru/order-summary-component)
- Live Site URL: [Visit the live site here](https://order-summary-component-chi-eight.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learnt that whenever you want to achieve the image at the top of a container as seen in the screenshot above then you can include the css properties ```top``` and ```position: absolute;``` on the specific image. However you must ensure that the container class has the css declaration of ```position: relative;```. It would also help if you structure your markup based on the design shown whereby having your image code above the code responsible for your content within the card like this 

```
<img src="" alt="" />
<!-- code responsible for the content here -->

```

The benefit of this structure is that it is easier if you are using flexbox or css grid to achieve the design layout since the code would be minimal and easier to understand.


### Continued development

I plan to use ```top``` and the ```position``` properties in my upcoming challenges in order to get more familiar with these two css properties and also reading articles and support channels to better understand the various possibilites that can be achieved by using these properties.

### Useful resources

- [CSS Tricks - CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me with the flexbox concept and I am really glad to be recommend this article, will use it going forward.

- [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS) - This is the guide to all the css properties with an indept explanation. Definitely recommend it.


## Author

- Frontend Mentor - [@TheCoderGuru](https://www.frontendmentor.io/profile/TheCoderGuru)
- Twitter - [@TheCoderGuru](https://www.twitter.com/TheCoderGuru)
