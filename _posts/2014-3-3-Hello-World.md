---
layout: post
title: Raspberry Pi Webserver
published: true
---
### Overview
My aim was to make a webserver on my raspberry pi to act as a central point of interaction for the household. I wished to be able to do stuff like host files that can be downloaded when needed, have a live weather report and to take advantage of the hardware capabilities of the pi by taking the temperature of at least one room. But, first to do any of this I had to create the webserver itself.

### Technology I used
To begin with I had to decide on what framework to base my webserver off of. The typical approach would be to use apache which will allow you to php scripting with a mySQL backend. While this is reliable and well documented and is the standard used in the industry I was hesitant to go this direction. This was because php is a language I am not familiar with and it is also one that is slowly losing popularity. While the latest php version has increased its speed dramatically and has prevented it from losing favour on those terms, it is also a language that mostly has one use case as well as having some well documented security flaws that overall turns me away from it. In comparison Python has proven to be very flexible, is decently fast and has many use cases that can easily be implemented into the website itself. As for whether to use Django or Flask, well I have had some experience in both and I have found flask much quicker to setup and far more useful for smaller scope projects so that was what I decided to use.




