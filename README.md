# d3-nomed
Creating [Nomed Font](https://www.behance.net/gallery/2459957/Nomed-Font) and animation with D3 and SVG

![example image](https://github.com/Cosxin/d3-nomed/blob/master/a-z.png)

## Nomed Font
Nomed Font is designed based on the simple triangulargeometric shape.

## JSON encoding
Each letter is encoded as a list of (x, y, direction) vectors.  
Each (x, y, direction) vector represents an isosceles triangle in this letter,  
where x,y are the coordinates of the apex of this triangle (in a 5x5 box) and direction represent the direction of the angle.

## Animation
An simple ease out animation is included in the example.  

## Try
Open Index.html and try these in your console:  
println("ABCD")  
easeOut()  
