## Exercise #3 - Google Cloud Storage + Google Cloud Bigquery + Python.

In this third exercise we will test your ability of working with 
files on the cloud and your skills with sql.

The first thing you will do is work with the `Python` package `google-cloud-storage` 
to interact with `gcp` and upload a file to a `storage bucket`.

The next step will happen in `bigquery` where you must upload and query the data you uploaded
to `storage` working with the `Python` package `google-cloud-bigquery` and doing some `sql`.

You can add any extra packages you need to the requirements file and use them in your script.

#### Setup
1. Change directories at the command line 
   to be inside the `Exercise-3` folder `cd Exercises/Exercise-3`
   
2. Create a python environment and install the dependencies.

3. There is a file called `main.py` in the `Exercise-3` directory, this
   is where you `Python` code to complete the exercise should go.
   
4. Once you have finished the project or want to test run your code,
   run the following command `python main.py` from inside the `Exercises/Exercise-3` directory

#### Problems Statement
Your task is three step task, upload the concatenated file you created in the previous Exercise to the
bucket name we specified to you in the email.

Once this file is uploaded to `storage` create a table under the `bigquery` dataset we told you in the email 
and upload that csv file from `storage` to your brand new table.

After that, create and execute a query that generates the same metrics we told you in the previous exercise
and save those metrics to a new csv file.

Generally, your script should do the following ...
1. Upload the data exported in the previous exercise to storage.
2. Create and upload the data to a table in bigquery
3. Create and execute a query that generates the same metrics of the previous exercise and export
   the result to a csv file.