# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/solution.png)

### Links

- Live Site URL: [Vercel](https://product-preview-card-component-ivory-three.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass pre-processor tool

### What I learned

```css
@mixin flex() {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
@mixin flexAlt() {
    display: flex;
    align-items: center;
}
@mixin spacing() {
    margin: 1rem;
    padding: 1rem;
}
```
```js
$(document).ready(function() {
    $("button").click(function() {
        $("button").css("background-color", "red");
    });
});
```

In this project, I learned how to use jQueries as a better alternative to DOM queries. I didn't know how to implement jQueries, as I didn't know where to download the source file and how to connect it to my code. Furthermore, I gained experience with Sass since I'm working with vanilla css. Sass allows me to use mixins to not have to re-write multiple lines of code and it displays nesting in a similar manner to an html document. Sass also offers global variables which I took advatange of, but vanilla css has had this feature so it's not something new for me.

### Continued development

In the future, I would like to enhance my knowlege of jQueries and apply them to various different situations. I am fairly familiar with DOM queries, but I still need to get more comfortable with the syntax regarding jQueries. Another thing I would like to learn and enhance is my knowledge about responsive design. In this project I learned about the clamp() function which reduces the need for using multiple media queries. However, there is still a lot of other techniques I can apply to the content within my webpage such as images or typography to allow it to better scale at different resolutions without manual intervention. Lastly, I would like to learn about Tailwind CSS so that I can streamline the design for my webpage without needing a seperate CSS stylesheet.

### Useful resources

- [How to download jQuery YT tutorial](https://www.youtube.com/watch?v=s6Q7xY25loA) - I was initially having issues using jQueries within my script.js file and noticed an error within terminal. So, I found this video helpful as I did not know I needed to download a file for jQueries nor did I know how to add it to my code.
- [W3Schools](https://www.w3schools.com/jquery/jquery_css.asp) - This webpage helped me understand how I can put jQueries into practice for events such as click events.
- [Media Queries Alternative YT video](https://www.youtube.com/watch?v=pYW3O0AxpI8) - This video helped me understand a more efficient alternative to media queries such as using min(), max(), and clamp(). I used clamp throughout my css stylesheet to avoid using multiple media queries.

## Author

- Frontend Mentor - [@JoshuaM04](https://www.frontendmentor.io/profile/JoshuaM04)