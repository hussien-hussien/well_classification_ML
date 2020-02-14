# Tanzanian Water Pump Classification Challenge

This project was the result of a challenge held in collaboration with Driven Data & Taarifa.

In their own words:
>Taarifa is an open source platform for the crowd sourced reporting and triaging of infrastructure related issues. Think of it as a bug tracker for the real world which helps to engage citizens with their local government. We are currently working on an Innovation Project in Tanzania, with various partners.

The goal of this project is to predict the operating condition of a waterpoint for each record in the dataset.

##### Description of Data Given\n
3 files have been provided: training_labels, training_values, test_values\n


+ `amount_tsh` - Total static head (amount water available to waterpoint)
+ `date_recorded` - The date the row was entered
+ `funder` - Who funded the well
+ `gps_height` - Altitude of the well
+ `installer` - Organization that installed the well
+ `longitude` - GPS coordinate
+ `latitude` - GPS coordinate
+ `wpt_name` - Name of the waterpoint if there is one
+ `num_private` -
+ `basin` - Geographic water basin
+ `subvillage` - Geographic location
+ `region` - Geographic location
+ `region_code` - Geographic location (coded)
+ `district_code` - Geographic location (coded)
+ `lga` - Geographic location
+ `ward` - Geographic location
+ `population` - Population around the well
+ `public_meeting` - True/False
+ `recorded_by` - Group entering this row of data
+ `scheme_management` - Who operates the waterpoint
+ `scheme_name` - Who operates the waterpoint
+ `permit` - If the waterpoint is permitted
+ `construction_year` - Year the waterpoint was constructed
+ `extraction_type` - The kind of extraction the waterpoint uses
+ `extraction_type_group` - The kind of extraction the waterpoint uses
+ `extraction_type_class` - The kind of extraction the waterpoint uses
+ `management` - How the waterpoint is managed
+ `management_group` - How the waterpoint is managed
+ `payment` - What the water costs
+ `payment_type` - What the water costs
+ `water_quality` - The quality of the water
+ `quality_group` - The quality of the water
+ `quantity` - The quantity of water
+ `quantity_group` - The quantity of water
+ `source` - The source of the water
+ `source_type` - The source of the water
+ `source_class` - The source of the water
+ `waterpoint_type` - The kind of waterpoint
+ `waterpoint_type_group` - The kind of waterpoint


-----

The first time around, using Random Forest Classifier and a ton of data cleaning, I was able to predict water pump conditions with 0.7850 accuracy. This is still a work in progress and I think I'll have the accuracy at least at 0.81 in the near future.



I've split this project into 3 different notebooks with different purposes designed to mimic the CRISP-DM process. 
+ *Exploratory Analysis* where I simply explore the data and create a few visualizations in order to better understand the nature of the data and answer a few initial questions.
+ *Data Cleaning* Most of the work was done here, the dat needed a ton of cleaning. Most of it was is very high dimensional catagorical data that had to be converted into numerical data with some sense.
+ *Modelling* This is where I began to use the cleaned data set to experiment with training models and making predictions.


Cool stuff I learnt about/ Experimented with:
+ Cross-Validation
+ Linear Discriminant Analysis
+ How to deal with high dimensionality
+ Feature Selection
+ Feature Engineering
+ Data Cleaning
+ More of Pandas & SciKit Learn
+ Hyperparameter Tuning
+ Random Forest Classification
+ 

---

#### Next steps:
+ Write a nice write-up where I can help the data tell it's story in a structured and easy to folow manner
+ Improve the model accuracy
  + I think more of the gains will come from tweaking the data rather than optimizing the models at this point.
+ Create more visualizations. Most of what I've done with the exploratory phase was for me to understand the data and not so much to communcate the data to another viewer.




