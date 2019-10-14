# Fundamentals of Data Analysis project
GMIT HDip Data analytics. Fundamentals of Data Analysis, semester 2, 2019 

**Introduction**
This project uses Python within a Jupyter Notebook to analyse the well-known 'tips' dataset, which is one of the example datasets contained within the Seaborn python package. The data relate to the tips given by diners at a restaurant, with seven variables recorded : 
1. total bill 
2. tip amount
3. gender of the person paying
4. whether or not the person paying was a smoker
5. day of the week
6. time of day - /lunch/dinner
7. size of the party

The first part of the project provides an overview of the variables, using basic statistics and plots.
The second part looks in more detail at the relationship between the total bill and the tip amount, using a variety of analytical tools.
The final section examines a number of pairs of variables to search for interesting correlations 

A snippet of the first few rows of the data is :
![alt text](sampledata.pdf)

**Method**
To analyse the dataset :
Double click the file 'Jupyter_Notebook' (file type IPYNB) within the repository to open the notebook.
Start at the top cell that contains Python code and work down the code cells sequentially to run each in turn, using 'Shift Enter' within each cell to run it. The text cells preceeding each code cell explain what is happening in the code.

To begin, python packages are loaded that are used for the analysis, including Seaborn.
The dataset is then obtained from Seaborn [1]

The user can display the full raw dataset if desired, and then obtain the basic statistics such as Mean and Standard Deviation for all the variables in numeric form, and produce various plots to clearly illustrate features of the dataset, such as the relationship between 
total bill and tip amount.


**Files**
The following files constitute the project :

jupyter_notebook.ipynb -  The Jupyter Notebook containing the code and text commentary
                        No run time arguments required, but 'help' can be accepted as an argument
                        Syntax : python iris_dataset.py [help]

sampledata.pdf      -  A copy of the first few rows of the dataset, to display in this Readme file


**References**

[1] https://analyticsindiamag.com/a-simple-introduction-to-pythons-seaborn-library/


