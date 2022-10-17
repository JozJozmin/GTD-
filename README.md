# Global-Terrorism-Database-GTD---EDA
Exploratory Data Analysis on Global Terrorism Database (GTD)
## **Problem statement** 
The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.<br>

Explore and analyze the data to discover key findings pertaining to terrorist activities. <br>

## **Tools and Libraries used**
* Pandas 
* Numpy
* Seaborn
* Matplotlib
* Plotly
* geopy
* langid
* multiprocessing

## **Steps included**
####   **1. Data Collection & Understanding** 
 * Importing the required libraries
 * Loading the dataset into Pandas DataFrame
 * Look at some information about the data

####   **2. Data Cleaning and Manipulations** 
 * Feature selection <br>
 * Checking for duplicated rows  <br>
 * Fixing incorrect values <br>
 * Handling the missing values (multiprocessing applied)<br>
 * Updating the datatypes <br>
 * Adding new feature columns <br>

#### **3. Exploratory Data Analysis & Visualizations**
###### **Univariate Analysis | Bivariate Analysis |  Multivariate Analysis**
#### **Ask & answer questions**
1. What period of time had the highest number of attacks and which period had the lowest?
2. How many attacks extended more than 24 hours and how many are not?
3. Number of successful and unsuccessful accidents
4. Do the trend in attacks vary with respect to month?
5. What are the top 25 target countries in the world?
6. Identify the 50 targeted cities in the history
7. Top 10 active terrorist groups in the most affected city? 
8. Compare the outcomes (number of fatalities & wounds) from the above findings. Identify the years with the least & most casualties in the city. Discuss the reasons.
9. Comment on the global trend in terrorism with respect to the period of time.
10. Discuss the role deadliest wars in history. Comment on the adverse outcomes after these disasters
11. Which region was the most fallen victim of attacks? Which region has the lowest?
12. What are the regions containing the highest and the lowest casualties?. Compare casualties, the death toll, and number of wounds in each region.
13. Compare the trend in attack in each region with respect to the time?
14. Number of attacks VS success rate.
15. What kinds of weapons are used in terror attacks?
16. Who are the common victims of terror attacks?
17. Who are the top 25 active terror groups? 
18. Find out the targeted countries of the top 3 active groups in history. Comment out outcomes. 
19. Explore the variable 'extended' with respect to the method of attack
