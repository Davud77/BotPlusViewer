# Equirectangular local images viewer for Qgis

This plugin allows the visualization of equirectangular local images, it can be used for any 360 image, given that the library [Marzipano](https://github.com/google/marzipano) is used.
 
## Prerequisites
 
The library Pillow is required,  install the **Pillow** python package.
Always from command prompt:

`python3 -m pip install pillow`

Or using:

`python3 -m pip install -r requirements.txt`

 
## How it works?
 
It's simple:
- You start a local server in Python in  `http://127.0.0.1:1520/viewer.html `
- A copy of the image associated to the selected registry is created in the folder where our viewer and server are.
- We open the browser and return the current yaw to our canvas anytime the image is moved.
