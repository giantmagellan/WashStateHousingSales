# Bryan Flores
---------------------------------------------
### Summary 
This branch performs the following functions:
   1. Performs data cleaning of the Kings County, WA dataset. <br>
       a. Reconstructed the following variables: dates and sqft living <br>
       b. Reorganized the dataset by yearly quarter.<br>
       
   2. Exploratory analysis and visualizations of the relationships between housing living area and price from May 2014 and May 2015.<br>
   
   3. Utilize a Batch Gradient Descent learning algorithm to predict the price of housing based on the three features showing the highest correlation to price:<br>
       a. Bedrooms<br>
       b. Living Area (sqft)<br>
       c. Grade

### Results
Method: Batch Gradient Descent <br>
Optimal Learning Rate: 0.15 <br>
Metric: Pearson <br>
Accuracy: 70% <br>

Bedrooms | Square Feet | Predicted Price
--- | --- | ---
1 | 900 | $250,985.93
2 | 1400 | $347,977.84
3 | 1850 | $435,293.07
4 | 2400 | $541,961.64
- Constant: Grade as 7
