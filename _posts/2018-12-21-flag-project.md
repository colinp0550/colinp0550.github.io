---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Pakistan by Colin Powlett

## Describe your program

-   What country did you design for? 
    I designed for Pakistan.
-   What grade do you expect? 
    I expect a grade of apprentice or practitioner because I worked very hard on the project, and when i had questions, I used all of my resources on trying to answer them. 


## Current output


* * *
![Flag](/images/pakistan-flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? 

I only had a few questions, so when they got answered they helped me out tremendously. Ine question was "How to insert an image onto a github file". Marlon also really helped me out. He showed me without telling me the exact answers, how to create the moon shape wihout using the overlap code.


## Explain your code.

RR=rectangle(500, 300, "solid", "dark green")
YC=circle(100, "solid", "white")
BC=place-image(YC, 250, 150, RR) 
GC=circle(100, "solid", "dark green")
place-image(GC, 270, 120, BC )



The rectangle argument creates a dark green rectangle. The circle argument creates a solid white circle which then I use BC to place the image of the circle onto a specific part of the rectangle. The other circle function, GC, creates a solid dark green circle, which is placed over the white circle to create a cresent moon.

* * *

```
include image
RR=rectangle(500, 300, "solid", "dark green")
YC=circle(100, "solid", "white")
BC=place-image(YC, 250, 150, RR) 
GC=circle(100, "solid", "dark green")
place-image(GC, 270, 120, BC )
ST=star(75, "solid", "white")
place-image(ST, 342, 100, ST)
place-image(ST, 342, 120, RR)
GT=star(80, "solid", "white")
```

* * *

The rectangle argument creates a dark green rectangle. The circle argument creates a solid white circle which then I use BC to place the image of the circle onto a specific part of the rectangle. The other circle function, GC, creates a solid dark green circle, which is placed over the white circle to create a cresent moon. The star argument is used to create a solid wite star that will be placed right next to the cresent moon. I was never able to figure out exactly how to do it. The other place images and star function are some of m other attempts at placing it upon the rest of the flag.
 
<!--- Delete this comment and add your writing -->


## Program code

```
include image
RR=rectangle(500, 300, "solid", "dark green")
YC=circle(100, "solid", "white")
BC=place-image(YC, 250, 150, RR) 
GC=circle(100, "solid", "dark green")
place-image(GC, 270, 120, BC )
ST=star(75, "solid", "white")
place-image(ST, 342, 100, ST)
place-image(ST, 342, 120, RR)
GT=star(80, "solid", "white")
```
