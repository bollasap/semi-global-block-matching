# Semi-Global Block Matching
A Matlab implementation of Semi-Global Block Matching (SGBM) for stereo matching.
It uses the 8-direction version of the algorithm with a small improvement for better results.
The improvement is that in the calculation of the total cost, the matching cost does not add up. Normally it had to add up eight times (once for each direction).

## Input Image
The Tsukuba stereo image that used as input.

<p align="center">
  <img src="left.png"> 
</p>

## Output Image
The disparity map that created at the output.

<p align="center">
  <img src="disparity.png"> 
</p>
