# D3-Testing

Repo for practicing D3 as well as assignments for DATA 760

***

## How it Works

Clone the repo (and or download a .zip) then start a python server using `python -m http.server 8000`. You should land on the index.html page which will host links to all of the pages/assignments/testing. For convenience, the pages are also currently held on Github Pages which you can navigate to using the link on the right side of the repo.

## Current Pages

#### Datasaurus Dozen

An intro assignment to exploring how D3 works by doing comparisons of the Datasaurus Dozen dataset. Changing the dataset in the dropdown menu will update the scatterplot, histogram, and shape plots accordingly. 

The datasets are by default mirrored against each other so that it is easier to see how the means/standard deviations are the same compared even though the density/shape of the data varies. This is juxtaposed against the individual scatter plots as well, giving a better sense of how their statistical values remain similar even though the datasets look vastly different. 

- The button allows the user to overlay the data (opaque, stacked) rather than have the datasets mirrored across the x-axis.
- Clicking on a histogram bar will highlight the corresponding points on the scatter plot as well as the clicked bin
  - behavior persists through changing axis, will reset when data is changed
- shape plots color in contours on top of each other
  - slider adjusts opacity of which dataset you want to see more
- density plot updates showing where the points are concentrated data-wise on both x/y axis rather than the histogram which only displays by the y-axis
  - animated the show the change in data from one dataset to the other
  - slider adjusts the number of density rings, rings are bounded by the axes
    
