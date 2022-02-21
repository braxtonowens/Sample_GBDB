# Sample_GBDB
Contains Sample data from the BYU Grain Boundary Data Base

The original dataset contains 7304 GBs. There is not systematic way of sampiling the dataset. <br>
The terminal command: $find . -maxdepth 1 -type f |head -100|xargs cp -t "$destdir" <br>
is used to take 100 files from the current location to a destination directory. <br>
The order is dependant on the find command.
