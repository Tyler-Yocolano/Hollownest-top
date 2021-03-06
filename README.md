# Hollownest-top

## Introduction

This is a rainmeter skin bundle based on the game [Hollow Knight](http://hollowknight.com/).  You need [Rainmeter v4.0](https://www.rainmeter.net/) or greater to use this skin.

## Installing the Skins

### RMSkin Package

Simply download the latest .rmskin package [here](https://github.com/Tyler-Yocolano/Hollownest-top/releases) and the installer will do everything for you!  Well, it will only load the map up, you'll have to go into the skin manager and load "CharmLauncher.ini" as well.

### Manual Installation

You can download the .zip file and place the root folder in your "Documents\Rainmeter\Skins\" folder.  Then open the Rainmeter Skin Manager and load both skins.

## The Skins

### __*Important:*__

Open the files "Hollownest-top\MapAndBackground\Map\Map.ini" and "Hollownest-top\CharmLauncher\Charms\Charms.ini".  In the [Variables] Section, change ````ResolutionX=1920```` and ````ResolutionY=1080```` to your actual resolution.  The assets should now scale to your resolution.

*__warning__: it might look ugly though, its based on 16:9 resolution.*

### Map and Background

Click the Map & Quill icon to see a map of Hollownest.  Select any area and your background will be changed to that area!

#### How to Modify Backgrounds

The backgrounds for the each section of the map can be found in "@Resources\MapAndBackground\". All you need to do is replace the location you want a different image at with the same name.  So any image will work, just make sure the image, for example, for Fog Canyon is called "Canyon.png"

### Charm Launcher

Click the Comapss icon and the Charms menu from Hollow Knight will appear! Add all your favorites in place of charms and include your own descriptions if you want.

#### How to Add Your Own Apps

To launch your own apps from the Charm Launcher, you'll need to edit the "\CharmLauncher\RowX.inc" files ('X' is the row you wish to modify).  Each just needs an image file at the charms "ImageName" property and a path to the application where it says "\*Set app path here\*".  Any custom icons can just be placed into the "\CharmLauncher\Charms\" folder and they will automagically be resized.

To edit a specific charm, the charm name can be used to figure out which one you want to edit.  For example, [Charm25] would be the 3rd row and charm 6.  I know, I indexed at 0 and I did X and Y Values backwards! But it made sense when I was doing it so I'm gonna leave it.

## Known Issues

- Currently made for 1920x1080 monitors.  Any help making it more dynamic in that sense would be appreciated!