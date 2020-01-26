# Morphological Analysis

In this project, I will perform a morphological analysis of a _C. elegans_ worm. 
Given a brightfield image of one worm, I computed the center of mass
of the animal, its axis of symmetry (computing the eigenvectors of the inertia
tensor of the worm), and the curvature of its perimeter.

## Execution

This program can be executed in Mathematica 11.1.1.0 and the most recent previous versions.
However, note that for version 11.1.1.0 there is a bug (most likely, some kind of version
 incompatibility) when plotting the osculating circle, in the curvature computation section. This does not
affect results and it's just a visualization issue. I have included the `worm\_curvature\_Portfolio.avi` 
file for a correct visualization of the osculating circle.

In case you don't have a license for Mathematica, you can still see the code installing [Wolfram 
CDF Player](https://www.wolfram.com/cdf-player/) for free.

For further information, I developed this program in Mac OS X 10.11.6. 

![worminputImage](https://github.com/mdies/morphological-analysis/blob/master/worm_curvature_Portfolio_inputImage.png)
![wormsymmetryaxis](https://github.com/mdies/morphological-analysis/blob/master/worm_symmetry_axis.png)
![wormosccircle](https://github.com/mdies/morphological-analysis/blob/master/screenShotOsculatingCircle.png)
