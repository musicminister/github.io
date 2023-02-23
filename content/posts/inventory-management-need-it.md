+++
title = "Inventory Management Need It"
date = "2023-02-23T14:03:45-05:00"
author = "Eugene Huo"
authorTwitter = "" #do not include @
cover = ""
tags = ["review", "organization"]
keywords = ["", ""]
description = "Do you need inventory management for your DIY components?"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++
## A review of [partsbox.io](http://partsbox.io)

"For every minute spent organizing, an hour is earned" - Anon.

When I started with DIY keeping track of components was pretty simple, the parts all came with the kits! But after branching out into sourcing components on my own, I definitely started thinking about how to organize things. 

Abe over at AI Synthesis recommends the "bags in bags" method of parts storage, which is mostly how I do it. [Check out the method as he describes it on his site](https://aisynthesis.com/how-to-store-diy-synth-parts/). So that's how to store things, but I quickly realized that I wanted to have a way to know where and how many of each part I had on hand, so that I could know before I started a build that I had all the parts on hand, without having to do a manual search for each item on the Bill of Materials (or BOM).

This is where 'inventory management' comes in. Do a google and you'll find a lot of solutions for inventory management, but there are are only a handful that are geared towards hobbyist electronics DIY'ers. And of those handful, only one has a free tier that isn't limited in the areas where it counts: [partsbox.io](http://partsbox.io).

The role of inventory management is relatively simple but powerful. You enter the parts as you receive them, tracking the name of the part, the number of parts, how much they cost (that's optional but useful), and which storage 'container' they are in. So a new entry would look something like: 1K Ohm 1/4W Metal Film Resistor, 100 units at $0.03 each, in the "ones" resistor bag.

Partsbox also allows the connection of a USB handheld scanner like the kind they use at checkout counters, which are surprisingly cheap to buy online. Any old one will do, and if the part comes in a package with a barcode (like from mouser, for example) then scanning and entering new parts is pretty efficient. Parts from tayda or elsewhere without a barcode will require manual input of the part name. Partsbox offers a the ability to search for a part using Octapart, and you can enter a specific part that way. For example, a resistor made by Taiyo Yuden. Or you can choose to just enter a generic part name, like in my example above, if you will be sourcing the same components from different manufacturers. The ubiquitous 1K resistor really doesn't need a super specific entry.

Once a part is entered into the system, you are able to see your stock levels, where a part is stored, and even a running tally of the value of your parts that you have on hand. But where the real power of system comes in is creating projects and tracking builds.

Each Project in partsbox, for me, is one eurorack module. Fill in the BOM for the project, and partsbox can then know how many of whichever component is needed for that project. Then when you click the "Build" button, partsbox will compare the BOM against the inventory, let you know if you have all the parts needed, and if not it will alert you as to which parts and how many you need to buy. If you have all the parts on hand, confirming the build will take those parts out of inventory and commit them to the build.

So I don't have to wonder if I have enough TL072 chips on hand to make the next module, I can just check the project and it will let me know. It will even tally the cost of the components used in any particular project, if you want to know how much is being sunk into any given module.

I also don't have to speculatively buy extra components in the hope that 'someday' I might use them, I can just get the parts that are needed. Of course knowing that buying in bulk usually saves money, partsbox can also show you how many of what component is used in every project, so you can have that information when you make your order.

Are there any cons? There is a time component, of course, entering components is time consuming, especially if you have a lot of parts on hand to start with. It would be ideal to get into something like this from the beginning, so that you enter as you receive parts. You'll have to factor in whether the time doing the initial inventory will be worth the payoff in the end.

The free tier doesn't support automatic ordering, which sounds really cool. You also can't just import a BOM from, say, a CSV file, unless it came from KiCad first.

Even with these limitations, I'm finding the information that partsbox gives me to be invaluable, and it is streamlining my ordering to the correct amount of any given component that I need.

It's amazing that they've kept it free for single user hobbyist types like me, and I hope this mini-review encourages you to give it a try.

Got questions? Leave me a comment and I'll try to answer them!
