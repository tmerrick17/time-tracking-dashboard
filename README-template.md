# Frontend Mentor - Time tracking dashboard solution

This is a solution to the [Time tracking dashboard challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/time-tracking-dashboard-UIQ7167Jw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Switch between viewing Daily, Weekly, and Monthly stats

### Screenshot

![](/design/screenshot-mobile.png)
![](/design/screenshot-desktop.png)

### Links

- Solution URL: [Solution URL](https://your-solution-url.com)
- Live Site URL: [Live site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Vanilla Javascript
- Mobile-first workflow
- Gulp setup

### What I learned

This one really put my beginner JS skills to the test.  I actually went and sought out different solutions that people did in their project and found the one that had a start to it.  I say start in that I saw a lot of repetitive code and even though I'm still in the early stages of learning JS, I know that the one thing in most languages that you can do is create functions to help get rid of repetitive code...so I asked Stack Overflow and got some great answers that helped me shorten the code up.  Below is an example of some of the JS...

```js
function getHoursAndPast (title) {
  var lowerTitle = title.toLowerCase();
  var hours = document.getElementById("hours-" + lowerTitle)
  var past = document.getElementById("past-" + lowerTitle)
  return [hours, past]
}
```
This code above helps me get the id's that I need to be dynamic so that I can use it later in a forEach function

### Continued development

I need to continue working on all things JS.  Period...but I still love Sass and working with getting better at CSS.  I still want to also play with functions and mixins in SASS.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/71544469/is-there-a-way-to-refactor-this-javascript-for-loop/71544744#71544744) - This was super useful in finding out how to refactor my code.

## Author

- Website - [Trevor Merrick](https://trevormerrick.com)
- LinkedIn - [@trevormerrick](https://www.linkedin.com/in/trevormerrick/)
- GitHub - [@tmerrick17](https://github.com/tmerrick17/)
- Frontend Mentor - [@tmerrick17](https://www.frontendmentor.io/profile/tmerrick17)
- Twitter - [@tcmerrick](https://www.twitter.com/tcmerrick)

## Acknowledgments

I would like to give acknowledgment to my college teacher Matt Steiner.  He has been helping me learn how to trouble shoot JS and use the console more in my web browser.  He is a great mentor.
