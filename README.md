# IMGD-5010-Assignment-2

I wanted to create the basis for a tile pattern so I wanted it to have both linear and rotational symmetry. 
The pattern will have four colours:  a background colour and three contrast colours.  

The procedure are as follows:  

## Step 1
Create a square canvas using the background colour. For visibility and convenience, a width of less than 200 is not recommended. 

## Step 2
Using contrast colour 1, locate the midpoint of  the top edge and draw a circle of diameter that is half the canvas width.  

This will result in a visible half circle within the canvas along the top of the canvas.  

Repeat creating circles on the other three edges of the canvas with matching orientations.  The centres of the circles will therefore be:
1. (half canvas width, 0)
2. (0, half canvas heoght)
3. (half canvas width, canvas height)
4. (canvas width, half canvas height)  

## Step 3
Add 2 diagonal lines in contrast colour.  The first diagonal line will run from upper left hand corner to bottom right and the other will run in opposite direction; from the top rignt had corner to the bottom left.  


## Step 4
Create the centre or focal point of the pattern.  
Using contrast colour 3, create a circle in the centre of the canvas whose diameter is 3/4 or 75% of the canvas width.  

Shift the origin of the canvas to be the centre of the canvas.  This will move the coordinate system origin from (0,0) to (half canvas width, half canvas height).  This will allow for the rotation of the next two elements to be mathematically easier to implement.  

Rotate the canvas clockwise 45 degrees.  
In contrast color 1, draw an ellipse whose centre in the centre of the canvas, keeping in mind that this is now the new origin of the canvas.  The height of the ellipse should be 20% of the height the canvas and the width of the ellipse should be 60% of the canvas width.  This should draw an ellipse that is aligned with one of the diagoal lines from step 2.  

Rotate the canvas counterclockwise 90 degrees and repeat the previous step to draw a matching ellipse that follows the other diagonal line.  

Rotate the canvas clockwise 45 degrees to return the original orthoganal orientation.  

Reset the origin from the centre of the canvas back to the top left corner.  

In contrast colour 2, draw a circle in the centre of the canvas that is 20% of the canvas width.  

Locate the coordinate that is ( 1/2 canvas width, 1/4 canvas height).  Draw an ellipse centred on this coordinate whose width is 2% of canvas width and height is 10% of the canvas height.  

Repeat the previous step but location of the ellipse centre is ( 1/2 canvas width, 3/4 canvas height). 

Locate the coordinate that is ( 1/4 canvas width, 1/2 canvas height).  Draw an ellipse centred on this coordinate whose width is 10% of canvas width and height is 2% of the canvas height.  
Repeat the previous step but location of the ellipse centre is ( 3/4 canvas width, 1/2 canvas height).
       
The resluting image should look like:  
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/8ce6bd32-a374-4bfe-b756-c1b8c898ec84" />  
Where background is white, CC1 is teal, CC2 is black and CC3 is orange.  



Tiled:
<img width="360" height="360" alt="9-tile" src="https://github.com/user-attachments/assets/3a094da9-c541-4b3d-a2d6-68938cb5cb25" />



