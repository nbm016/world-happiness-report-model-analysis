# world-happiness-report-model-analysis
Model analysis for predicting happiness scores using the World Happiness Report (WHR) dataset.

<b>About - WHR Model Analysis Project</b><br>
Using the World Happiness Dataset, this analysis implements and fine-tunes Machine Learning Models to predict Happiness (Life Ladder) scores given social, financial, and geographic country data. <br>

Programming Languages and Libraries: Python, Pandas, Scikit Learn / Sklearn, Seaborn, MatPlotLib

Technologies: Jupyter Notebook, GitHub

Concepts: ML Lifecycle, Problem Identification and Importance, Data Exploration, Data Cleaning, Data Preprocessing, Feature Engineering, Model Development/Implementation and Hyperparameter Tuning, Model Evaluation, Data Visualization

Models: Random Forest Regressor, Linear Regression

<b>Machine Learning Lifecycle</b><br>

Machine Learning Problem Identification

ML Problem: Predict the happiness score given the features relevant to countries' social standing and wellbeing. Inspect the features that contribute the most to predicting happiness. 

Type of Problem: Supervised learning, regression predictions. 

Label for Regression Prediction: Life Ladder (known as the Happiness score in the World Happiness Report dataset). 

Importance of Problem: For organizations that are in the social justice, human rights, and ethics industries, determining where a country stands in terms of happiness in crucial to identifying what initiatives to invest in (positive initiatives) or divest from (negative initiatives). 

Feature list: Social Support, Freedom, Positive affect, Negative affect, Corruption, Life Expectancy at Birth, LogGDP, Region (Binary Indicators for Ten Regions).

Data Exploration: Scatterplot visualizations of feature relationships (strong linear correlation versus weak linear correlation). 

Data Cleaning: Mean imputation for missing values in all numerical-valued columns. 

Data Preproccesing / Feature Engineering: One hot encoding of the regions for each country (ten regions in total), feature selection of relevant features to the label. 

Key takeaways and figures: Both models performed well (R2 and RMSE metrics were used) when data was cleaned with feature engineering. The Random Forest model provided the ranking of features that contributed to the happiness predictions.


