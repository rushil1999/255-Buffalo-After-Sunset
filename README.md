Buffalo crime data analysis
------------------------------

## Table of Content
  * [Overview](#overview)
  * [Dataset](#dataset)
  * [Potential questions](#potential-questions)
  * [Directory Tree](#directory-tree)
  * [Algorithms used](#algorithms-used)
  * [Visualization Tool](#visualization-tool)
  * [Results](#results)
  * [Future Scope](#future-scope)

## Overview:
This project is based on crime data analysis of a city in New York state which is Buffalo. The dataset consists of the information related to the crimes that are happening in Buffalo city over the years. This project mainly to bring awareness to the people and the authorities of the Buffalo city on the crimes happening across the city by analyzing the crime data and drawing patterns from it. Visualizing the features in such a way that it is easy to understand the crime patterns and gain insightful information out of it.

## Dataset:
The below is the link to the dataset used in this project.
https://data.buffalony.gov/widgets/d6g9-xbgu


## Potential questions:
The analysis has been done to answer the following potential questions.
  * Which crime occurs most frequently?
  * At what time of the day the greatest number of crimes occur?
  * Is there any noticeable factor of crime happening rate over different location parameters (Police District, Council District)
  * What’s the trend in daily crimes over the years (Is it upward or down draft)?
  * What are the hot zones of a different crimes on the city map?

## Directory Tree:
```
├── clusters_data_subsets
│   ├── Cluster_Inci_Freqs
│   ├── Clusters
├── Graphs
├── Tableau Dashboard
├── .gitignore
├── Datasets.zip
├── Project Notebook.ipynb
├── README.md
```


## Algorithms used:
Methods/Algorithms used for this project are mentioned below:
1. PCA
2. KMeans

In addition to the above mentioned algorithms, analysis was also carried out using a visualization tool. The tool used for this purpose is Tableau.

## Visualization tool:
The visualzation tool used for this project is Tableau.
Below are some of the screenshots of the sheets present in the dashboard.
![image](https://user-images.githubusercontent.com/52078988/170855666-d493c379-75d7-42f1-a138-3bcbac260b2c.png)

![image](https://user-images.githubusercontent.com/52078988/170855674-cb22204d-e33f-4513-aa89-ba0bc880ad6a.png)

![image](https://user-images.githubusercontent.com/52078988/170855678-858ca4f5-8d3c-4908-8db4-90290892a92c.png)

![image](https://user-images.githubusercontent.com/52078988/170855684-3c1d6f6b-634d-402d-aed1-e998aeee5a47.png)

![image](https://user-images.githubusercontent.com/52078988/170855690-8a8719c0-adaf-41d3-b59e-826c8a5cdfd8.png)

The tableau dashboard can be accessed using the link present in the Table folder of the repo.

## Results:

Using KMeans and Tableau, the above mentioned potential questions are answered.


## Future scope:
Use other features present in the dataset to draw more patterns of crime. If we can get more data from the police department like what are the number of officers available and their shift schedule, then we can help form a patrol schedule with officers who are equipped with tools to handle such situations.
A lot of assaults are happening on weekend nights between 9-12 near some specific zip codes. This could mean that there are some clubs where these fights are happening. We can send notices to places where there are inciting violence and ask them to have stricter security and increase guards.



