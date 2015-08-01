---
layout: default
title: publications
---

## Mapping recipes

#### Contents
* The basics
    * [Choosing colour palettes](/mapping/colour_palettes.html)
    * [Creating continuous colour palettes](/mapping/cont_colour.html)
    * Adding a north arrow and scale bar
    * Map legends
    * Adding degrees N labels
    * Multipanel maps
    * Multilayer maps
    * Exporting publication quality maps
* Interactive maps
    * Interacting within R
    * Google maps
    * [Share maps online with OpenStreetMap](/mapping/create_geojson.html)
    * Interactive web maps
* Plotting topography
* rasterVis  
* Fast plotting of large files  
* misc
    * Making rasters that curve with the globe


## title<a name='title_short'></a>
description

### Ingredients
Packages: `raster`

Data: Polygons

### Steps
Steps to take `for` the recipe

#### **(1)** step 1

    some code

#### **(2)** step 2  

    more code

*************





*************

### Maps with ...  

### Fast plotting of large shapefiles and rasters  
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
spplot(raus, maxpixels=200)
spplot(shapefile) ## HOw to draw this fast????
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************
### ggplot maps  

### Fast plotting of large shapefiles and rasters  
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
spplot(raus, maxpixels=200)
spplot(shapefile) ## HOw to draw this fast????
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  
###  Create a KML for Google Earth
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  

### Google Maps  
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  

### Publication quality maps  
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  
### Twitter map?

### Why are there lines across my polygon
recentre it
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  

### Adding degrees to labels
recentre it
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
#Just once
xlabel <- parse(text=paste('Longitude', "^o ", "*W", sep=""))
ylabel <- parse(text=paste('Latitude', "^o ", "*N", sep=""))

image(rland, legend = F, col =landcol, xlab =xlabel, ylab = ylabel)
```
**(2)** Then this:
```{r, eval=FALSE}
To every label
labelsX=parse(text=paste(abs(seq(-100, -50, 10)), "^o ", "*W", sep=""))
labelsY=parse(text=paste(seq(50,100,10), "^o ", "*N", sep=""))
plot(-100:-50, 50:100, type="n", xlab="", ylab="", axes=FALSE)
axis(1, seq(-100, -50, 10), labels=labelsX)
axis(2, seq(50, 100, 10), labels=labelsY)
```
*************  


xlabel <- parse(text=paste('Longitude', "^o ", "*W", sep=""))
ylabel <- parse(text=paste('Latitude', "^o ", "*N", sep=""))

image(rland, legend = F, col =landcol, xlab =xlabel, ylab = ylabel)



*************  

### Multipanel figures
recentre it
Description of the recipe and its goal
#### Ingredients
Packages and data required for this recipe
Packages: ` a package`
Data: A spatial points database `sites`

#### Steps
Steps to take for the recipe
**(1)** Do this:  
```{r, eval=FALSE}
Use layout
if plotting rasters, then need to use the image function...

```
**(2)** Then this:
```{r, eval=FALSE}
```
*************  


xlabel <- parse(text=paste('Longitude', "^o ", "*W", sep=""))
ylabel <- parse(text=paste('Latitude', "^o ", "*N", sep=""))

image(rland, legend = F, col =landcol, xlab =xlabel, ylab = ylabel)
