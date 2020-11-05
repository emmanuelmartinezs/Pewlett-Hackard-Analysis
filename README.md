# Pewlett Hackard Analysis

**Data Analyst at PyBer**
Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Overview of Project
PyBer CEO has given you and your manager a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. 

> Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

1. ***Deliverable 1***: A ride-sharing summary DataFrame by city type
2. ***Deliverable 2***: A multiple-line chart of total fares for each city type
3. ***Deliverable 3***: A written report for the PyBer analysis [`README.md`](https://github.com/emmanuelmartinezs/PyBer_Analysis). 

## Resources and Before Start Notes:

* Data Source: `PyBer_Challenge_starter_code.ipynb` named later as `PyBer_Challenge.ipynb`
* Data File: file.csv
* Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas

For more information, read the [`Documentation on Python data typess`](https://docs.python.org/3.6/library/stdtypes.html#numeric-types-int-float-complex). 

## Check the Version of Matplotlib
Before we get started on any project, it's good practice to make sure we have the latest version of the software we'll be using. Because we'll be using Matplotlib, let's check to make sure we have version 3.1.0 or greater
Follow the instructions below for your operating system.

**Check the Version on the Command Line in macOS or Windows**
To begin, launch the command line and activate the PythonData environment.

To activate the **PythonData** environment on the command line, type `conda activate PythonData`.

**macOS look similar to this:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/Pyvr1.PNG?raw=true)


**Windows look similar to this:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/Pyvr2.PNG?raw=true)


At the Python prompt ( >>>), type import matplotlib and press Enter to import Matplotlib.

Next, to check the version of Matplotlib, type `matplotlib.__version__` (there are two underscores before and after "version") and press Enter
The output should be 3.1.0 or greater.

**Extra Note:** 

To update Matplotlib for your development environment; with your PythonData environment activated, type `conda install -c conda-forge matplotlib` at the command prompt and press Enter.

In Jupyter Notebook, create a new file if one hasn't been created. Add the following code to a new cell.

**Check the Version in Jupyter Notebook**
Alternatively, you can check the version of Matplotlib in Jupyter Notebook. To do that, follow these directions

To start Jupyter Notebook, navigate to the Class folder on your computer using the command line or Anaconda prompt.

Activate the PythonData environment if it's not activated. Type and run `jupyter notebook`.

**From Anaconda Terminal:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/jpvr1.PNG?raw=true)

**From Jupyter Notebook Data:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/jpvr2.PNG?raw=true)


For more information about the latest Matplotlib version, see the Matplotlib documentation [Links to an external site.](https://matplotlib.org/3.1.0/index.html). 


**Matplot over Jupyter Note:**
Here a Simple Example how it looks a `Matplotlib.pyplot` chart:

**Code and Graph**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/chartsample1.PNG?raw=true)



**Annotate Charts Using the MATLAB Method**
Here are a few methods that you can use to annotate charts using the MATLAB method:

It is highly recommended to add x-axis and y-axis labels and a title to every graph you create so the viewer knows what it conveys. If you have more than one line or bar on a graph, making each line or bar stand out with a distinct color or line style is helpful, as is adding a legend for each dataset that the lines or bars represent. In addition, thoughtfully setting your x-axis and y-axis ranges can make the data more appealing.

**Matplotlib Functions and Feature**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/MatplotlibFunc.PNG?raw=true)


**Extra Note: Create a Vertical Bar Chart**

To create a bar chart using the object-oriented interface method, use the `ax.bar()` function and add the x and y data parameters inside the parentheses.

**Matplotlib Functions and Feature**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/VertBarChartExample.PNG?raw=true)


## Deliverable 1:  A Ride-Sharing Summary DataFrame by City Type
### Deliverable Requirements:

1. The total number of rides for each city type is retrieved. 
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.  
5. The average fare per driver for each city type is calculated. 
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.
 
### Results with detail analysis:

**1. The total number of rides for each city type is retrieved.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.1.PNG?raw=true)

**2. The total number of drivers for each city type is retrieved.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.2.PNG?raw=true)

**3. The sum of the fares for each city type is retrieved.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.3.PNG?raw=true)

**4. The average fare per ride for each city type is calculated.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.4.PNG?raw=true)

**5. The average fare per driver for each city type is calculated.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.5.PNG?raw=true)

**6. A PyBer summary DataFrame is created.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.6.PNG?raw=true)

**7. The PyBer summary DataFrame is formatted as shown in the example.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.7.PNG?raw=true)



### Deliverable 2: A multiple-line chart of total fares for each city type
### Deliverable Requirements:

1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.
2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."
3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.
4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.
5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 


### Results with detail analysis:

**1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.1.PNG?raw=true)

**2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.2.PNG?raw=true)

**3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.3.PNG?raw=true)

**4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.4.PNG?raw=true)

**5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.**

> Image with `Jupyter Notebook` & `Python` Code below.

**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.5.PNG?raw=true)



## Deliverable 3: A written report for the PyBer Analysis
### The analysis should contain the following:

1. **Overview of the analysis** 
* Explain the purpose of the new analysis:

    > The purpose of this written report for Data Analyst at PyBer is to create a complete summary of the Ride-Sharing data by city type. Including a quick summary of line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib libraries. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics. Our Final Analysis include multiple-line graphs of total weekly fares for each city type.


2. **Results** 
* Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types:

    > * The Suburban fares started around $1,000, and the analysis was not profitable, fare dropped in March and in mid-April.  
    > * The Rural fares started at around $200, the analysis shows fares increase and dropped till the end of April.  
    > * The Urban fares start with an average of $1,800 with a consistent increase around 2,300. 
    
    > The PyBer summary DataFrame, 
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/1.7.PNG?raw=true)

     > A multiple-line chart of total fares for each city type,
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/2.5.PNG?raw=true)

     > PyBer Ride-Sharing Data (2019), 
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/analysis/Fig1.png?raw=true)      

3. **Summary** 
* Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types:

    > **1)** From our analysis, we can predict that there are good opportunities to expand the business in rural and suburban cities, including hiring drivers to operate and explode business in rural and suburban cities.

    > % of Total Drivers by City Type,
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/analysis/Fig7.png?raw=true)
    
    > **2)** The Urban cities fare is the highest and consistent, giving us great and new business opportunities to expand rides.  

    > % of Total Fares by City Type, 
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/analysis/Fig5.png?raw=true)
    
    > **3)** The Rural cities fare is the lowest of the other two city types (Urban and Suburban cities), in addition, fares never intersect.  Knowing that all fares never intersect, we can expand fares and increase business financial income to the company without affecting our rate.

     > Total Fare by City Type,
    ![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true) 


#### PyBer Analysis Completed by Emmanuel Martinez
