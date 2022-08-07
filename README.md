# The Odin Project Sign-Up-Form project

This is a solution to the [The Odin Project Sign-Up-Form project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form). It is for helping me improve my coding skills by building realistic projects. 

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

- Sign-up form should be client-side validated,
- With optimal layout a cross different screen size devices

### Screenshot

!![Screenshot 2022-08-07 at 09-48-09 Sign-Up-Form](https://user-images.githubusercontent.com/57036823/183278003-e43d0ff1-1994-48aa-86d1-630e447f533b.png)




### Links

- Solution URL:https://github.com/tmoris/Sign-Up-Form
- Live Site URL:https://tmoris.github.io/Sign-Up-Form/

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
-Scss



### What I learned

While working on this project i have learnt
how to:- use CSS grid for styling page  and create reponsive layouts.
organize work using scss partial files, use of mixins and accessing of scss variables using @use.
I have also leart client-side form validations.


For code snippets examples, see below:

```Scss 
.form-control {
  inline-size: 100%;
    padding: 0.35em 1em;
    background-color: var.$clr-GrayishBlue;
    border-radius: 0.25em;
    border: 0;
    border-block-end: 0.0635em solid var.$black;
    opacity: 0.6;

 &:invalid:not(:focus):not(:placeholder-shown) {
      border: 0.0635em solid var.$red;
      background-image: url("../css/imgs/close-circle.svg");
      background-position: 98%;
      background-repeat: no-repeat;
      background-color: var.$red-light;

      &~.small-text {
        display: block;
        color: var.$red;
        padding-block-start: 0.5em;
      }
    }
}



### Useful resources
-[theodinproject](https://www.theodinproject.com)-This is helping me learn programming and codding.
- [web.dev](https://web.dev/learn/css/) - This helped me learn mordern CSS techniques. I really liked the content and will use it going forward.
- [kevinpowell](https://courses.kevinpowell.co/conquering-responsive-layouts) - This is an amazing course which helped me finally understand responsive web design. I'd recommend it to anyone still learning this concept.

###Continued Development
-currently, am continueing to develop and polish my coding skills in website development


## Author

- Github - [@tmoris]https://github.com/tmoris
- Frontend Mentor - [@tmoris](https://www.frontendmentor.io/profile/tmoris)
- Twitter - [@tibenkanamoris](https://www.twitter.com/tibenkanamoris)

