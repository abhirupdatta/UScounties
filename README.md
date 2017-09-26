# UScounties
Adjacency matrix for the 3066 counties and parishes for the 48 contiguous US states.

3066 counties include 64 parishes of Louisiana and 3002 counties for the other 47 states of contiguous US. Hawaii and Alaska are not included. Cities are not included. 

The adjacency matrix countyadj.csv is a 3066x3066 matrix with the (i,j)th element is one if the (i)th and (j)th counties share a geographical border and is zero otherwise. 

The data used to create the matrix is available at https://www2.census.gov/geo/docs/reference/county_adjacency.txt. 
