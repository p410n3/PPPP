# PPPP
PayPal Peeping Protection - PPPP

## Protects you from Peeping Persons trying to read your KBA Questions on PayPal

PayPal offers this feature that allows you to answer KBA like security questions if you cant use your phone for 2FA. This is great if your phone is out of battery of course, but whatever answer you write into the input fields is *NOT MASKED*. So anyone looking at your screen can read what you wrote. That sucks.

To combat this I made this bookmarklet. To go from this:

![img1](img/1.png)

To this:

![img2](img/2.png)

## Installation

1) Click the link that says 'PPPP' down there.
2) Select **all the text** you see.
3) Drag the marked text into your browsers Bookmark bar. (You can rename it, but dont change the URL) 

[PPPP](https://raw.githubusercontent.com/p410n3/PPPP/master/pppp.js)

To use the PPPP, click on the bookmarklet when you are on the Security Question Page at PayPal.

## FAQ

Q: Why not as a UserScript for Tampermonkey, this way I dont have to press a button.

A: Two reasons: PayPal uses CSP, so it didn't work, and UserScript 
   have an autoupdate feature, which means you have to trust me to 
   not steal your PayPal credentials afetr an update.

Q: In which browsers does this work?

A: Does work in Chromium, does not work in FireFox due to CSP restrictions

Q: You should never use KBA in the first place!

A: But if you have to, it's a bit more secure now.
