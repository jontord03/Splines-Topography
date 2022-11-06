# 3D Bicubic Interpolation of a Lake Bed
### Visualizing a lake bed based on a collection of several chosen points in 3D space

My method was to place 4 points with the greatest distance from the coast and each other, because a point on a more gradual slope of the lake is more representative of the overall surface than a point on a steeper part of the lake, and points chosen in the middle of the lake represent a larger percentage of the lake. I wrote a python script to calculate a bicubic spline interpolation: the result was a 3D surface. 


