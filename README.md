# gimp-blender-import
Import GIMP Image as Layers (.xcf, .xfcgz, .xfcbz2 etc.)

This addon provides (more or less) the functionallity of [Import GIMP Image to Scene (.xcf, .xjt)](https://wiki.blender.jp/Extensions:2.6/Py/Scripts/Import-Export/GIMPImageToScene) by Daniel Salazar (ZanQdo) but for Blender versions 2.80 and upwards since the old one isn't supported anymore. It is based on [Import Images as Planes](https://gist.github.com/tschundler/6b68141004cdc7678f0247a025410f47) by Florian Meyer (tstscr), mont29, matali and Ted Schundler (SpkyElctrc).

The old (pre 2.80) version depended on xcftools which isn't maintained anymore. This version depends only on GIMP itself and uses script-fu to extract the layers from the image and creates planes in Blender. It is located under File > Import > Import GIMP image layers as planes.

## Missing functionalities:

* Offsets of the original layers are not preserved
* Layer opacity is not preserved

 
