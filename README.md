Group5-Homework2
================

Preliminary Setup Steps
-----------------------
To run this code you'll need to install the following packages
inside your virtual machine:

    sudo apt-get install libgeos-3.3.3 python-mpltoolkits.basemap python-mpltoolkits.basemap-data python-mpltoolkits.basemap-doc
    sudo apt-get install python-pandas

Running Code
-------------

* Clone this repository (Group5-Homework2) to your desktop via UI or command ```git clone```

* Open Virtual Machine and ```cd``` into the directory that you want to save the earthquake data to

Then run iPython Notebook from your machine with this command:

    ipython notebook --no-browser --ip=0.0.0.0 --script --pylab=inline

* Open iPython Notebook in your browser and import the file 'recent_earthquakes.py'. This file will be located in the clone of this repository on your desktop. 

* Open 'recent earthquakes' in iPython Notebook and run each code cell to read in live earthquake data

* Run code cell 4 to cache data

* The cached data will be titled "EarthQuakeData" followed by the date (year-month-day) and .txt

* The cached data will be saved to the directory in which you ran iPython Notebook
