---
title: Brian Edgar Web Pages
layout: default
---
# Brian Edgar's website

{:toc}

## My Web Apps
### [Korero](https://bwedgar.github.io/korero) A web app for learning Te Reo. 
### [Push To Telescope](https://bwedgar.github.io/PushToTelescope) A web app for finding celestial objects using a Dobsonian mounted Telescope
### [Slide Show](https://bwedgar.github.io/slideshow) A web app that will make a slide show of photos from the photo folder and allow Spotify to play while the iphone is mirrored to a TV.

## Writting Web Apps

###  GitHub
After too many times of losing code I started using GitHub to store my code in March 2019.  I write code using the Atom editor.  I use GitHub Desktop on a MacBook Air rather than command line instructions. I am writing my own [guide](github.md) to how GitHub works so I can remember it.
I have the CodeHub app on my iPhone which lets me edit any GitHub file away from my computer.
### Tools
I code web apps using HTML5, Javascript and CSS.  I used to use Coffeescript, JQuery and JQuery Mobile until 2017 but found they are not really needed with the updated JS version.   
### Making a web app available offline.  
I used the code from [medium.com](https://medium.com/@onejohi/offline-web-apps-using-local-storage-and-service-workers-5d40467117b9)
This uses a service worker to cache the files the web app needs to run. (This replaces the Cache Manifest I have previously used)
I found that the code to register the service worker has to be moved to the DOMload event in index.html or it does not run. The reference to the location has to be correct [see](https://gist.github.com/kosamari/7c5d1e8449b2fbc97d372675f16b566e)
### Icons
I make icons for the web apps using the online drawing program [Pixilart](https://www.pixilart.com/draw).  I save the icons as 100X100.
I include a manifest.json file.  I include the code that iOS needs to make a web app.
### This Web site
I write this site using the [markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) provided by GitHub. This allows links, content and formatting without having to write HTML tags. So much easier.

## Coding sounds
I became interesting in making sounds using code in 2019.  This was mainly motivated with using a web app to control my model railway using audio modulated infrared signals.  It occurred to me that audio effects could be made by the same web app.
### Bird Songs
Birdsongs are analysed and reproduced using Web Audio API [Coding Bird Songs](birdsongs.md).
### Sound effects
I am writing a [web app](soundeffects.md) to make sound effects for my model railway.  These ideas are based on [go](https://noisehack.com/generate-noise-web-audio-api)
### WebAudio test
This is a way of testing if a device can use Web Audio API. [test](https://bwedgar.github.io/WebAudioTest)
### Synthetic Māori voice. 
I have written a mespeakmaori.js to change written maori language into spoken.  I use the formant synthesiser at [mespeak](https://www.masswerk.at/mespeak/) with code to produce the necessary phonemes and stressed syllables.  I did not use the option of coding a voice as I could not understand how to do this. This is part of my korero web app and can also be accessed at [mespeakmaori](https://bwedgar.github.io/mespeakmaori)

## Astronomy
### My Telescope
I bought a short focus 6 inch equatorial mounted telescope around 1995 when I was less informed about telescopes than I am now. I found this hard to carry around with its heavy equatorial mechanism and tripod and it was hard to get a comfortable viewing angle. I then modified the mount to make an alt-az mounting as I had no need to track stars or use the setting circles to find stars. This made it easier to use but still not very portable; I did not use it much. Lately I got rid of the tripod and gearing by building a dobsonian mounting. I had some formica offcuts from a bench I had made, some 18 mm plywood left over from building and some teflon blocks I had got from a plastics shop years ago. I used the excellent instructions on the [Stellafane site](https://stellafane.org/tm/dob/index.html). The finished product exceeded my expectations. It is easy to use and I expect to spend more time with my telescope.  [photo](img)
### Web sites
[Atlas of the Universe](http://www.atlasoftheuniverse.com/index.html)
### My Push To Telescope web-app
#### [Push To Telescope](https://bwedgar.github.io/PushToTelescope)
#### [Go to Push To Telescope page](pushToTelescope.md)


## Model Making
### Model Rail
I had a 4x8 foot table top train set from Triang when I was a child. It must have been their [TT scale](https://en.m.wikipedia.org/wiki/TT_scale). My grandparents had an old [Lionel train set](https://en.m.wikipedia.org/wiki/Lionel_Corporation). The three rail system gave a painful electric shock! I would set this up on the carpet of their downstairs room and had many happy days surrounded by the heady fumes of “carbon tet”.

I have been an “armchair modeller” for many years. In October 2017 I bought some [angle brace](http://www.miteknz.co.nz/Products/LUMBERLOK-Timber-Connectors/Bracing-Products/Angle-Brace/) to make a frame. I only put it together in February 2019.
The aim is to have all the electronics, lighting and mechanical parts in the frame and have several models that can fit in the frame, so saving space and allowing different scenery.
I also plan to 3D print my engines and rolling stock. This suggest using battery powered engines.
#### Frame
![image](/images/modelRailFrame.png)

Angle brace cutting table

length no.|1.32mm|0.8mm|0.38mm	|0.14mm|TOTAL mm
----------|--------|--------|---------|-------|--------
2|1|2|1|2|3.68
3|1	|2|2||3.68
4|1|2|2||3.68
5|1	|2|2||3.68

## 3D Printing
I use a MakerBot Replicator 2 to print models. I create my objects using code written with [OpenScad](http://www.openscad.org/). I keep my OpenScad code on my OpenScad repository on GitHub.  I share my objects on [Thingiverse](https://www.thingiverse.com/bwedgar/designs).

## Electronics
I have been interested in electronics since childhood when I got a [Phillips electronics set](https://m.youtube.com/watch?v=h1TII3Z-jXk).
### Picaxe
I use Picaxe microprocessors. These come in various sizes from 8 legs to many more. They are programmed in BASIC from a PC.  
My picaxe programs are in GitHub repo [Picaxe](picaxe.md).
#### Model Rail Frame Controller
This takes input from a smart device and controls engines, lights, mechanical devices.
#### Infrared Serial Data Transmitter Web app
This web app allows a computer or mobile device to send serial signals to a picaxe computer (or Sony TV). It is based on a circuit by ???.  [Run the Web App](https://bwedgar.github.io/InfraRedSerialTransmitter)



