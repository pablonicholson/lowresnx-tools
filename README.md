# lowresnx-tools
Tools for manipulating LowRes NX files.

## nx-imtobg
Background import tool, convert image files into characters and bg. It will compress the character data by removing duplicate and flipped tiles.

Usage:
```
nx-imtobg imagefile nxfile [palidx [palrom [chrom [bgrom]]]]
```

## nx-imtochr
Character import tool, convert image files into characters.

Usage:
```
nx-imtochr imagefile nxfile [palidx [palrom [chrom [bgrom]]]]
```

## nx-bgtoim
Background export tool, convert bg data into image files.

Usage:
```
nx-bgtoim nxfile imagefile [palidx [palrom [chrom [bgrom]]]]
```

## nx-chrtoim
Character export tool, convert character data into image files.

Usage:
```
nx-chrtoim nxfile imagefile [palidx [palrom [chrom [bgrom]]]]
```
