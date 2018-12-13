---
layout: post
title: "Weekly #11: Flag-Project-In process"
date: 2018-12-13
---
![Flag image](/images/Flag3.png)

\\\ 
include image <br/>

size = 200 <br/>
width =  size * 3 <br/>
height = size * 2 <br/>
H2 = (height / 2) <br/>
W3 = (width / 2) <br/>
C8 = (width / 1.25) - (height / 2) <br/>
C9 = (width / 1.15) - (height / 2) <br/>
S3 = (width / 1.10) - (height / 2) <br/>

#------ <br/>
R = rectangle(width, height, "solid", "red") <br/>
C = circle(140, "solid", "white") <br/>
E = circle(100, "solid", "red") <br/>
C3 = circle(80, "solid", "white") <br/>
S = star(80, "solid", "red") <br/>
S2 = rotate(160, S) <br/>

#-------- <br/>
RC = place-image(C,W3, H2, R) <br/>
C5 = place-image(E,C8, H2, RC) <br/>
C7 = place-image(C3,C9, H2, C5) <br/>
Flag = place-image(S2,S3, H2, C7) <br/> 
\\\ <br/>

