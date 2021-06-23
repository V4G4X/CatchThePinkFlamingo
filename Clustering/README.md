# Clustering

Our goal is to segment our user base so that we can get a high-level/abstract understanding of the different types of users we have.  
This provides us managable bites/goals for us to market to our users. 

## Steps:
 1. [Attribute Selection](1%20Attribute%20Selection.pdf):  
   Select which attributes to use for segmenting our user base.  

 2. [Dataset Creating](2%20DataSet%20Creation.pdf):  
   Join and Wrangle [flamingo-data](../DataSets/) tables to get the attributes we decided on in the previous step.

 3. [Clustering](3%20Clustering.pdf):  
   Segmenting our created Dataset into 3 Clusters.  
   **Note:** The Values were all Normalised/Scaled before clustering for better understanding of results. 

 4. [Conclusion](4%20Recommended%20Actions.pdf):  
   Provides Recommendations to increase Revenue.

## Working
This [Jupyter Notebook](Clustering.ipynb) contains all the working done above, step by step.    
From reading files, to wrangling and joining, to normalising dataset and finally Clustering.  

**Note:** This Notebook requries a Scala Kernel to run AND also needs the Apache Spark Libraries to be available to said Kernel.  
[Apache Toree](https://toree.apache.org/) recommended.
