# Sample_GBDB
Contains Sample data from the BYU Grain Boundary Data Base (find . -maxdepth 1 -type f |head -1000|xargs cp -t "$destdir")

The original dataset contains 7304 GBs. There is not systematic way of sampiling the dataset.
The terminal command $find . -maxdepth 1 -type f |head -200|xargs cp -t "$destdir" 
is used to take 200 files from the current location to a destination directory.  
