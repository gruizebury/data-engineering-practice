## Exercise #2 - WebScraping and File Downloading with Python.

In this second exercise you will practice your Python analytic skills,
we will extend upon the previous exercise and try to gather some insight
based on the files we downloaded.

You will have to provide the following information for the files you
downloaded in the previous exercise:

* Average `Sunrise` and `Sunset` value for your data set per station
* Average `HourlyWindSpeed` per station for every 6 hour period

Finally you'll need to export the concatenated dataset as a CSV for the next exercise.

#### Setup
1. Change directories at the command line
   to be inside the `Exercise-2` folder `cd Exercises/Exercise-2`.

2. Copy the `downloads` folder from the previous exercise here either
through python or manually.

3. There is a file called `main.py` in the `Exercise-2` directory, this
is where you `Python` code to complete the exercise should go.

4. Once you have finished the project or want to test run your code,
   run the following command `python main.py` from inside the `Exercises/Exercise-2` directory

#### Problems Statement
You need to gather some insight from the files downloaded in the previous exercise.

You are looking for some particular metric about these files.
Firstly you want to know what is the average sunrise and sunset time is for the year 2021
for each particular station.
You also want to know the average wind speed for each 6 hour period. For this you can split the
day into 6 hour boxes and calculate the average of each box.

Each file contains meteorological data for a given station gathered each 20 minutes. Each row
contains the information gathered at that point in time. Please beware that not all rows have all columns populated.

Generally, your script should do the following ...
1. Concatenate all the files gathered in the previous exercise into a single pandas dataframe.
2. Analyze the dataframe to extract the necessary metrics.
3. Export the raw data dataframe for using it in the next exercise.
