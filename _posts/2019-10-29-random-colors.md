---
layout: post
title: Random Colors
bigimg: /img/IMG_0330.JPG
tags: [programming, beginner, programmer]
---

This assignmemt involved working with Arduino and our Lilypad USB Plus boards.
The goal was to program the onboard RGB LED to display a random RGB color.
The light should only go on when the button is pressed and only turn off the button is not pressed.
Basically, the light should be on as long as the button is pressed and be a different color each time the button is pressed.

![One of the random colors](/img/IMG_0330.JPG){: .center-block :}

A trick I would pass on to my past self would be to remember the boolean statements!
My LED kept blinking while the button was pressed, so I realized that I needed to include a boolean to turn the light on.
Thus, I could alternate between the Light On being true and the Light On being false, which was very helpful in my final product.
