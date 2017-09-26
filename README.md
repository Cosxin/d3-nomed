# d3-nomed
Creating [Nomed Font](https://www.behance.net/gallery/2459957/Nomed-Font) and animation with D3 and SVG

![example image]
(https://github.com/Cosxin/d3-nomed/blob/master/a-z.png)
## Nomed Font
Nomed Font is designed based on the simple triangulargeometric shape.

## JSON encoding
Each letter is encoded as an list of (x, y, direction) vector.
Each (x, y, direction) vector represents an isosceles triangle in this letter, where x,y are the coordinates of the apex (in a 5x5 box) and direction is the direction angle.

## Animation
An ease out animation is included in the example.

## Try
Open Index.html and try these in console:
println("ABCD")  
easeOut()
