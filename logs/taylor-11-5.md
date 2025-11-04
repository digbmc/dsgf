---
title: November 5 Log
date: 2025-11-05
author: Charlie
---

# Updates for week of November 5

I just got back from the annual Byzantine Studies Conference, where I presented my MA project, including some maps!

## Project progress

Since my conference paper and this GIS project deal with the same subject, some last-minute additional research ahead of the conference proved very helpful for my mapping project.

### Determining locations of monasteries

My project deals with four icons in four Ethiopian monasteries. I was able to locate two of these monasteries on Google Maps without much trouble. Another monastery, named Getesmani Maryam, was mentioned in some academic publications, but proved difficult to find on Google Maps. Luckily, the *Encyclopedia Aethiopica* entry for Getesmani Maryam included coordinates: 11.10 N, 38.4 E. The last monastery, called Dabra Jamado Maryam, proved more illusive. I eventually determined that "Jamado" is an alternate transliteration of ዠመዱ, which is often instead transliterated as Žämmädu. (When the icons were first published in the early 70s, there was no standard system for transliterating Amharic and other Ethiopic languages.) I was able to find the location of Žämmädu Maryam on Google Maps.

### Gathering data and creating an initial map with ArcGIS online

With the locations of my monasteries finalized, I gathered the location data in a spreadsheet. I also included location data for the place of production of the icons (Candia/Herklion, Crete) and other sites that they may have treveled to before reaching Ethiopia. For each site, I included a column to specify whether the icons were *known* to have been at the site, or whether the connection is speculative. I then used this data to generate [a map with ArcGIS online](https://brynmawrcollege.maps.arcgis.com/apps/mapviewer/index.html?webmap=b87d035d6d864946ab5e09c2e4937f02). I used conditional styling so that the known sites appeared in green and the speculative sites in yellow.

## Next steps

### Move to ArcGIS Pro

At the moment, if sites are too close together, their labels do not appear. After some searching online, I think I've determined that there is no good workaround to this in ArcGIS online, but Pro has features that allow for overlapping labels.

### Mapping premodern geopolitical "boundaries"

I want to give my viewer a sense of the geopolitical boundaries that existed in this period (early 16th century), but these boundaries were unstable and in flux. I also have not been able to find a satisfactory map of 16th century Ethiopia, although I will continue searching. I will likely map these boundaries myself, with a polygon layer. Other projects, like [Native Land Digital](https://services6.arcgis.com/SC70xY1nSLm15pYn/arcgis/rest/services/Native_Land_Digital_territories/FeatureServer), have done so with great success.
