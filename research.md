---
layout: page
title: Research
pagination:
  enabled: true
---

# Research interests

## Circumgalactic Medium (CGM)

![]({{ site.url }}{{ site.baseurl }}/assets/images/KeckRidge.jpg)
Me, standing in front of the Keck telescopes at Mauna Kea, Hawaii.

I use the Keck telescopes to study the Circumgalactic Medium CGM) of galaxies that are at a redshift (z) = 2, which means light we see today left these galaxies something around 3 billion years after the Big Bang. The circumgalactic medium is like the atmosphere of a galaxy. You can look at Earth's atmosphere, see all this oxygen here and realize that oxygen doesn't last very long in the atmosphere, something must be producing it, which it is (all life on earth!), something very similar happens with the CGM. By looking at the contents of the CGM, you can tell what kind of star formation has happened in the galaxy in the past, and maybe what is happening right now! 

![]({{ site.url }}{{ site.baseurl }}/assets/images/Keck_Observing.jpg)
A typical observing night on Keck. The amount of zero sugar red bulls I can go through in a two/three night run is not healthy/recommended.

I use the Keck telescopes for my work, and use an instrument called the Keck Cosmic Web Imager to image the CGM around galaxies. Keck I and Keck II are two of the largest optical and infrared telescopes in the world. They are both segmented telescopes, which means they aren't one giant monolithic mirror, but made up of hexagonal segments that combine to form a large mirror.

![]({{ site.url }}{{ site.baseurl }}/assets/images/KeckMirror.jpg)
Me standing in front of just one of the Keck Mirror segments. Each segment is 1.8 meters in diameter. 


## Lunar Laser Ranging (APOLLO)

![]({{ site.url }}{{ site.baseurl }}/assets/images/APOLLO_Sensor.jpg)
This tiny little guy is an Avalanche Photodiode, and it is the main detector that measures the distance between Earth and Moon down to 1 mm!

APOLLO (the Apache Point Observatory Lunar Laser-ranging Operation) is an ongoing experiment at the 3.5m telescope located at the Apache Point Observatory in Southern New Mexico, near the town of Alamagordo. APOLLO shoots a large laser at the moon and bounces signals off the retroreflector arrays left on the moon by the Apollo (notice the difference in capitalization) astronauts during Apollo 11, 14 and 15 missions. APOLLO can also range two Russian rovers with retroreflector arrays on them, the Lunokhod-1 and Lunokhod-2. Measuring the Earth Moon distance is a test of general relativity. When predicting the orbit of the moon, we expect Einstein's General relativity to differ from Newton's relativity by about 10m. Since APOLLO can measure Earth moon distance down to 1 mm, the test can distinguish between the two theories down to 1 part in 10 to the fourth! So far, GR wins out!

For my work on APOLLO, I characterized and improved the timing resolution of the detectors deployed on site, making ranging more efficient and faster compared to before. I also wrote my own heat simulation to simulate the retroreflector arrays on the moon over the course of an Eclipse, where their reflecting capabilities go down significantly. My work showed this is due to presence of very fine lunar dust that has accumulated slowly over the course of many decades. 


## Point Spread Function Reconstruction (PSF-R)

![Photo credit: Sean Goebel]({{ site.url }}{{ site.baseurl }}/assets/images/goebel_4lasers.jpg "Photo credit: Sean Goebel")

The Keck All-sky Precision Adaptive Optics (KAPA) upgrade on Keck is an ongoing effort to upgrade the Adaptive Optics system at the Keck Telescopes. My work on KAPA relates to reconstructing Point Spread Functions (PSFs) for the Near Infrared Camera 2 (NIRC2) instrument on Keck. Simply put, a PSF just means "What does a star look like on a telescope"? If you have ever seen pictures from the Hubble Space Telescope, you might have noticed they have 4 point spikes coming out of them. If you have seen pictures from the James Webb Space Telescope, you might have noticed they have 6 point spikes! Why the difference? This is because of the shape of the mirrors and the support structure that holds them in place and obscures the view of the telescope. Hubble has a spherical mirror and the secondary mirror in front of it is held together by 4 supporting struts. This creates the classic 4 spike pattern because when focusing the light from a distant star.

KAPA will upgrade the laser on the Keck telescope to create 4 artificial Laser Guide stars instead of 1, providing improved performance assisted by a new Real Time Controller. My work on KAPA involved predicting a long exposure PSF from first principles, given our knowledge of the adaptive optics setup, telescope and various bits of information we can gather about the atmosphere on any given night. 

## Phase Retrieval for space based telescopes

While adaptive optics has been developed to correct for atmospheric distortions on the ground, theoretically it is the science of improving the quality of PSFs generated by a telescope system. In space, the imperfections of the PSF don't originate from the atmosphere, but from small misalignments in the optics and instruments of the telescope. I am currently working on implementing machine learning techniques to sense these imperfections, and correct them using a deformable mirror on space based telescope concepts. 

## Dwarf galaxies

Dwarf galaxies are some of the smallest galaxies in the universe. They are the most abundant galaxy by mass, and yet are difficult to study since they are hard to detect historically. However, modern surveys have greatly increased the number of known dwarf galaxies and we are starting to understand the importance of these tiny members in the evolution of the whole universe! I am currently investigating dwarf galaxies with really faint radio jets, caused by faint supermassive blackholes that are otherwise undetectable. By studying this faint class of supermassive blackholes, we can learn a great deal about how the most massive galaxies and supermassive blackholes grow and evolve from their ancient progenitors. 
