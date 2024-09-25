### AIRCRAFT SAFETY SURVEY

![Image_Alt](https://github.com/mwangikelvin201/dsc-phase-1-project-v3/blob/22386181de86a566db0914c2bdf6af1b9292a017/gettyimages-82096009-2048x2048.jpg)



### INTRODUCTION

The aircraft business has got alot of choices.They all differ in size,perfomance,price and safety.In this analysis the aim is to look into the safety of different aircrafts using the accidents data from the Aviation Data.csv.

### Problem Statement
Identify the safest aercraft for the airline to use.

### Main objective

The primary objective is to identify the aircraft that has the lowest risk for the business. This is from the data of accidents and incidents that have happened in the past involving different aircrafts. Also determining whether the aircraft models had anything to do with the accidents.

### Notebook Structure

Data collection

Data preprocessing

Exploratory data analysis(EDA)

Comparative analysis and Visualization

insights and recommendations



### Business understanding

The aircraft business is a very crucial business especially in terms of safety to passengers. This introduces the airlines to the big task of choosing the best aircrafts for the passengers not only in terms of comfort and luxury but most importantly the safety of the passengers. There is a vast choice of aircrafts in the market.Some which have had a good record safety wise and some which have been questionable in terms of safety due to their history of accidents which lead to loss of life and critical injuries and mechanical failures which potentially put the passengers at risk. It is ALWAYS very important to look into past data of aircrafts and see their records of the above before making a purchase for the safety of the passengers in order to avoid catastrophes through loss of life and tarnishing the company's reputation.

### Business questions regarding safety

What is the safest plane model in the market?

What is the safest plane Make among those involved?

How many engines are sufficient for our craft safety?

What engine type should be considered from those in the market?




## Project Overview

For this project, you will use data cleaning, imputation, analysis, and visualization to generate insights for a business stakeholder.

### Data Understanding and Analysis
## 1.Data Source
The data is from  [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the National Transportation Safety Board. 
## 2.Data Description

The contains includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
The data has all the plane features of all the planes that were involved in the accidents.
The data includes features such as plane model,plane make,number of engines ,type of engine as well as weather during the happening of the accident among other information.

 ### Methodology
 ## Data Wrangling: 
 The data underwent a comprehensive data wrangling process to ensure its quality and suitability for analysis. The following steps were performed during the data wrangling phase:

## Data Cleaning:
Handled missing values, duplicates, and formatting issues in the datasets to ensure data integrity. Applied appropriate techniques, such as imputation or removal, to address missing values.

 ### Explolatory Data Analysis
 Here we mostly used visualizations to gain insights of the relationship between our data variables . Bar graphs came in very handy to show the relationship between injuries and different plane models as well as other plane modifications.
 ## correlation analysis:
 Here we were carried a correlation analysis of our numerical columns to see how strong the relationship is.
  ### Visualizations
  Here is a visualization showing Top 10 Plane Models by Total Uninjured people
  
  ![Img_Alt](https://github.com/mwangikelvin201/dsc-phase-1-project-v3/blob/e3c28b149c53417da190f4c059ff880c6353d52b/my_plot1.png)
  
  Here is a visualisation showing Top 10 Plane Make by Total Uninjured people
  
 ![Img_Alt](https://github.com/mwangikelvin201/dsc-phase-1-project-v3/blob/f0dac55d2c1ab7188f3e120a6eea7cf6b2a1fd24/my_plot2.png)
 
 Here is a visualisation showing Top 10 Number of Engines by Total Uninjured people
 
 ![Img_ALt](https://github.com/mwangikelvin201/dsc-phase-1-project-v3/blob/810511850b4177da235ccef69f806280a83bfb30/my_plot4.png)
 
 Here is a visualisation showing Top 10 Engine Type by Total Uninjured people
 
 ![Img_Alt](https://github.com/mwangikelvin201/dsc-phase-1-project-v3/blob/5d08b823a5c70d28bcfebcc0ddddb795f7eee0a7/my_plot3.png)
 
### Conclusions.
Although the hope is that we get a plane that never gets involved in an accident,we are not yet there. Nevertheless we can always determine the craft that always has the best chances of survival incase an accident happens.

Based on the Explolatory data analysis(EDA) conducted above, we can draw the following conclusions:

1.The plane "Model" plays a very big role in survival and minor injuries of the passengers. From our plots above it is evident that although the Model 737 leads with most fatal and serious injuries which is very devastating.On the other hand it also leads with most uninjured people and that is a positive insight.

2.The plane Make is also a very crucial in determining the survival rate and injury state of those on board. The make "cessna" has a very poor record in injury rate.It leads in all the injury records with most casualties. It has the most seriously injured,fatal injuries as well as the minor injuries. That is quite alarming for the model.

On the other hand Boeing has the most uninjured people so it is correct to say that it is the safest plane make above all others involved in this analysis.

3.On the engine make,it is seen that the planes with a turbo fan engine type leads with the most uninjured people. It is also correct to say the reciprocating engine(Which is used on most aircrafts on the analysis) is relatively safer because it has the most minor injuries. It is something posistive considering it is used in most of the aircrafts.

4.The number of engines is another aspect that cannot be ignored in our analysis.Planes with one engine caused most fatal injuries and minor injuries.The ones with more than one engine caused less and less with crafts having two engines being responsible for the most uninjured people.

### Recommendations
Based on our conclusions and observations,we can go ahead and make the following recommendations.

1.Model: For the model The airline should consider the 737.Even though it leads on the injuries,it also has an advantage on all others in the uninjured number of people.(The model 737 is also linked to the make boeing which has proven to be the safest considering the Make.It is popularly known as Boeing 737)

2.Make: The Boeing has proved to be the best in Make considering the safety of the passengers.The airline should consider the boeing make for the safety of the passengers.

3.Engine make: The airline should consider  a craft that makes use of the turbo fan engine type.This is the engine found in the Boeing 737 plane and has great capabilities of perfomance in high altitudes and great speeds.

4.Number of engines: on the engine number,anything more than one engine is considerably safe. Two seems to be the mostly used and has proved to be very safe.

More than two engines is practical but also very inefficient in terms of fuel given that most crafts that utilize four and more engines are mostly millitary.Two engines would be very okay for the airlines flights.

## Conclusion

Based on this analysis, the Boeing 737 stands out as the safest option. It combines a favorable injury record with robust performance capabilities. Airlines can tailor the aircraft for luxury and commercial needs, ensuring both safety and passenger satisfaction.

# dashboard
For a comprehensive view of the data and insights, check out the dashboard [here](https://public.tableau.com/app/profile/kelvin.mwangi/viz/Comparisonofdifferentinjurystatisticswithvariousplaneaspects/VisualsoftheAviationDataSet?publish=yes)

