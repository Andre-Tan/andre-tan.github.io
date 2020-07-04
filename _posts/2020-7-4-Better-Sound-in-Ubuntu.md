---
layout: post
title: Better Sound in Ubuntu
published: true 
categories:
    - ubuntu
tags:
    - sound
    - settings
    - tech tips
---

I bought a Dragonfly Black Digital-to-Analog Converter (DAC), a lower-tier version of the famous portable DAC Dragonfly Red. 

This DAC brought an abundant joy to the experience of listening to music in my Windows machine. Weirdly, the same thing cannot be said when I am listening on my Ubuntu machine at work. Considering that more than half of my active hours is spent at work, this pains me as I feel like I am not getting 100% of the thing I paid for.

My first hypothesis is that my Dragonfly is not compatible with Linux machines. Traversing through audio forums, I found that this is not the case. Dragonfly has drivers for Ubuntu. The fact that I can hear sounds coming out from my DAC also means that it does work (right?). 

Does this mean my sound card is bad? This is even less logical because my Ubuntu machine is priced at least 3 times as expensive as my Windows machine (which is a budget HP I bought during my student years). I know the price does not stand for itself here to the choice of sound card, but I do not remember my Windows machine having any special sound card so I believe they should at least be the same level. My Windows machine simply would not have better individual specification compared to my Ubuntu machine.  

 Does this then mean Windows render sound better than Ubuntu? Is this another case where Windows is better than Linux?
 
 Good thing this is not the case. The reason is simply that **Ubuntu default sound configuration is bad**. 
 
Rather than me explaining what to do, I think I better refer everyone to my primary reference: https://medium.com/@gamunu/enable-high-quality-audio-on-linux-6f16f3fe7e1f
 
 I am now happy with my sounds and I found new appreciation for my Dragonfly Black. I had planned to sell it and upgrade to a Dragonfly Red/Cobalt before I found this solution, but I think I will hold on to this DAC longer now that my music sounds as good as I expected.
 
 **Additional Note** 
 
 Later on, I also installed PulseEffects. It provides more customization to the sound setting (e.g., equalizer) which I like to play around with.
  
  PulseEffects sometimes break my sound output setting, though. There are times where I come into a Zoom call and I cannot hear anything, only to find the sound coming back after I redirected the sound to my Dragonfly on the sound output setting.
 
 Sound is always directed to my Dragonfly. However, I need to change it to another output and then return it to my Dragonfly to make the sound come back out from my target output (sort of re-redirecting the output).
 
 I think this is due to the sound being directed to PulseEffects to render before Dragonfly and it does not come up outside of PulseEffects GUI. 
 
 This is just a small annoyance and does not hamper the joy of listening to better-sounding music in my Ubuntu machine.