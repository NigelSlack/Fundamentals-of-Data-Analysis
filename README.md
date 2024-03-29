# Fundamentals of Data Analysis project
GMIT HDip Data analytics. Fundamentals of Data Analysis, semester 2, 2019 

**Introduction**
This project uses Python within a Jupyter Notebook to analyse the well-known 'tips' dataset, which is one of the example datasets contained within the Seaborn python package. The data relate to the tips given by diners at a restaurant, as recorded by one waiter, with seven variables included : 
1. total bill 
2. tip amount
3. gender of the person paying
4. whether or not a smoker was in the party
5. day of the week
6. time of day - lunch/dinner
7. size of the party

The first part of the project provides an overview of the variables, using basic statistics and plots.
The second part looks in more detail at the relationship between the total bill and the tip amount, using a variety of analytical tools.
The final section examines a number of pairs of variables to search for interesting correlations 

A snippet of the first few rows of the data is :  

| total_bill | tip | sex | smoker	| day	| time | size |    
| ---------- | --- | --- | ------ | --- | ---- | ---- |  
| 16.99	| 1.01 | Female |	No | Sun | Dinner	| 2 |  
| 10.34	| 1.66 | Male | No | Sun | Dinner |	3 |  
| 21.01	| 3.5 | Male | No	| Sun |	Dinner | 3 |   
| 23.68	| 3.31 | Male	| No | Sun | Dinner |	2 |  
| 24.59	| 3.61 | Female |	No | Sun | Dinner	| 4 |   
| 25.29	| 4.71 | Male	| No | Sun | Dinner	| 4 |  
| 8.77	| 2	| Male | No |	Sun |	Dinner | 2 |   

**Method**
To analyse the dataset :
Double click the file 'Jupyter_Notebook' (file type IPYNB) within the repository to open the notebook.
Start at the top cell that contains Python code and work down the code cells sequentially to run each in turn, using 'Shift Enter' within each cell to run it. The text cells preceeding each code cell explain what is happening in the code.

To begin, python packages are loaded that are used for the analysis, including Seaborn.
The dataset is then obtained from Seaborn [1]

The user can display the full raw dataset if desired, and then obtain the basic statistics such as Mean and Standard Deviation for all the variables in numeric form, and produce various plots to clearly illustrate features of the dataset, such as the relationship between 
total bill and tip amount. Relationships between each of the other variables and total bill/tip are examined, and then interesting features commented upon.


**Files**
The following files constitute the project :

jupyter_notebook.ipynb -  The Jupyter Notebook containing the code and text commentary  
                          Double click to run

**References**

[1] https://analyticsindiamag.com/a-simple-introduction-to-pythons-seaborn-library/


