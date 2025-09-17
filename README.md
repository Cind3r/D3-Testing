# D3-Testing

Repo for practicing D3 as well as assignments for DATA 760

***

## How it Works

Clone the repo (and or download a .zip) then start a python server using `python -m http.server 8000`. You should land on the index.html page which will host links to all of the pages/assignments/testing. For convenience, the pages are also currently held on Github Pages which you can navigate to using the link on the right side of the repo.

## Current Pages

#### Datasaurus Dozen

An intro assignment to exploring how D3 works by doing comparisons of the Datasaurus Dozen dataset. Changing the dataset in the dropdown menu will update the scatterplot as well as the histogram data accordingly. 

The datasets are by default mirrored against each other so that it is easier to see how the means/standard deviations are the same compared even though the desnity of the data varies. This is juxtaposed against the individual scatter plots as well, giving a better sense of how even though the datasets look vastly different, their statistical values remain similar. 

- The button allows the user to overlay the data (opaque, stacked) rather than have the datasets mirrored across the x-axis.
- Clicking on a histogram bar will highlight the corresponding points on the scatter plot as well as the clicked bin
  - behavior persists through changing axis
