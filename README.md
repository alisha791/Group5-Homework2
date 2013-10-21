Group5-Homework2
================

Preliminary Setup Steps
-----------------------
To run this code you'll need to install the following packages
inside your Virtual Machine:

    sudo apt-get install libgeos-3.3.3 python-mpltoolkits.basemap python-mpltoolkits.basemap-data python-mpltoolkits.basemap-doc
    sudo apt-get install python-pandas
    sudo apt-get update pandas

* Clone this repository (Group5-Homework2) to your desktop via UI (Clone in Desktop) or command ```git clone```

Running Code
-------------

* Open Virtual Machine and ```cd``` into the directory that you want to save the earthquake data to

Then run iPython Notebook from your machine with this command:

    ipython notebook --no-browser --ip=0.0.0.0 --script --pylab=inline

* Open iPython Notebook in your browser and import the file 'recent_earthquakes.py'. This file will be located in the clone of this repository on your desktop. 

* Open 'recent earthquakes' in iPython Notebook and run each code cell to read in <a href="http://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/1.0_week.geojson">live earthquake data</a>, M1.0+ Earthquakes in Past 7 Days
  + The first cell reads in the earthquake data from JSON format, loading the data into a data frame
  + The second cell examines a single earthquake incident and shows how the lists and dictionaries are represented, providing information on how to access keys, values and items
  + The third cell creates a new data frame for all the earthquake incidents after cleaning the data; it accesses the variables that we want to observe and analyze, and appends each earthquake's data points to that variable, forming arrays; the arrays form a data frame with labeled columns

Caching Data
------------

* Run code cell 4 to cache data

* The cached data will be titled "EarthQuakeData" followed by the date (year-month-day) and .txt

* The cached data will be saved to the directory in which you ran iPython Notebook
