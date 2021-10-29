---
layout: page
title: Research
permalink: /research/
---

### Outer solar system ###
I developed a novel methodology for identifying trans-Neptunian objects (TNOs) in the temporally sparse data taken by the Dark Energy Survey. These planetesimals are distant objects in the outskirts of our solar system, and their orbital architecture trace the formation history of the giant planets.
As DES is not a solar system survey, this process is very challenging: we need to identify single-night transients (i.e. sources that only appear in one place in one night) and link detections into orbits, that are then confirmed by using images where the objects are not detected, but expected to be lurking below the detection threshold, by stacking such images. In the first four years (of six) of DES, I've identified 316 TNOs, with 139 of these being new discoveries. See [Bernardinelli et al 2020 ApJS 247 32](https://iopscience.iop.org/article/10.3847/1538-4365/ab6bd8) for details. If you're interested in our objects, you can download them in the journal or [here](/downloads/destno_main.fits).
{:refdef: style="text-align: center;"}
![316 TNOs in the first four years of DES](/images/map.png){:height="70%" width="70%"}
{: refdef}

With this data, I also examined our extreme trans-Neptunian objects, those with semi-major axes larger than 150 AU and perihelia larger than 30 AU. This particular type of object is interesting because they seem aligned, leading to the recent formulation of the Planet 9 hypothesis, a postulated giant planet very far from the Sun. Our analysis showed no statistically significant clustering, meaning that our objects can be explained without the need for an additional planet in the solar system. This analysis is presented in [Bernardinelli et al 2020 Planet. Sci. J. 1 28](https://iopscience.iop.org/article/10.3847/PSJ/ab9d80).
{:refdef: style="text-align: center;"}
![DES extreme TNOs](/images/etno.png){:height="70%" width="70%"}
{: refdef}

The more challenging search over the full six years of data from DES built upon our previous search, and led to an impressive total of 814 objects. This was an incredibly challenging search, as the computational time approached 20 million CPU-hours. In addition to the extra two years of data, we also had deeper catalogs due to some optimizations I developed for the DES image processing pipeline. I have also developed [survey simulation](https://github.com/bernardinelli/DESTNOSIM) software for DES, enabling statistical comparisons of theoretical models of the outer Solar System to our data. This analysis is presented in detail in [Bernardinelli et al 2021 - 2109.03758](https://arxiv.org/abs/2109.03758). The full catalog can be found [here](/downloads/y6_table.fits).
![813 Outer Solar System objects in the DES](/images/aei.png){:height="70%" width="70%"}
{: refdef}


As a part of this Year 6 search, we have found something quite unexpected, but really interesting: the comet C/2014 UN<sub>271</sub> (Bernardinelli-Bernstein). This object is fascinating by a number of reasons: it's a comet discovered at almost 30 au and, given how far it was in the first few DES images of it, it didn't show noticeable activity. It's also quite large for a comet, with a diameter estimated at about 150 km (depending on your choice of albedo, of course), making it one of the largest comets ever found! We have conducted a detailed study of its orbit, past dynamics and activity in a combination of DES + a few other surveys images of it from 2010 to 2020, presented in detail at [Bernardinelli, Bernstein et al 2021 - 2109.09852](https://arxiv.org/abs/2109.09852). 
![NoirLab press release image of Comet B-B](/images/cometbb.png){:height="70%" width="70%"}
{: refdef}

### Other ###
Inside DES, I also worked with the characterization of the atmospheric turbulence correlation for DECam exposures in order to better understand astrometric errors on our images. Besides that, I conducted a careful study on the detection efficiency in the DES pipeline, leading to a significant improvement in the recovery efficiency and completeness of DES exposures.

### Undergraduate ###
During my undergraduate years, I worked with prof. Raul Abramo with cosmological applications of supernovae Ia. Our main goal was to develop an observational strategy for the S-PLUS variability/SNe survey. I also worked with measurements of the atmospheric extinction coefficient using all-sky images inside the S-PLUS collaboration.

