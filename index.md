---
layout: index
---
<<<<<<< HEAD
/**
Write a C/C++ function that lights a patch of height-mapped geometry.
Your function should perform standard diffuse lighting on each vertex, as well as self-shadowing.
 up of a regular grid of GRI
The patch is madeD_RESOLUTION_X by GRID_RESOLUTION_Y vertices.
The vertices' 
The input to yx,y coordinates range from (0,0) to (GRID_SIZE_X,GRID_SIZE_Y). The z coordinates of each vertex are given by a height input.
our function is as follows:
- A 2 dimensional array of floats of size GRID_RESOLUTION_X by GRID_RESOLUTION_Y, specifying the height (z value) of each vertex in the patch.
- A float[3] specifying the light direction.
- A float specifying the light intensity.

The output of your function is as follows:
- A 2 dimensional array of floats of size GRID_RESOLUTION_X by GRID_RESOLUTION_Y, where each float represents the color/intensity of the corresponding vertex. 
  Vertices that are in shadow should return 0.
*/

#define GRID_RESOLUTION_X  257
#define GRID_RESOLUTION_Y  257

float height[GRID_RESOLUTION_X][GRID_RESOLUTION_Y];
float out_colors[GRID_RESOLUTION_X][GRID_RESOLUTION_Y];

void light_patch( float light_direction[3], float light_intensity )
{
	// TODO: write me
}
=======
你好，我是孙山，欢迎使用GitHub pages
>>>>>>> 93c584c5482442db5dc8b44c53d0ddcf6df6a4f5
