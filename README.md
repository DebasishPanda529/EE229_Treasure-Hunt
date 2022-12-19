# EE229_Treasure-Hunt

This particular project required the collective effort of all the participants in order to solve the problem. First of all, each person had to download a file,
which contains 1000 complex data points, the pattern being unique to his/her roll number(The files are available in the NewData folder). Now, the 1000-point 
segment was part of a long sequence of values, about 35000-40000 points long, i.e. each student had been given different segments of this particular sequence.
Each segment has some overlap with adjacent segments, and this provides the clue to figure out our neighbors. 

The python code written by me takes as input two .dat files, and calculates the number of points common to the real(or complex) part of the data of both the files.
The code also plots the real(or complex) part of the data and gives as output the points common to the files.
