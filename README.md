# Bitmask
###### Generate JSON representations of bitmasks from image selections for machine learning applications.
[DEMO](https://monixlabs.com/bitmask)

![Bitmask in use](https://i.imgur.com/tfCFd8n.gif)

## Data Output
Bitmask outputs a JSON string representing the area selection of an image. All the arrays are 0-based *(e.g an image which is 300px in height will be represented as a multidimensional array of length 299, assuming one of the [y,x]  output formats are selected in the options menu.*)

###### Formats
| Format | Description |
| --- | --- |
| Pixel Coordinate Array [y,x] | A representation of the selected area in which x coordinates are contained within an array who's index corresponds to a y coordinate. |
| Pixel Coordinate Array [x,y] | A representation of the selected area in which y coordinates are contained within an array who's index corresponds to an x coordinate. |
| Bitmask Array [y,x] | A representation of the selected area in which x coordinates are contained within an array who's index corresponds to a y coordinate. Selected pixels are represented by a 1, while the rest are represented by a 0. |
| Bitmask Array [x,y] | A representation of the selected area in which y coordinates are contained within an array who's index corresponds to a x coordinate. Selected pixels are represented by a 1, while the rest are represented by a 0. |