# My fifth project and solution to the stats preview card component challenge over at [Frontend Mentor](https://www.frontendmentor.io/challenges)

## This was the assignment

![](./design/desktop-design.jpg)

## This is my solution

[Click here to see the live page](https://arthurpog.github.io/stats-preview-card-component/)

![](./design/my_solution.png)


I really thought I was not going to have any problems with this one. Boy, was I wrong. I wanted to use grids and have it over with in less than an hour. It took me 5 to finish the project and I had to fall back to using `flexbox` to put an end to my suffering. I then got stuck at a div creating a line under my images. After an hour of looking for solutions I realized that the culprit wasn't the div but rather the image. After going back to the basics that images are *inline* elements which gives them a little padding at the bottom as, I suppose, per one's browser's default settings. Anyway, after changing the `display` of the image elements to `block` I finally got it working.

I also used the `flex-direction: column;` for the first time and the `mix-blend-mode` property for the image, which was nice.

Unfortunately I was not able to recreate this layout using grids, but I will revisit the whole subject in detail in my next session, learn the basics properly and try again.
