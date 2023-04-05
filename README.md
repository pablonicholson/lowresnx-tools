# lowresnx-tools
Tools for manipulating LowRes NX files.

## nx-imtobg
Script to convert image files into characters and bg, it will compress the image by removing duplicate and flipped tiles.

Usage:
```
nx-imtobg imagefile [palette] >> nxfile
```
It will create two ROM entries, with the first entry containing characters data, and the second entry containing bg data which is used to restore the original image.

## nx-imtochr
Script to convert image files into characters without compression.

Usage:
```
nx-imtochr imagefile >> nxfile
```
It will create one ROM entry containing characters data.
