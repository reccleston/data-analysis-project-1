# data-analysis-project-1
#### First large data analysis class project

<img src="Images/alcohol_image.png" width="1000" height="400">


## Worldwide Alcohol Consumption Analysis 
Project link : 

### Motivation

The earliest records of alcohol brewing date more than 8000 years ago. There is an emerging view among evolutinary biologists that early departures from hunter/gatherer society can be directly attributed to the production of fermented beverages. Interestingly, while alcohol may have contributed to the genesis of civilization, it has simultaneously been villifed as an indicator of moral failing. 

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
<img src="Images/3_consumption_boxplot_by_continent.png" width="700" height="400">
<img src="Images/4_beer_to_happiness_regression.png" width="700" height="400">
<img src="Images/5_spirit_to_happiness_regression.png" width="700" height="400">
<img src="Images/6_alcohol_servings_to_happiness.png" width="700" height="400">
<img src="Images/7_wine_to_happiness_regression.png" width="7000" height="400">

### Limitations
* As we merged our datasets we had one list of values that was our North Star for how we approached the analysis - alcohol consumption (L). Focusing on alcohol consumption, that yielded data for 186 countries. [Insert Nadia] 

### Group Members
* Ryan Eccleston
* Alison Sadel
* Stephen Bretscher
* Nadia Richards
* Jean-Pierre Gilbert
    
### Declaration
The authors declare and solemnly affirm that this research has neither been funded by any political or religious groups nor are the authors in any way affiliated to any institutions with direct or indirect access to groups with biased interests. This research work has been carried out in the interests of technology and academics.

