# World Happiness Report Model Analysis
Model analysis for predicting happiness scores using the World Happiness Report (WHR) dataset.


## 🌎 <b>About WHR Model Analysis Project</b> 🌎<br>
Using the World Happiness 2018 Dataset, this analysis implements and fine-tunes Machine Learning Models to predict Happiness (Life Ladder) scores given social, financial, and geographic data for 164 countries. <br>

<b>Dataset: </b> World Happiness 2018 CSV and Excel Files

<b>Programming Languages and Libraries: </b>Python, Pandas, Scikit-Learn / Sklearn, Seaborn, MatPlotLib

<b>Technologies:</b> Jupyter Notebook, GitHub

<b>Concepts:</b> ML Lifecycle - Problem Identification and Importance, Data Exploration, Data Cleaning, Data Preprocessing, Feature Engineering, Model Development/Implementation and Hyperparameter Tuning, Model Evaluation, Data Visualization

<b>Models:</b> Random Forest Regressor, Linear Regression

<br>

## 🤖🧠 <b>Machine Learning Lifecycle</b> 🧠🤖<br>

### Machine Learning Problem Identification

<b>ML Problem:</b> Predict the happiness score given the features relevant to countries' social standing and wellbeing. Inspect the features that contribute the most to predicting happiness. 

<b>Type of Problem:</b> Supervised learning, Regression predictions. 

<b>Label for Regression Prediction:</b> Life Ladder (known as the Happiness score in the World Happiness Report dataset). 

<b>Importance of Problem:</b> For organizations that are in the social justice, human rights, and ethics industries, determining where a country stands in terms of happiness in crucial to identifying what initiatives to invest in (positive initiatives) or divest from (negative initiatives). 

<b>Feature list:</b> Social Support, Freedom, Positive affect, Negative affect, Corruption, Life Expectancy at Birth, LogGDP, Region (Binary Indicators for Ten Regions).
<br><br>

### Data Exploration

Scatterplot visualizations of feature relationships (strong linear correlation versus weak linear correlation). 
<br><br>

### Data Cleaning

Mean imputation for missing values in all numerical-valued columns. 
<br><br>
### Data Preproccesing / Feature Engineering

One hot encoding of the regions for each country (ten regions in total)<br>
Feature selection of relevant features to the label. Relevant features identified have some linear correlation with the happiness label.  
<br>
### Model Selection and Implementation 

Random Forest Regressor (Ensemble Learning Method), Linear Regression
<br><br>

### Model Evaluation and Refinement

Regression Prediction Evaluation Metrics: R2 and RMSE

<i><b>Random Forest:</b></i><br>
R2 = Range between 88% to 90% <br>
RMSE = Range between 31% to 35%

<i><b>Linear Regression:</b></i> <br>
R2 = 91% <br>
RMSE = 30%

<b>Key Takeaways and Figures</b>

Both models performed well (R2 and RMSE metrics were used) when data was cleaned with feature engineering. The Random Forest model provided the ranking of features that contributed to the happiness predictions.
<br>

