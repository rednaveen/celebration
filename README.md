# Introduction

This page provides a quick way for displaying warm wishes(TV or large screens) to your loved ones for occations such as birthday, anniversary or any other customizable message. 

Note that this page uses plain js and html so any android tv should be able display it on built-in browser.

# Steps to cast to Android TV
* Open "Screen Sharing" on your Android-TV
* Open the celebration link on your laptop/desktop: [https://rednaveen.github.io/celebration/index.html?wishmsg=Happy%20Birthday!!](https://rednaveen.github.io/celebration/index.html?wish=Happy%20Birthday!&themetimeout=30)
* Once the animation starts click on 3 dots on right top corner of the Google Chrome browser.
* Click "Save and Share" option
* Next select "Cast", select your Android-TV(if the Android-TV is already visible and searching does not end, click on Stop and select the Android TV)

# Parameters accepted
Available parameters:
<pre>
?wish= Your custom message → Current: "[current value]"
&size= Font size (number) → Current: [current value]
&theme= 1=confetti, 2=balloons, 3=stars, 4=gifts, 5=fireworks, 6=hearts → Current: "[current value]"
Example: ?wish=Happy Birthday!&size=80&theme=2
</pre>

# Samples

## Theme changes every 10 seconds, cycling through all 6 themes URLs:
https://rednaveen.github.io/celebration/index.html?wish=Happy%20Birthday!&themetimeout=30

## Starts with confetti, changes every 5 seconds URLs:
https://rednaveen.github.io/celebration/index.html?wish=Congrats!&theme=1&themetimeout=30

##  Changes theme every 15 seconds
index.html?wish=Hello&size=80&themetimeout=30
