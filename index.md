# Welcome to My GitHub Pages

Hi! This is **Yunxi Zhang**. Welcome to my ANLY 503 Portfolio!

Let me show you around! Click on the link to see my assignments and final project!


## Assignment 5
### Static Visualization Assignment
### Introduction & Data
In the previous assignment, you started working with the raw data dumps from the bank's systems, you tidied (is that even a verb?!?) some datasets, and you created an analytical dataset. An analytical dataset may be tidy or not -there is somewhat of a gray area there- however, it is a dataset that can be used for both data visualization and modeling.

We are providing an extended analytical dataset, with one record per account and many different variables/measurements/features for each account.

We are also providing the transactions.csv data as well so you can build some visualizations from the raw data.

### Instructions & Tasks
Use the data provided in the files above to create analysis and visualizations that answer the posed question or complete the task.

 1. Explore all accounts. Create visualizations that combine or these account characteristics:

    Whether an account has a credit card or not.
 
    Whether an account has a loan or not.
 
    The average balance for the account.[*Task1*](https://yz721.github.io/a5t1/)
 
 2. What is the distribution of all loans and what are their characteristics? [*Task2*](https://yz721.github.io/a5t2/)
 
 3. Is there a relationship between a good or bad loan and the time between an account is opened an the loan is created? Is there a specific set of accounts that seem to be at higher or lower risk of defaulting? [*Task3*](https://yz721.github.io/a5t3/)
 
 4. For the account with the highest number of transactions, make a time series line plot for the behavior of the account over time, including all debits and credits, the different methods, and the with the different categories.[*Task4*](https://yz721.github.io/a5t4/)
 
 5. Explore the validity of the data for the case whether or not an account has a credit card and whether or not they have associated credit card transactions. Is there anything worth noting? [*Task5*](https://yz721.github.io/a5t5/)


## Assignment 7
### Introduction
In this assignment you will visualize the flow of people between different states in the United States over the period of one year, using network graphs.

You are required to choose New York, Texas and two other states as the origin states (where people lived the previous year) for this visualization, and show graphically the relative numbers of people that moved to the top 10 destination states (current state, in the data set) from each of the origin states. You are expected to create a single graphic for this project. For clarity, for each origin state, you will find the top 10 states that people moved to from that state in the year in question, and the union of those states will be represented as nodes in the graph. You will not consider migrations to other countries or US Territories (Puerto Rico, Guam and others), but only consider migrations to the 50 states and District of Columbia.

### Tasks
1. You have to extract the data from this Excel file programmatically, i.e., using R and/or Python, not just copy it by hand to another Excel file. For this, you will have to open and understand the structure and format of the data in the file.

2. You will need to extract the data in the form of a data frame with 3 columns: source, target and count; the last column will contain the numbers of people who migrated from the source state to the target state in 2018

3. You can now use this data frame to create a graph object using igraph (R or Python), tidygraph (R) or networkx (Python)

4. You will create a single network graph, where the width of each edge representing the number of people moving between the two states, the color of the edge denoting the state of origin, and preferably arrows denoting the direction of migration. These aspects are required. You can style other aspects of the graph as you choose to improve readability.

5. Your submission will consist of one R Markdown file, named networks.Rmd and its corresponding HTML file networks.html, along with any files and folders created in the rendering process. 

[*Network Link*](https://yz721.github.io/network/)




## Final Project
This is Final project is the visulizations of NYC Restaurant Reviews in 2018.
Check to see which restaurant attracts you the most.

Visualizations contain each of the following types:

Exploratory

Geographical

Graph/Network

Time Series

Text

[*Entrance*](https://yz721.github.io/Sissizhang/#project-introduction)

# Have you found anything interesting? Have FUN !!!
