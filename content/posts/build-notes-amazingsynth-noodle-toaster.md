+++
title = "Build Notes Amazing Synth Noodle Toaster"
date = "2023-02-08T15:03:09-05:00"
author = "Eugene Huo"
authorTwitter = "" #do not include @
cover = ""
tags = ["notes", ""]
keywords = ["", ""]
description = "Build notes for the MI Module Tester board and acrylic case from Amazing Synth"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
draft = false
+++

The Amazing Synth Noodle Toaster is an iteration on the [Mutable Instruments Module Tester](https://pichenettes.github.io/mutable-instruments-diy-archive/module_tester/) designed by Émilie Gillet.

> Several problems were faced during the development of our Eurorack modules:
>
> - How to power and test a module during development? Bench-top power supplies are cumbersome (especially for projects requiring 3 supply rails) and standard test equipment is sometimes useless or frustrating for quantities like musical notes or V/Oct scales. On the other extreme of the scale, who would run the risk of putting a half-built prototype in a rack loaded with thousands of euros worth of modules?
>
> - What kind of setup to use for factory testing?
>
> - How to take a project away from the lab without carrying heaps of "dependencies"?
>
> We solved this the Mutable Instruments way, rolling up our sleeves and designing a simple box able to provide power and all kinds of test signals (clocks, gates, CVs, audio tones) to a module. This tool is made available under cc-by-sa (hardware) and GPL (firmware) licenses.

Amazing Synth in the UK have taken this design and produced a nice clone of the PCB, as well as a custom fitted case made from cut acrylic, in various colours.

I spent a very enjoyable day putting this together. I have since used it to test a VCA module that I put together, and it would make light work of VCO calibration, for example.

Build Notes:

\- I chose the wrong kind of pin header to attach the LCD screen, so mine is sitting up off the PCB supported only by the pins. Probably not a problem as long as I don't push hard on the screen. It's supposed to sit on the PCB, but I like it slightly raised as it's more visible through the opening in the case

\- The bourns trimmers on the upper right are quite tall and prevent the case from sitting down flat, it would be nice to maybe either have an opening for them so the case can screw down on the standoffs without pushing on the trimmer tops

\- the acrylic case has indented print labelling (a la D&D dice) so I filled them in with a white crayon, I think it looks nice, it pops against the blue colour

\- I made a mistake in putting it together, in that I did not fully fill with solder the joints for the power connector. I don't know why, I thought I could just partially solder them but the unit wouldn't power on when I tried it the first time. After fully filling the joints it powered on successfully

