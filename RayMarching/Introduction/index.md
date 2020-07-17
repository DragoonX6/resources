# An introduction to Ray Marching: Introduction

## Prerequisites
This resource expects the reader to have basic programming knowledge in a C-like language, have an understanding of basic high school level math (pythagorean theorem, etc), and have a decent understanding of both matrices and vectors.

## What is Ray Marching

Ray marching is a form of ray tracing.  
With ray tracing we calculate where the ray intersects the surface of a primitive by solving the line primitive equation.  
With ray marching we calculate the distance between a point on the ray and the surface of the primitive.  
We then move the point by the distance, and calculate the distance again.  
We keep doing this until we're so close to the object that we can count it as a hit.

In essence this is all there is to it when it comes to ray marching, it's just another way of finding the point of intersection.  
However, by doing this in a different way, we also get to take advantage of some extra properties that allow us to do cool stuff like deforming objects, or combining them into new objects.

## Cool stuff you can do


