# Hackerearth-amazon-business-research-analyst-hiring-challenge


### Competition hosted on <a href="https://assessment.hackerearth.com/challenges/hiring/amazon-business-research-analyst-hiring-challenge/">hackerearth.com</a>

# About

### Build a machine learning model that can calculate the time the delivery person takes to deliver the order.

### Final Score is 82.15

### Evaluation Metric 100*R2 score.

### File information
 * hackerearth-amazon-data-preparation.ipynb
   #### The dataset is in a little bit tricky format. Each and every row of the train and test dataset is in a separate text           file. To train a model have to create a data frame from the text file information.
 * hackerearth-amazon-hiring-eda.ipynb
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* hackerearth-amazon-hiring-model.ipynb
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * pycaret    
     #### Compared multiple regression models using pycaret’s compare_models function. Then took the top 3 models based on the           r2 score then blend the model by using pycaret blend_models function. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Approach_Hackerearth-amazon-business-research-analyst-hiring-challenge.pdf)
     

### Lightgbm Regressor Residual Plot
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Voting%20Regressor%20Residual%20Plot.png)

### Lightgbm Prediction Error Plot
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Voting%20Regressor%20Prediction%20Error%20Plot.png)

### Top 3 Models
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Voting%20Regressor%20Models.PNG)

### Lightgbm Feature Importance Plot
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Feature%20Importance%20Plot-%20%20%20Lightgbm%20Regressor.png)

### SHAP - Lightgbm Feature Importance Plot
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/SHAP%20Feature%20Importance%20Plot%20-%20Lightgbm%20Regressor.png)

### Time_taken_(min) distribution of train and test data
![Alt text](https://github.com/hariprasath-v/Hackerearth-amazon-business-research-analyst-hiring-challenge/blob/main/Time_taken_(min)%20distribution%20of%20train%20and%20test%20data.png)



     





