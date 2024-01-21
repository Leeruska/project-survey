# READ ME

This is my test survey based on my excercise on the FreeCodeCamp course.

## Table of contents

- [Overview](#overview)
    - [Links](#links)
- [Process](#process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## Overview

Made this project to learn more about CSS and basic html. I based the project on what I did on FreeCodeCamp excercise, but in that one I mistakenly pressed "submit" before making any CSS. So I wanted to build this again based on that.
This form doesn't collet any data anywhere.

### Links

- Finished project in GitHub Pages URL: [https://leeruska.github.io/project-survey/](https://leeruska.github.io/project-survey/)

## Process

### Built with
- HTML
- CSS

### What I learned

I haven't added a background image before, so adding it from my own photos and making it behave as I wanted was a challenge. I got good help from W3schools site: https://www.w3schools.com/cssref/pr_background-image.php

I also had a problem for the background image not showing on the Github Pages, while "it worked on my computer" (classic). I resolved it by changing the original:
```css
  background-image: url(/images/lights.JPG)
```

to this:
```css
  background-image: url("../images/lights.JPG")
```

While troubleshooting that I also learned, that Github Pages is case sensitive. Good to remember in the future projects!


I wanted to get the input fields for "Name", "Email" and "Age" to align, and I found te answers in here very helpfull: https://stackoverflow.com/questions/10868640/align-html-input-fields-by

I just needed to make the labels for them separated from the rest of the form, and I did with "class" called "fix".

## Continued development

I still want to get the radio & checkboxes to align with the text better, because now it looks like they are on a different level.

Other improvements I would do:
- make a confirmation page after submitting the survey
- get the survey to actually save data somewhere, but that I won't make public for security and safety reasons.
- getting the "Other" input field to be on the same line with the label, the fix for the first input fields messed it up.

## Author

I am Veera, a beginner with HTML & CSS and coding in general. Check my profiles in:
- Github - [@Leeruska](https://github.com/Leeruska)
- Frontend Mentor - [@Leeruska](https://www.frontendmentor.io/profile/Leeruska)
- Freecode Camp - [@Leeruska](https://www.freecodecamp.org/fcc51b5d19d-b2b9-44f3-b98d-0e8cf194ad8b)
- LinkedIn - (https://www.linkedin.com/in/niemiveera/)


## Acknowledgements

Thanks for Frontend Mentor for this good ReadMe template.
Thanks for FreeCodeCamp for the course to learn HTML and CSS
Thank for [W3Schools](https://www.w3schools.com/) and [Stackoverflow](https://stackoverflow.com/) for helping me through the problems.
