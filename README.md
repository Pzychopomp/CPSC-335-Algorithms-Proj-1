# CPSC--335-Algorithms

## Members:
 David Nguyen (dnguyen271@csu.fullerton.edu) & Vivian Truong(18vtruong@csu.fullerton.edu)

## Lawnmowers Algorithm Pseudocode:
    
    a[] // a random given array
    n = a.size()
    for i = 1 to n-1 do:  // move from left to right
        if (a[i] == black && a[i+1] == white): // check for swappable elements
            swap;
            
    for j = n-1 down to 1 do:  // move from right to left
        if(a[j] == white && a[j-1] == black): // check for swappable elements
             swap;

## Alternate Algorithm Pseudocode:

    a[] // a random given array
    n = a.size()
    for i = 1 to n-1 do:  // move from left to right
        if(a[i] == white && a[i-1] != white): // check for swappable elements
            do nothing;
        else if (a[i] == black && a[i+1] != black):
            swap;
        i += 1 // adds 1 in addition to regular increment making it skip a pair
        
    for i = 2 to n-2 do: // check the secondleft to secondright disc
        if(a[i] == white && a[i-1] != white): // check for swappable elements
            do nothing;
        else if (a[i] == black && a[i+1] != black):
            swap;
        i += 1 //adds 1 in addition to regular increment making it skip a pair
