+++
title = "Build Notes Nlc Lux"
date = "2023-02-15T22:56:09-05:00"
author = "Eugene Huo"
authorTwitter = "" #do not include @
cover = ""
tags = ["notes", "nlc"]
keywords = ["", ""]
description = "Build notes for the nonlinearcircuits LUX module"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++
This is a pretty unique and simple module consisting of two light sensitive photodiodes producing CV outputs depending on how much light they receive. The gain can be increased by increasing the value of the gain resistor.

I made a video using two lux modules to simulate some bird songs, using them like a kind of optical theremin.

[Making Bird Sounds and Songs with Eurorack](https://youtu.be/6OflJaoHDFE)

**Build Notes:**

\- I experimented with 4 different values of gain resistor: 1M, 2.2M, 3.0M and 4.7M Ohms which will be useful in giving a different response under the same lighting conditions, or to choose one to use depending on how bright or dark the performance environment is

\- upon testing I thought I had messed it up somehow because the CV outputs were extremely 'dirty', when I used them in a 1v/oct VCO input the sounds was very noisy. I realized that it was actually the lights causing the noise, because I have LED pot lights in my house and they must be flickering and causing the CV output to look like a square wave! Shining a flashlight with an incandescent bulb on the modules resulted in a smooth tone with no noise. Fascinating!

\- this is a build involving SMD components, including a SOIC TL072. I used the iron for this one, I'll probably break out the paste and air for a more involved build. It is a pretty good first time module for SMD, as it doesn't have very many components at all.
