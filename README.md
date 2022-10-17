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
    1. Both the <code>month</code> and <code>day</code> columns includes value 0
    2. The <code>city</code> column contains both the 'unknown' and 'Unknown' values. <br>
 * Handling the missing values (multiprocessing applied)<br>
    1. Null values in the columns <code>num_injured</code> and <code>num_fatalities</code> were filled with forward filling <br>
    2. Null values in the columns <code>entity_name</code> , <code>specific_victim</code> and <code>victim_nationaliy</code> were replaced wih 'Unknown' <br>
    3. Null values in the <code>victim_subtype_cata</code> were replaced with 'Unnamed Civilian/Unspecified'<br>
    4. The possible Null values in the <code>city</code>,<code>longitude</code> and <code>latitude</code> column is found out by using geopy and langid libraries <br>
    5. Remaining Null values in <code>city</code> replaced with 'Unknown'.<br>
    6. The remaining Null values in the <code>longitude</code> and <code>latitude</code> columns are dropping out.<br>
 * Updating the datatypes <br>
   1. The datatypes of <code>num_fatalities</code> and <code>num_injured</code> is changing to int64 <br>
 * Adding new feature columns <br>
   1. Creating a new column <code>num_casualities</code> by adding <code>num_fatalities</code> and <code>num_injured</code>

#### **3. Exploratory Data Analysis & Visualizations**
###### **Univariate Analysis | Bivariate Analysis |  Multivariate Analysis**
