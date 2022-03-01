## Data Engineering Practice Problems

One of the main obstacles of Data Engineering is the large
and varied technical skills that can be required on a 
day-to-day basis.

- Python data processing.
- csv, flat-file, parquet, json, etc.
- SQL database table design.
- Python + Cloud, data ingestion and retrieval.
- Data cleansing / dirty data.

### How to work on the problems.
You will need two things to work effectively on most all
of these problems. 
- `python`
- `python environments`

For each exercise you will need to `cd` into that folder and
create a python environment installing the needed packages,
in each exercise's folder you'll find instructions to follow.

Bare in mind that even if we propose some python packages to use you
can install and use any python package you need to solve each problem.

### Exercises

#### Exercise 1 - Web scrapping + Downloading files.
The [first exercise](https://github.com/gruizebury/data-engineering-practice/tree/main/Exercises/Exercise-1) tests your ability to download a number of files
from an `HTTP` source and unzip them, storing them locally with `Python`.
`cd Exercises/Exercise-1` and see `README` in that location for instructions.

#### Exercise 2 - Pandas file processing.
The [second exercise](https://github.com/gruizebury/data-engineering-practice/tree/main/Exercises/Exercise-2) 
tests your ability with Pandas to perform some actions with data and calculate some metrics.
`cd Exercises/Exercise-2` and see `README` in that location for instructions.

#### Exercise 3 - Python + Google Cloud Storage + Google Bigquery.
The [third exercise](https://github.com/gruizebury/data-engineering-practice/tree/main/Exercises/Exercise-3) tests a few skills.
This time we  will be using two popular `gcp` package called `google-cloud-storage` and `google-cloud-bigquery` to try to perform
multi-step actions to upload the previous data files to `storage` and then to `bigquery` and recalculate the same metrics of the
Exercise 2 using `sql`.
`cd Exercises/Exercise-3` and see `README` in that location for instructions.