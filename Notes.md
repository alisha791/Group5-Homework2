2013-10-19

Office hours with Aaron from 11 - 1 pm

####Data Curation:

* Could not get Aaron's code to run, realized that we have to install pandas first with sudo get-apt install python-pandas
* Tried to read new data using JSON but could not get the new data into a usable format
* Discussed JSON with Aaron, suggested that we move on to caching the data from his csv file
* However, after looking at the issue tracker and reading more about JSON, group was able to format the new data into a data frame
* Discussed data caching with Aaron to get a better understanding of the goal of the assignment
* Worked with horizontal group members on data caching
* Used to_csv to save the data and wrote code so that the cached data would be named with the date
* Struggled with figuring out how to use git push to save the cached data to our repository
* Read about git commands online and figured out how to use ```git clone```, ```git add```, ```git commit```, and ```git push```

####Visualization:

* 

####Roadblocks:

#####Data Curation:

+ Unfamiliar with JSON representation, and navigating and accessing keys, values, and items in the lists and dictionaries
+ Lack of working knowledge in Python, and understanding how syntax differs from R (i.e. indentation, for loops), as well as how importing libraries and using functions worked
+ How to ```git push``` .ipynb and .py files to the working repository to share code and collaborate with group

Problem solving was a key part to understanding how to work through the data curation stages. JSON was a completely new format that we were unfamiliar with, coupled with learning Python and working in the iPython Notebook (which our group had familiarized ourselves with after the first assignment). We used numerous **strategies** to tackle this assignment:

Read up on documentation:

+ <a href="http://pandas.pydata.org/pandas-docs/stable/10min.html">Pandas documentation</a> helped to understand how to select data, view the data frame, append data, etc.
+ <a href="http://earthquake.usgs.gov/earthquakes/catalogs/eqs7day-M1.txt">Old data feed</a> differed from the <a href="http://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/1.0_week.geojson">new data feed</a>, so searching for relationships between variables of the data helped allow more familiarity with how lists and dictionaries are organized.
+ Another strategy was working through extracting the data for the variables of one single earthquake, then applying the for loop to all earthquakes and then generating the new data frame from <a href="http://docs.scipy.org/doc/numpy/reference/arrays.html">arrays</a>, reading up on ```numpy```

Work with others and ask friends:

+ Asked for explanation from EECS friends more familiar with GitHub on concept of ```git push``` since didn't understand how to push .ipynb and .py files from Virtual Machine; learned that it involves a sequence of commands
