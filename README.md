# Linear Regression - EDA and Model Training

This project looks into training a Linear Regression model using Medical Data for an Insurance Company to know how much the charges would be for a client, depending on his health condition and habits. 

An exploratory data analysis was done before training the model, so the model can get the best possible data to acheive the best possible accuracy. 

## 📒 Key Takes

Linear Regressions lead with numerical data. For this project there was a need to factorize categorical data in order to be able to train the LR Model. After the EDA it was easy to understand what data could be relevant or not to predict our target variable of Charges, just by looking at the heatmap: 

<img src="https://github.com/athousanddetails/gustavolima-linearregression-eda/blob/main/assets/corr.png" width="500">


Althought the available data was not the best to have a good predictive model. 
Another key take is that boosting will not always improve your model, in this case trying boosting the hyperparameters and with a Ridge Model didn't return better results. The data you have to work with is a key factor in your model, as expected. 

For this project in mind, perhaphs having more data about the patients could help finding better features.
