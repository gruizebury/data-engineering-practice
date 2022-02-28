## Exercise #3 - Google Cloud Storage + Google Cloud Bigquery + Python.

In this third exercise you will practice your Python skills again,
we will extend upon the idea of working with files and start by 
uploading data to a `google storage` cloud bucket on `gcp`.

Working with the `Python` package `google-cloud-storage` to interact with `gcp` is very
common, and this will ensure you get an introduction to that topic.

The next step will happen in `bigquery` where you must upload and query the data you uploaded
to `storage` working with the `Python` package `google-cloud-bigquery`.

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
Your task is three-fold, upload the concatenated file you created in the previous Exercise to the
bucket name we specified to you in the email.

Once this file is uploaded to `storage` create a table under the dataset we told you in the email to
`bigquery` and upload that csv file from `storage` to your brand new table.

After that, create and execute a query that generates the same metrics we told you in the previous exercise
and save those metrics to a new csv file.

Generally, your script should do the following ...
1. Upload the data exported in the previous exercise to storage.
2. Create and upload the data to a table in bigquery
3. Create and execute a query that generates the same metrics of the previous exercise and export
   the result to a csv file.