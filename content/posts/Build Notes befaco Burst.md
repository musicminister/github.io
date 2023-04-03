Title: Synth DIY Space posts  
Author:

# Build Notes: Befaco Burst #

I really want to love Befaco. They're based in Barcelona, my favourite city in the world. They make cool modules, and they encourage diy. But maybe it's a result of me not reading the BOM carefully enough, but I've just had the most frustrating time with sourcing parts. First I didn't realize that the resistors were 1/8W, and I only had 1/4W ones on hand. Then the pots that they use are a special kind. The sliders are special. The toggle switches were not the ones I had on hand.

A lot of this is solved by buying parts directly from Befaco, but shipping from Spain isn't cheap, or it isn't fast. I understand that you design boards around certain parts, and so much of my frustration is on me not knowing which parts to order, or assuming that what I had was the right one.

So this build was done in stages, while I waited for parts to arrive from Spain. And just when I thought I had completed the whole thing, I realized that I had to program the ATMega 328P IC, so I had to order a USB programming adaptor and I'll try to do that another day. Fortunately the firmware can be gotten from Befaco's GitHub repository, so that's easy enough.

Build Notes:

\- learning to read the BOM, but then looking at the physical board to make sure lead spacing is correct, pin configurations are what you expect, and so on, will save many of my headaches

\- if you're going to buy a bare ATMega328P chip for this, you'll need to program it for the BURST to work, as I learned when I tried to turn it on and found that it didn't do anything

\- I ordered this: <https://a.co/d/8PbcyUJ> USB ASP Programmer

\- if you're going to DIY Befaco you should bite the bullet and order the unique parts from them in quantity, so that you just have them, mostly potentiometers and sliders, and if you want the fancy anodized jack nuts

\- the board layout and shape itself if a work of art, seriously. Very pleasing to stare at once completed.
