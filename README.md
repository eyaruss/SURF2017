# Photometry 
The first 5 cells of this file are the photometry code.
The remaining 3 are tests cases.

The code uses 2 files (observed and SNhunt).
Observed is used to get the z coordinate (which in this case I looked up from the table and manually imported).
SNhunt is the image I wish to run the photometry on (and also used to get accurate coordiantes).

To run the photometry code, run the fist 5 cells in sequence.
This creates coordinates and a radius, which are used to find an aperature.
The aperature is then used to run the photometry. 

The problem I am facing is that my aperature sum is returning as NaN, and I can't figure out why. 

The test cases test a made up data set, a data set with negative numbers, and an imported data set of a real image. 
None of them return NaN. There are also no NaN in my original data set. 
