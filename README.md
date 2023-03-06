# CPSC--335-Algorithms

Members:
David Nguyen (dnguyen271@csu.fullerton.edu)
Vivian Truong(18vtruong@csu.fullerton.edu)

Lawnmowers Algorithm Pseudocode:
a[] // a random given array
n = a.size()
for i = 1 to n-1 do:  // move from left to right
// check for swappable elements
     if(a[i] == white && a[i+1] != white):
          swap;
     else if (a[i] == black && a[i+1] != black):
          swap;
for j = n-1 down to 1 do:  // move from right to left
// check for swappable elements
     if(a[i] == white && a[i+1] != white):
          swap;
     else if (a[i] == black && a[i+1] != black):
          swap;
