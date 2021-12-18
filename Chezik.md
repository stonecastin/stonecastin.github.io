---
layout: page
title: Reformatting Chezik et al (2017)
---

Chezik et al 2017 is an analysis of rivers' ability to mitigate the effects of climate change.
I was interested in this paper as it uses the spatial analysis package rgdal, which I can use in my thesis.

I got stuck on the part in the original code where the author mentioned file directories.
This is a part of rgdal, which can't cooperate with the here package.
This meant that the code could only run properly on the author's computer, and nowhere else.
In trying to find the file I've looked back at the paper, and I assume it is a shapefile of the Fraser watershed.

In reformatting the code I learned to use the "here" package to indicate file loading and saving locations, in addition to workarounds in rgdal.
Originally, the rgdal commands were formatted to provide a complete directory to the files on the author's computer.
To fix this, I had to change the working directory in each rgdal function to be in the folder the data was in.
This change, in addition to the use of here functions, made the code completely reproducible on a direct download from the github repository.
I will be using the here package to make my thesis analysis reproducible in the same manner.

With the time left in the semester I was unable to complete the reformatting.
With the code as it is, only aobut a third is functioning, and I still haven't found the elevation data that the code refers to. 
