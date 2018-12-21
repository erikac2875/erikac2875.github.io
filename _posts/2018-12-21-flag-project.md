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

-  Strategies I used to work in this program were writing code that I know first and looking through new tools that will help me with my flag. For examples rotating it. I wasn't able to find it on the guides for Pyret, but I asked one of my classmates 
( https://masonm6137.github.io/blog/ ) for help. I asked him, "how did you rotated a Star to 160 degrees? because I was having trouble rotating it". I also I asked another classmate ( https://oliviae5741.github.io/blog/ ) for help, on how can I can keep the all pieces together while the flag changes to another sized. This was one of my biggest challenges out of this project, but at last got it. My flag seems finish but I am still finishing some small details, even if I was working on this project out of class, it was challenging. 

## Explain your code.

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

-   The code I posted is the part the manages the colors of the figures that are using their code, and the width and height. Each of this figured have unique letters that represent them. This 10 lines can change anytime. If they change then the other line that has this code will change too. This lines make it easier that way we don't have to go through all the code and change the same code multiple times. If we change the size of the flag, which is the first line, then the flag will change to the number but the flag will look the same because of the width and height. The numbers are calculated correctly. This shows the flag can be any size you want it to be. The color has its own letter, instead of writing the whole name of the color, we just have to write it once and just write the letter that represents it. Not all figures will be the same on the flag some will have to divide with only height or width, I used height 
-  For this code to be able to work they need to have a sized to multiply and then divide. There is a figured that needs hight and width that way it will be controlled by sized which helps the rest of the figures connected to it stay with the sized that is added to it and make the flag look the same only different size.

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
