# Image-Restoration-Using-Blind-algorithms-and-gradient-descent-

This was a project carried out with an aim to restore blurred and noisy images.
The basic idea is to first determine a PSF(Point Spread Function) for the given input image using Blind Richard-Lucy algorithm. 
The PSF estmiation takes place iteratively according to a bound given by the programmer.  
After this a Gradient Descent method is used to recover the image itself using the PSF determined previously.
This image is further prcoessed and enhanced using modified R-L algorithm before getting qualified as an output.

Now the programmes have been named as tryi.m, which means ith try or ith attempt.

The program was tested on a set of microscopic and telescopic images, the results of which along with the images are provided.
