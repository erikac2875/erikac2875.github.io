---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Tunisia by Erika Chunzho

## Describe your program

-   The country I design it for was Africa because thats where Tunisia is located. I want for them to aprove if its functual, for everyone to use it. That way everyone else will be able to use the flag. This flag took almost a week to make it. 
-    For this project I'll expect a four because I work hard. I looked for different ways to place this flag together. It was exciting creating a flag, step by step. It was challenging, but it was fun looking for different ways to build it together. 

## Current output


* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? 



## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
size = 200
width =  size * 3  
height = size * 2 

H = height / 2
W = width / 2


Red = color(231, 0, 19, 1)
white-c = color(255, 255, 255, 1)

R = rectangle(width, height, "solid", Red )

circle-1 = height / 4

star-1 = height / 6
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
include image
include image-structs 

size = 200
width =  size * 3  
height = size * 2 

H = height / 2
W = width / 2


Red = color(231, 0, 19, 1)
white-c = color(255, 255, 255, 1)

R = rectangle(width, height, "solid", Red )

circle-1 = height / 4

star-1 = height / 6


c = circle( circle-1, "solid", white-c)
pi = place-image(c, W , H , R)

c2 = circle(circle-1 * 0.85, "solid", red)
pi2 = place-image(c2, W, H, pi)

c3 = circle(circle-1 * 0.70, "solid", white-c)
pi3 = place-image(c3, W * 1.07, H * 1.0, pi2)

S = star(star-1, "solid", red)
S2 = rotate(160, S)
flag = place-image(S2, W * 1.09, H , pi3)
```
