# data-analysis-project-1
#### First large data analysis class project

<img src="Images/alcohol_image.png" width="1000" height="400">


## Worldwide Alcohol Consumption Analysis 
Project link : 

### Motivation

The earliest records of alcohol brewing date more than 8000 years ago. There is an emerging view among evolutinary biologists that early departures from hunter/gatherer society can be directly attributed to the production of fermented beverages. Interestingly, while alcohol may have contributed to the genesis of civilization, it has simultaneously been villifed as an indicator of moral failing among many religious and cultural groups. Health and safety policies surrounding alcohol abound and have the potential to influence society greatly. Consequently, we looked to examine alcohol data.   


### Tasks Involved
I. Corpus Collection
API calls were made to Open Weather and Google. We also collected data from 'World Health Organization,' 'Our World in Data,' and Kaggle. 

II. Pre-processing and Data Normalization
Nine lists(csvs) were merged to create our dataset with information for 186 countries:
	
* Continent/Geographic region
* Climate 
* Exports 
* Major Industry 
* Alcohol consumption 
* Mental Health 
* Life expectancy 
* Happiness Index 
* Country Capitals
* Wine Productions
* Consumption By Alcohol/Type
* Wine Consumption
    
Preprocessing the dataset involved an iterative series of tasks like removing Nans, renaming columns for consistency, deleting extraneous columns and searching/removing duplicates. 

III. Analysis and visualization
Visualizations were built using variety of Python libraries like Matplolib and Seaborn.

### Output
<img src="Images/1_drinking_bin_correlation_matrix.png" width="700" height="400">
<img src="Images/2_top_5_pie_chart.png" width="700" height="400">
<img src="Images/map.png" width="700" height="400">
<img src="Images/4_continent_boxplot.png" width="700" height="400">

### Analysis 

### Limitations
* As we merged our datasets we had one list of values that was our North Star for how we approached the analysis - alcohol consumption (L). Focusing on alcohol consumption, that yielded data for 186 countries. 

* For data on GDP, Life Expectancy, Happiness score and Mental health disorders, the number of datapoints decreased from 186 to 141 rows/values (countries). The biggest reduction in data available was especially apparent in reference to the Oceania continent with data only available for Australia/New Zealanda. Due to limited sample size, the analysis from that particular continent cannot be considered statistically significant when taking into consideration GDP, Life expectancy, Happiness score and Mental health disorders.

* Data collections method may vary by country. Additionally, while consumption may be listed as nominal in certain muslim-dominated countries, there likely exists underground consumption that may not be reflected in the data.

* This was an exploratory analysis and as a continuation, it may be beneficial to look at other indicators like violent crime, religion, education etc. 


### Group Members
* Ryan Eccleston
* Alison Sadel
* Stephen Bretscher
* Nadia Richards
* Jean-Pierre Gilbert
    
### Declaration
The authors declare and solemnly affirm that this research has neither been funded by any political or religious groups nor are the authors in any way affiliated to any institutions with direct or indirect access to groups with biased interests. This research work has been carried out in the interests of technology and academics.

