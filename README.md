The code operates on the following 3 assumptions:
  1. Any of the files will follow the CS_FIT_23_to_Glasgow.cvs format.
  2. The energies are written as 0.001,3.001,6.001, etc. It is assumed that these can be written as 0,3,6,etc.
  3. The cross sections in the file were measured in millibarns (not barns as quoted). 

The code then returns the mean log probability density of the datafile. 
