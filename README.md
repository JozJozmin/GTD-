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
1. What percentage of total attacks had extended more than 24 hours?
2. Percentage of successful and unsuccessful attacks
3.  Do the trend in attacks vary with respect to month?
4. Identify the trend in attack over the years. Which year had the highest & lowest number of attacks?
5. Comment the global impact of terrorism with appropriate visualization.
6. Identify the top 50 targeted cities in the history
7. Identify top 5 active terrorist groups in the most affected city?
8. Compare the outcomes (number of fatalities & wounds) of most victimized city. Identify the years with the least & most casualties in the city. Discuss the reasons.
9. According to the data, which are the top 25 countries currently at risk of increased terrorist activity?
10. Discuss the impact of terrorism on the worst affected countries.
11. Death tolls with respect to year, country & region
12. Compare the Worst affected countries Versus Rest of the world
13. Which region was the most fallen victim of attacks? Which region has the lowest?
14. What are the regions containing the highest and the lowest related deaths?. Compare casualties, the death toll, and number of wounds in each region.
15. Compare the trend in attack in each region with respect to the time?
16. Number of Successful and Unsuccessful attacks per year
17. What kinds of weapons are used in terror attacks?
18. Who are the common victims of terror attacks?
19. Who are the top 25 active terror groups?
20. Identify the attacks by top 3 ranked groups over the years
21. Find out the targeted countries of the top 3 active groups in history. Comment your findings.
22. Explore the variable 'extended' with respect to the method of attack.

#### **Summary and Conclusions**
#####  **Insights:**
* Last 6 years in the data (2012 -17) are found to be the most prominent periods of attacks according to the data. Global terrorism peaked in 2014 with more than 16,700 attacks in a single year, followed by the year 2015 with more than 14,000 attacks. The year 1971 had the least number of attacks in the globe with 463 attacks.
* All three: the number of fatalities, number of wounds, and total number of attacks are interconnected.  It makes sense that the last 6 years in the data had the highest number of related deaths, wounds, and property damages. 
* The impact of terrorism reached its peak in 2014.  From 2011-14, the number of attacks increased to 232%, related deaths increased to 474%, confirmed wounds increased to 212% and property damages increased to approx.193%.  Although related deaths & property damages have declined since 2015 with respect to the number of attacks but related wounds have increased to 5% from 2014.
* Baghdad city, the capital of Iraq has experienced the highest level of terrorism in the globe with more than 7500 incidents. Followed by Karachi in Pakisthan, Lima in Peru, Mosul, and Belfast victimized more than 2000 times. Karachi, Lima, and Mosul collectively had fewer attacks than Baghdad city alone faced.
* Baghdad city was severely victimized over the last 6 years. More than 46% of total related deaths in the city were reported during these periods. Since the government is not able to find the terror group responsible for 86% of the attacks that happened in the city, we can confirm wars in the specified period. The city has faced severe damages during this time due to the Iraq War which lasted until 2011 and subsequent insurgency and renewed war that lasted until 2017. The effect of the United States invasion of Iraq (which lasted from 2003-11) is also clearly visible in the graph.
* Iraq was the most affected country by terrorism in history, followed by Pakistan, Afghanistan, India, Colombia, Philippines, Peru, and so on. Iraq alone was victimized more than 24,500 times throughout the time period 1970 – 2017 had more than 80K related deaths which is almost 3 folds more than the attacks that happened in the country. Related wounds in the country were 6 times more than the number of attacks.
* Pakistan, Afghanistan & Nigeria also had more than 24k fatalities. Nigeria had a higher number of fatalities compared to the lesser number of attacks. Since the most victimized countries are densely populated, it makes sense that attacks in these countries claim more lives.
* Iraq, Afghanistan, Pakistan, Nigeria & Syria are severely victimized in the 20s. This period of time is famously known as the Syrian Civil War, Iraq War, Afghanistan War, and The War Against Boko Haram. India shows a higher number of attacks in the late 90s and early 20s. 
* From 2005 onwards, more than 50% of global terrorism-related deaths are reported from Iraq, Pakistan, Afghanistan, and Syria only. In 2007 alone, approximately 72% of global terrorism-related deaths had been reported from these countries only.
* There are 12 categorized regions are there in the data. The Middle East and North Africa is the most affected region by terrorism where 27.9% of total global attacks had been reported resulting in over 32% of all terrorism deaths and over 40% of all terrorism wounds had been recorded.  Followed by South Asia with 25% of total global attacks resulting in 23.5% of total related deaths and 25.7% of related wounds. However, the majority of the attacks have been recorded after the year 2000. Since most targeted countries are from this region the above findings make sense.
* It is really appreciable that East Asia, Central Asia, and Australasia & Oceania are the most peaceful regions in the globe according to the data. These regions collectively contribute only less than 1% of attacks happening all over the world. Especially the region Australasia & Oceania had only 0.03% of all terrorism deaths and 0.04% of all terrorism wounds.
 This may be because:
  1. These regions include countries that have the most active counter-terror units to protect their citizens. 
  2. consists of countries that are least densely populated.
* Bombing/Explosion was found to be the most prevalent method of attack that covered 49% of global attacks, followed by Armed Assault and Assassination. Hijacking, Unarmed Assault and Hostage Taking were the rare methods of attack (covers <1% of global attacks). Implementing more securities for disarmament or bomb detection over countries will be more beneficial for reducing terrorism related violence and its consequences.
* Approximately 24% of victims of terrorism were 'Private Citizens & Property' followed by the 'Military' with 15% and police with 13.6%. It makes sense. Since war is always a conflict between countries and groups, the Military, Citizens & Property will be the top victims of fire and explosions always. 
* Taliban is found to be the most active deadliest group in history and was responsible for 4% of total global terror attacks. Taliban’s first attack was on 1995 . During 20s they have grown into most deadliest group in Afghanistan with 7403 attacks that cause 30342 deaths and 29598 wounds.
* The newly emerged group in 2013 , Islamic State of Iraq and the Levant (ISIL) who is responsible for 3% of total global terror attacks was the second deadliest group in the history. The group was severly active on Iraq during 2013 -17.
* The 3rd ranked group  Shining Path (SL) with 2.4%  total global terror attacks  was the most deadliest group during 1980-1997. After 1992, there is a significant reduction in attacks initiated by SL lowering from 277 to 73. Peru was the most fallen victim of SL.
* Followed by Al-Shabaab in 4th rank with 1.8% total global terror attacks , Farabundo Marti National Liberation Front (FMLN) in 5th rank with 1.7% of total attacks and so on.
* According to the data, if an attack is extended more than 24 hours , 85% of chances that the attacks will be Hostage Taking (Kidnapping) and 6% chances for  Armed Assault. On the other hand if an attacks is not extended more than 24 hours, in 50% of cases the method of attack will be Bombing/Explosion. Unarmed Assault, Hostage Taking (Barricade Incident), and Hijacking are the rarely reported method for attacks within 24 hours.

#### **Challenges Faced**
1. Large amount of null values were present in the data.
2. Presence of incorrect values in the meaningful features. 
3. Selection of right visualization techniques for the analysis.
