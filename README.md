# PHP favicon

This is the Inkscape project file for the php.net favicon.
The logo is the one created by [Levi Morrison](https://github.com/morrisonlevi), in white, over a blue rounded square:

![Preview](https://user-images.githubusercontent.com/7695608/173258715-1dc83707-9e1d-44f7-b205-187d95dd2b4c.png)  
![Dark preview](https://user-images.githubusercontent.com/7695608/173258719-beb6c69d-88d9-4802-84f6-b7fc6ce6384d.png)


## Export steps

### PNG images
- Export a 196x196px PNG image.
- Use an image editor to scale it down to 16x16, 32x32 variantes. Ensure the 16x16 result is crispy. I've used GIMP.
- Use TinyPNG or similar to optimize the PNG images.

### ICO icon
Use [RedKetchup Icon Editor](https://redketchup.io/icon-editor) or a similar editor to create a single .ICO icon with both 16x16 and 32x32 dimensions using the respective PNGs exported before.

### SVG Icon
- Export a optimized SVG from Inkscape.
- Optimize it using [SVGOMG](https://jakearchibald.github.io/svgomg/) or a similar tool.

## Why not use an online favicon generator
I tried [Real Favicon Generator](https://realfavicongenerator.net/) but the 16x16 version was not as crispy as scaling down using GIMP.
It has options for the scaling algorithm though.
