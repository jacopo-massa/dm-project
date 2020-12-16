# Data Mining Project

This project consists in data analysis based on the use of __data mining tools__. It has to be performed by using Python. 
The guidelines require to address specific tasks and to report results in a unique paper. Well commented Python notebooks contains the code of each task.

Before talking in details about the tasks, some tips (for the correct execution and visualization of the supplied notebooks) are provided.

## Setup 💻
Create a virtual environment , and install the dependecies:

```
python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt
```
&nbsp;

## Tasks  ✔️

### Task 1 - Data Understanding and Preparation 
&nbsp;  
#### Task 1.1: Data Understanding

Explore the dataset with the analytical tools studied and write a concise “data understanding” report describing data semantics, assessing data quality, the distribution of the variables and the pairwise correlations.

#### Task 1.2: Data Preparation

​Improve the quality of data and prepare it by extracting ​ _new features_ interesting for describing the customer profile and his purchasing behavior.

&nbsp;  
### Task 2: Clustering analysis

Based on the customer’s profile explore the dataset using various clustering techniques. Different algorithms and approaches must be compared:
 - K-means
 - Density-based clustering (DBSCAN)
 - Hierarchical clustering

&nbsp;  
### Task 3: Predictive Analysis
Consider the problem of predicting for each customer a label that defines if (s)he is a **high-spending** customer, ​ **medium-spending** customer or ​ **low-spending** customer. After having defined some indicators for assigning these labels, perform the predictive analysis comparing the performance of different models:

 - Decision Tree
 - Random Forest
 - SVM
 - KNN
 - Naive Bayesian


### Task 4: Sequential Pattern mining

Model the customer as a sequence of baskets and apply the sequential pattern mining algorithm.


&nbsp;  

## Contributors ✨

 - [Jacopo Massa](https://github.com/jacopo-massa)
 - [Giulio Purgatorio](https://github.com/GPurgatorio)