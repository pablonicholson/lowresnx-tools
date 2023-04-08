# lowresnx-tools
Tools for manipulating LowRes NX files.

## nx-imtobg
Convert image files into characters and bg, it will compress the image by removing duplicate and flipped tiles.

It will create two ROM entries, with the first entry containing characters data, and the second entry containing bg data which is used to restore the original image.

Usage:
```
nx-imtobg imagefile [pal] >> nxfile
```

## nx-imtochr
Convert image files into characters without compression.

It will create one ROM entry containing characters data.

Usage:
```
nx-imtochr imagefile >> nxfile
```

## nx-chrtoim
Convert characters into image files.

It will create a PNG image from characters data.

Usage:
```
nx-chrtoim nxfile [chrom] [pal] [palrom]
```
