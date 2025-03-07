# House Price Prediction Project

|Model	| MSE |	MAE |	R2 |
|---|---|---|---|
|random_forest|	47.043665|	4.073827|	0.241820|
|catboost|	47.136262|	4.072531|	0.240328|
|xgboost|	47.483248|	4.087922|	0.234736|
|linear	| 49.116138	| 4.225337|0.208419|
|ridge|	49.116276|	4.225343|	0.208417|
|lasso|	49.156077|	4.226551|	0.207775|
|decision_tree|	76.854116	|4.858190	|-0.238620|

🧐 _While our model's performance in terms of MAE, MSE, and R²-Score was not optimal due to our limited experience in model building at the time, the project demonstrated a strong grasp of the end-to-end predictive modeling process. From data collection and preprocessing to model deployment, we applied rigorous methodologies and best practices. This experience not only reinforced our technical foundation but also showcased our ability to approach complex problems systematically, laying the groundwork for future advancements in model optimization._

# About this Project Requirement
**Objective:**
In this project, performer will demonstrate their end-to-end skills in data scraping, data
preprocessing, feature engineering, modeling, and evaluation. The task involves predicting
house prices using machine learning models. The following requirements outline the project
details.

**Data Collection:**
1. Scrape and collect data items from the website https://batdongsan.vn/ban-nha/ to create
a comprehensive dataset.
2. Explore the website thoroughly to gather relevant information on each data item for
house price prediction.
3. Determine the size of the dataset to be collected.
Data Preprocessing and Feature Engineering:
1. Select appropriate data features for training the models.
2. Perform necessary data preprocessing steps such as handling missing values, encoding
categorical variables, and scaling numerical features.
3. Conduct feature engineering techniques to enhance the predictive power of the selected
features.

**Methodology:**
1. Visualize a heatmap based on the address of the listed house using kernel density
estimation at a certain time.
2. Design a methodology to address the house price prediction problem.
3. Consider various approaches and techniques for data analysis and modeling.
4. Justify the chosen methodologies and explain their effectiveness.
5. Recommended models include Linear/Ridge/Lasso Regression, Decision Tree/Random
Forest, and Gradient Boosting among others.
6. Encourage students to explore advanced models if feasible.
7. If deep learning models are used, prefer and recommend the PyTorch framework.
8. Choose relevant metrics for model evaluation.
9. If multiple models are employed, students should perform model benchmarks and
identify the best one for the problem.

**Implementation and Reporting:**
1. You are not required to implement the algorithms from scratch, but it is
recommended if possible.
2. Using Jupyter Notebook for implementation and report generation.
3. The report can be written in both Vietnamese and English.
4. Include a detailed explanation of the implementation process and any challenges faced.
5. The report should demonstrate a comprehensive understanding of the selected models
and techniques.
