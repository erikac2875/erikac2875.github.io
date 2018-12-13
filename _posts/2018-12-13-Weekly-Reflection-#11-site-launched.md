---
layout: post
title: "Weekly Reflection #10, Launches Site"
date: 2018-12-13
---
![flag image](image/download.png.png)

\\\include image

size = 200
width =  size * 3  
height = size * 2 
H2 = (height / 2)
W3 = (width / 2)
C8 = (width / 1.25) - (height / 2)
C9 = (width / 1.15) - (height / 2)
S3 = (width / 1.10) - (height / 2)

#------
R = rectangle(width, height, "solid", "red")
C = circle(140, "solid", "white") 
E = circle(100, "solid", "red")
C3 = circle(80, "solid", "white")
S = star(80, "solid", "red")
S2 = rotate(160, S)

#--------
RC = place-image(C,W3, H2, R)
C5 = place-image(E,C8, H2, RC)
C7 = place-image(C3,C9, H2, C5)
Flag = place-image(S2,S3, H2, C7)\\\
