# Constructing Simple Polygon

An application for constructing simple polygon. A simple polygon is the polygon where it’s edges doesn’t intersect. 
![enter image description here](https://lh3.googleusercontent.com/RHI7HTrGs31-CosszuyoWhpM3fPY2gGHmLUtO2Ci4lp2zeTzHVtRu9t00rjGRGIZ8y2ESxaFZkd-)

## Algorithm
Algorithm Simple Polygon (p1, p2, p3, …, pn):
1. Input: p1, p2, p3, …, pn (points in plane)
2. Output: P (a simple polygon whose vertices are p1, p2, p3, …, pn in some order)
3. Begin
4.  For i=2 to n do
Compute the angle alpha_i between the line -p1-pi- and the x-axis (it is sometimes desirable to take an extreme point instead of p1, e.g., a point from the set with the largest x coordinate)
		 
5. Sort the points according to the angles alpha_2, …, alpha_n (Break ties according to distances from p1)
 P is the polygon defined by the list of points in sorted order
6. End

## Preview
![enter image description here](https://lh3.googleusercontent.com/VorHNh3i-te85PIoFQn_WFAYZpwlKL9viz8LAlPCB8M5OIFjZEMuLHTtl7LNRH_Eq3p84hoKd9J0)
