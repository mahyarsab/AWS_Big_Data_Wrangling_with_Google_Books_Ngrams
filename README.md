# AWS_Big_Data_Wrangling_with_Google_Books_Ngrams

- [First Jupyter Notebook on EMR ( AWS S3 & Hadoop & PySpark & Spark SQL ) ](https://github.com/mahyarsab/AWS_Big_Data_Wrangling_with_Google_Books_Ngrams/blob/main/1.%20Mahyar_Sabouniaghdam_Spark_on_EMR_Notebook_for_Step4.ipynb)
- [Second Jupyter Notebook on Local Computer ( Hadoop & Spark & boto3 ) ](https://github.com/mahyarsab/AWS_Big_Data_Wrangling_with_Google_Books_Ngrams/blob/main/2.%20Mahyar_Sabouniaghdam_Step6_to_8_Notebook.ipynb)
- [Step by Step Full Report](https://github.com/mahyarsab/AWS_Big_Data_Wrangling_with_Google_Books_Ngrams/blob/main/Mahyar_Sabouniaghdam_Big_Data_AWS_Project.pdf)
- [Filtered CSV Data](https://github.com/mahyarsab/AWS_Big_Data_Wrangling_with_Google_Books_Ngrams/blob/main/filtered_data.csv)

![image](https://user-images.githubusercontent.com/122119114/225180087-b5ba7db0-61b3-43b3-b4c4-9d2d05205ed6.png)

The [Google Ngrams](https://books.google.com/ngrams) dataset was created by Google's research team by analyzing all of the content in Google Books - these digitized texts represent approximately 4% of all books ever printed, and span a time period from the 1800s into the 2000s.



The aim of this project is to apply the skills and knowledge of the Big Data Fundamentals unit to load, filter, and visualize a large real-world dataset in a cloud-based distributed computing environment. In this project, we will be using Hadoop, Spark, Hive, and the S3 filesystem to analyze the Google Ngrams dataset. The dataset is hosted in a public S3 bucket and is accessible through [here](http://brainstation-dsft.s3.ca-central-1.amazonaws.com/eng_1M_1gram.csv).

---

This project includes:

1. A Jupyter notebook containing the PySpark code used to analyze the dataset on EMR for step 4.

2. A Jupyter notebook that reads the data from the S3 bucket into a Pandas DataFrame for step 6 to 8.

3. A report documenting the project steps, including code snippets, screenshots, and analysis of the findings.


---

Methodology:

In this project, I will follow a Big Data analysis workflow. I will first filter and reduce the data down to a manageable size, and then analyze it locally on my machine after extracting data from the Cloud and processing it using Big Data tools. The scope of data processing and analysis is outlined in the diagram below:

![image](https://user-images.githubusercontent.com/122119114/225180739-31e0c95a-564f-4157-8c61-5f52904eae7e.png)

---

Project Description:

In this project, I will use Amazon EMR to spin up a cluster with Hadoop, Spark, Hive, Jupyterhub, and Livy installed. I will then copy a large dataset from an S3 bucket into the Hadoop File System (HDFS) and use PySpark to analyze the data.

The dataset is the Google Ngrams dataset, which represents approximately 4% of all books ever printed and spans a time period from the 1800s into the 2000s. I will use PySpark to filter the dataset to only include rows where the token is "data", write the filtered data back to HDFS, and then move the resulting file into an S3 bucket.

Finally, I will then use Python and the Pandas library to read the data from the S3 bucket into a Pandas DataFrame and use Matplotlib to plot the frequency of the token "data" over the years.


To complete this project, it will be needed to have access to an AWS account and be familiar with PySpark, Pandas, and Matplotlib. Being comfortable using the command line and connecting to a remote server via SSH is also required.

---


Closure:

This project aims to demonstrate the application of Big Data tools to analyze a large real-world dataset in a cloud-based distributed computing environment. The Google Ngrams dataset is a valuable resource for linguistic research and can provide insights into the use of language over time. Through this project, I hope to gain a better understanding of the dataset and the capabilities of Big Data tools such as Hadoop, Spark, and Hive.


