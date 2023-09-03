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

![](./images/screenshots/)


**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/arvndlr/order-summary.git)
- Live Site URL: [Add live site URL here](https://order-summary-ten-zeta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learn a little bit in breakpoints and also about designing. I improve my skills in box model and I am able to duplicate the challenge.

To see how you can add code snippets, see below:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="./css/styles.css">
```
```css
@media only screen and (max-width: 376px) {
  body {
    font-size: 14px;
  }

  .container {
    box-sizing: border-box;
    width: 325px;
    height: 565px;
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    align-items: center;
    border-radius: 20px;
    background: #fff;
  }
  .img-container {
    height: 160px;
  }
  .img-container img {
    width: 325px;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
  }
  .card-container {
    margin-top: 35px;
    text-align: center;
    width: 285px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .card-container p {
    margin: 20px auto;
    font-size: 14px;
  }
  /*Annual*/
  .annual-plan {
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #f8f9fe;
    padding: 20px;
    border-radius: 15px;
    height: 80px;
  }
  .annual-plan p {
    margin: 0 30px 0 15px;
    text-align: left;
  }
  .annual-plan a {
    font-weight: 700;
  }
  #annual-title {
    font-size: 1.2em;
    font-weight: 700;
    color: black;
  }
  button {
    margin: 0 auto 10px;
    width: 280px;
    height: 50px;
  }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I want to improve in breakpoints and responsive design. I wanna know how can I make my code more precise.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Break Points](https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp) - This helped me for the responsiveness of the website.
- [Utopia](https://utopia.fyi/type/calculator?c=375,14,1.2,1440,16,1.2,5,2,&s=0.75|0.5|0.25,1.5|2|3|4|6,s-l&g=s,l,xl,12) - This website helped me in sizing my fonts and containers.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@HouR-Bean](https://www.frontendmentor.io/profile/HouR-BeaN)
- Twitter - [@arvndlr](https://www.twitter.com/arvndlr)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Most probably you will face challenges in breakpoints and design. So my technique in figma is I import the design images and then measure the size of the box through rectangle. And in breakpoints I just change the values of the with, height and font sizes of the cards.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
