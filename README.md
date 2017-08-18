# Hollownest-top

## Introduction
This is a rainmeter skin bundle based on the game [Hollow Knight](http://hollowknight.com/).  You need [Rainmeter](https://www.rainmeter.net/) to use this skin. Right now, there are 2 skins. There is one for changing backgrounds based on the hollow knight map. And the second is an app launcher based on the charms menu.

## Modifying the Skins
### Map and Background
The backgrounds for the each section of the map can be found in "@Resources\MapAndBackground\". All you need to do is replace the location you want a different image at with the same name.  So any image will work, just make sure the image, for example, for Fog Canyon is called "Canyon.png"

### Charm Launcher
To launch your own apps from the Charm Launcher, you'll need to edit the "CharmLauncher\Charms\Charms.ini" file.  Each just needs an image file at the charms "ImageName" property and a path to the application where it says "\*Set app path here*".  Any custom icons can just be placed into the "@Resources\CharmLauncher\Charms\" folder and they will automagically be resized.

To edit a specific charm, the charm name can be used to figure out which one you want to edit.  For example, [Charm25] would be the 3rd row and charm 6.  I know, I indexed at 0 and I did X and Y Values backwards! But it made sense when I was doing it so I'm gonna leave it.