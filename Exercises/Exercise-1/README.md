## Exercise #1 - Downloading Files with Python.

In this first exercise you will practice your Python skills,
as well as learn about a very common task ... downloading data files
from a `HTTP` source.


#### Setup
1. Change directories at the command line
   to be inside the `Exercise-1` folder `cd Exercises/Exercise-1`

2. Create a python environment and install the dependencies.

3. There is a file called `main.py` in the `Exercise-1` directory, this
   is where you `Python` code to complete the exercise should go.

4. Once you have finished the project or want to test run your code,
   run the following command `python main.py` from inside the `Exercises/Exercise-1` directory

#### Problems Statement
You need to download 10 random files that are sitting at the following specified
`HTTP` url. You will use the `Python` package `requests` to do this work.
We also recommend using the BeautifulSoup module to find the downloadable link.

You will need to pull the filename from the download uri.

They should be downloaded into a folder called `downloads` which
does not exist currently inside the `Exercise-1` folder. You should
use `Python` to create the directory, do not do it manually.

Generally, your script should do the following ...
1. Create the directory `downloads` if it doesn't exist.
2. Check the links from the source_uri.
3. Pick 10 files at random and download them into the `downloads` folder.

#### Download URI is listed in the `main.py` file.
