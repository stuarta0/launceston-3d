# City of Launceston 3D Model

![Skyline in Godot](https://raw.githubusercontent.com/stuarta0/launceston-3d/main/docs/skyline.jpg)

A LIDAR scan of the City of Launceston, Tasmania, AU.


## Formats

Available in multiple levels of detail in glTF format.

For FBX and Sketchup models, use the app:<br>
http://s3-ap-southeast-2.amazonaws.com/launceston/atlas/index.html

## Stats

Represented per tile. Total size is for each LOD dataset. Each LOD contains 142 tiles.

| LOD | Avg. Tris |  Texture Size | Total Size |
| --- | --- | --- | --- |
| L15 | 4,786 | 128x128 | 56 MB |
| L16 | 5,847 | 256x256 | 76 MB |
| L17 | 9,192 | 512x512 | 148 MB |
| L18 | 18,707 | 1024x1024 | 394 MB |
| L19 | 42,625 | 2048x2048 | 1.2 GB |
| L20 | 94,980 | 4096x4096 | 3.9 GB |

Total repo size: 5.8 GB

## License

Licenced Under Creative Commons Licence - Attribution 3.0 Australia (CC BY 3.0). See LICENSE for more information.

## Dataset Info

Each tile is a 200m x 200m square. Origins are at each tile center, with vertical location representing sea level.

```
(c) Launceston City Council 2013
Spatial Sciences Department
Contact 03 63233341

Acquisition Dates:  14th and 18th August July 2015
Capture Pixel Size: 2-3 cm and 5cm GSD
Horizontal Datum:   Geocentric Datum of Australia 1994 (GDA94)
Vertical Datum:     Australian Height Datum (AHD)
Map Projection:     MGA Zone 55 (Origin offsets X: 511491 Y: 5412892)
Spatial Accuracy:   0.05m absolute accuracy (XYZ)

Please note that this model has the above origin offsets applied 
for viewing purposes. Any measurements and data overlays need to 
take this into consideration.
```