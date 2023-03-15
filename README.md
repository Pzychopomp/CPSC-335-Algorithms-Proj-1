# CPSC--335-Algorithms

## Members:
 David Nguyen (dnguyen271@csu.fullerton.edu) & Vivian Truong(18vtruong@csu.fullerton.edu)

## Lawnmowers Algorithm Pseudocode:
    
    a[] // a random given array
    n = a.size()
    for j = 0 to n/2 do: // make sure it runs n/2 times
       for i = 1 to n-1 do: // move from left to right
           if (a[i] == black && a[i+1] == white): // check for swappable elements
               swap;
            
       for j = n-1 down to 1 do:  // move from right to left
           if(a[j] == white && a[j-1] == black): // check for swappable elements
                swap;

## Alternate Algorithm Pseudocode:

    a[] // a random given array
    n = a.size()
    bool sorted
    while(!sorted) do:
       for i = 1 to n-1 do:  // move from left to right
           else if (a[i] == black && a[i+1] != black): // check for swappable elements
               swap;
        
       for i = 2 to n-2 do: // check the secondleft to secondright disc
           else if (a[i] == black && a[i+1] != black): // check for swappable elements
               swap;
