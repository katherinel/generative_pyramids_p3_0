This is a new version of my generative pyramids project that works with 
Processing 3.0 and ModelbuilderMk2.
[Old project is here: https://github.com/katherinel/generative-pyramids]

Get the new modelbuilder mk2 library here:
https://github.com/mariuswatz/modelbuilderMk2

In the /export folder, grab the latest .zip of the library (currently 0162),
unzip it and put it into your Processing library folder. Processing recommends
making a new folder for storing your P3 projects and libraries, as many older
ones won't work.

------------------

Diffs from old version:
* UGeometry is now UGeo
* had to add UMB.setPApplet(this); in setup()
* model.draw() requires no arguments
* UVec3 is replaced with UVertex
* UGeometry rectangles are now UVertexList rectangles 
