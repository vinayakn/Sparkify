# Sparkify project:Building Customer Churn Predictive Model Using SPARK


### Table Contents:

|S.NO| Description | README |
|--| ------ | ------ |
|1|Motivation|[GOTO]()|
|2|Installation | [GOTO]()|
|3|The file structure | [GOTO]() |
|4|Summary of the results of the analysis| [GOTO]() |
|5|Acknowledgements | [GOTO]() |

# Motivation

We have data of Sparkify, A fictional music app just like any other music apps in Playstore.so here we will try to predict/identify users who will be/or about to churn and suggest to take some appropriate action to stop him churning out.We will work on a tiny subset data/logs .which having some of details about all the user who are using this music app.

We are doing this analysis on local machine .however we can scale the same analysis on the larger data set using any big data platform.
For ex:-> on Spark cluster using AWS with same code and slight modification in code for example pointing out path of hdfs where log files present to read it, etc


##### **Steps Followed:**
* Load all the required libraries & Create spark session.
* Exploratory Analysis.
* Feature Engineering.
* Building Modeling.
* STEPS TO TAKE to Retain
* Improvement

# Installation
#### **Libraries:**
		*Python,
		*Pyspark,
		*pandas,
		*numpy,
		*seaborn,
		*Matplotlib
			

# The file structure: 

* Sparkify.ipynb Notebook is main file of the project.
* It demonstrates the process of using pyspark to explore the data and build the model.
	
	
# Summary of the results of the analysis:
We Split the feature & target variable data set into train, test and then built pipeline and implemented various machine learning models(2).Since the churned users are a fairly small subset, we used F1 score as the metric to optimize and we found Random forest better model compared to other One.
	
# Acknowledgements:
Must give credit to Udacity for the project. You should and can't use this for your Udacity capstone project. 
Otherwise, feel free to use the code here as you would like!
