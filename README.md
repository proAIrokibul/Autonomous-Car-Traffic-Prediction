# Autonomous-Car-Traffic-Prediction

### **methodlogy**

It includes datacollection, data pre-processing, exploration data analysis, and feature extraction, model training, model selection which is then followed by the performance assessment, RMSE is used as the measuring criteria, and finally simulation is performed for real time performance of the model. The findings of this empirical analysis can be used to show how ML can be utilized to improve the traffic management systems that pertain to AVs.

### **Data Descryption**

The traffic data used in this study was obtained from the NYC Open Data API and includes the data from the month October of the year 2020.The variables contained in the dataset are traffic counts by hour, roadway segments, to, from, dates and direction information 

### **Data Preprosseing**
 
 Preprocessing work included dealing with missing data, duplicates, and outliers as well as feature creation including the day of the week and the month. To complement the above, checking for null values and duplicates was done, and it was found that the data was free from duplicates and null values. The above was done to ensure the presence of consistency in data, whereas the outliers were detected and handled using the Interquartile Range (IQR) technique. 
 
 ### **Model Development**
 
 The benchmark models that used in this study is Random Forest, Linear Regression, SVM and GBR the models were trained using default hyperparameters and the performance was assessed using RMSE. As a temporal model, LSTM model used the normalized traffic count and one hot encoded variable in the structured sequence format of the past 24 hours. This model constructed using Tensor Flow   was trained and tested in a like manner. RMSE, MAE and R-2 score measures were used to evaluate the models’ forecasts 

### **Summary and Findings**
 
 This research was able to incorporate a Random Forest model into an AV system in an attempt to predict traffic flow in real-time and suggest the most convenient path. The model proved to be accurate and its traffic predictions had to be used to change routes to avert traffic risks. The benchmark with an LSTM model underscored the merits of the Random Forest in this respect, and underlined the usefulness of model choice in AV scenarios. Therefore, the study emphasizes the signification of employing machine learning models to improve decision-making aspects of AV systems for improved efficiency of transport delivery.
 
### **Future Researche Directions**
 
 Possible extension to this research could be done in a way that involves feeding real-time data into the AV system so as to assess the system’s reliability in other real-world traffic conditions. Moreover, striving for the development of the multi-criteria route optimization algorithms, including such factors as current weather conditions, closed roads, or real-time traffic conditions, will allow for the improvement of the system’s operation. Researchers could also consider whether there is any benefit in using multiple models together, for example when one model is poor at identifying a particular type of traffic, this could be offset by another model which is good at this task, and the results of several models could then be averaged to produce an even better result. However, extending the analyzed traffic descriptions and used datasets could give a detailed assessment of the models and support creating more reliable and versatile AV systems.
 
 
