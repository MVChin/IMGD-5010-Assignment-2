# IMGD-5010-Assignment-2

I wanted to create the basis for a tile pattern so I wanted it to have both linear and rotational symmetry. 
The pattern will have three colours:  a background colour and three contrast colours.  

The steps are as follows:

1.  Create a square canvas using the background colour.
2.  Using contrast colour 1, create a half circle on the top of the canvas.  The half circle will be
    a. centred on the top edge
    b. the diameter will lie on the top edge
    c. the diameter will be half the width of the canvas
3.  Repeat creating a half circle on the other three edges of the canvas.
4.  Add 2 diagonal lines in contrast colour 2.  The diagonal line 1 will run from upper left hand corner to bottom right and the other will run in opposite direction; from the top rignt had corner to the bottom left.
5.  Create the centre or focal point of the pattern.
    1.  Using contrast colour 3, create a circle in the centre of the canvas whose diameter is 3/4 or 75% of the canvas width
    2.  Shift the origin of the canvas to be the centre of the canvas.  This will move the coordite system origin from (0,0) to (half canvas width, half canvas height).  This will allow for the rotation of the next two elements to be mathematically easier to implement when coding.
    3.  Rotate the canvas clockwise 45 degrees.
    4.  in contrast color 1, draw an ellipse whose centre in the center of the canvas, keeping in mind that this in now the new origin of the canvas.  The height of the canvas should be 20% of the height and the width of the ellipse should be 60% of the canvas width.  This should draw an ellipse that follows one of the diagoal line.
    5.  Rotate the canvas counterclockwise 90 degrees and repeat the previous step to draw a mathching ellipse that follows the other diagonal line.
    6.  Rotate the canvas clockwise 45 degrees to return the original orthoganal orientation.
    7.  Reset the origin from the centre of the canvas back to the top left corner
    8.  In contrast colour 2, draw a circle in the centre of the canvas that is 20% of the canvas width
    9.  locate the coordinate that is ( 1/2 canvas width, 1/4 canvas height).  Draw an ellipse centred on this coordinate whose width is 2% of canvas width and height is 10% of the canvas height.
    10.  Repeat the previous step but location of the ellipse centre is ( 1/2 canvas width, 3/4 canvas height.
    11.  locate the coordinate that is ( 1/4 canvas width, 1/2 canvas height).  Draw an ellipse centred on this coordinate whose width is 10% of canvas width and height is 2% of the canvas height.
    12.  Repeat the previous step but location of the ellipse centre is ( 3/4 canvas width, 1/2 canvas height.
       
