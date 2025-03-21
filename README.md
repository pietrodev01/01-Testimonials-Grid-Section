What I learned:

- If you want a grid items height to be the size of its content use auto in grid-template-rows(5, auto).

- Their should be no space in between repeat and the bracket in -> repeat(4, minmax(255px, 1fr)). This was ruining my grid and it took me 15 minutes to figure it out.

- To get the overlapping text both the element with the text and the images parent element need to be set to relative if you are positioning the images using position: absolute.

![screenshot](screenshot.png)
