# DataScience Capstone Project: DrugReviews Dataset Insights
Data analysis of drug reviews dataset as last part of project requirements of [Udacity Data Science Nanodegree Program](https://learn.udacity.com/nanodegrees/nd025/parts/cd1971/lessons/c20e1b63-c711-475b-b1ba-3ea987081193/concepts/dc9cae33-1b66-484a-95e4-61c166c64cf5)

## Project Goal
The main aim of this project is to analyze in depth the data of online drug reviews dataset Drug Review dataset of UCI found in [Kaggle](https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018) in order to fullfil the business requirements of this capstone project focused on the construction of predictive models:
* Classification of Emotional Inclication based on Drug Review
* Multiclassification of Medical Condition based on Drug Review

## Data Source Description
* Data files: Cannot upload the dataset file it was very large for GitHub.
* Jupyter notebook: Data Science Capstone Project.ipynb 

## Library Packages
Warnings, WordCloud, Numpy, Pandas, Tabulate, Matplotlib, Seaborn, Nltk, String, TextBlob, Sklearn, Re

## Summary of Results
An exploratory data analysis is implemented in order to undestand better the data structure and peculiarities related to this dataset, such as missing values and etc and we focus finding relevant insights and trends related to the drug consumption such as average drug reviews per drug category or how many drugs are used per medical condition or which the most frequent medical condition. Therefore, we also conducted a sentiment analysis in order to harvest the latent information of drug reviews related to their sentiment and perform additional exploratory analysis to the sentiment content of drug reviews.
We decided to mainly focus only on the data of top 10 frequent medical conditions excluding the reviews that are associated with neutral sentiment, thus the final analysis was based on 94960 drug reviews. The drug reviews which served as main input for the primary outcomes such as sentiment and medical condition where preprocessed removing any noise related to data imperfection or typed error. Therefore, we applied a model selection procedure adapting the cross validation methodology for different machine learning models in order to evaluate their performance using classification metrics.
All the analysis is shared here [https://medium.com/@alexispolymeropoulos/athens-airbnb-data-driven-insights-2baf01f52814](https://medium.com/p/e17677dca62b/edit)

## References
[Rohan Harode] (https://medium.com/sfu-cspmp/draw-drug-review-analysis-work-96212ed98941)

[Hamiz Ahmed] (https://towardsdatascience.com/predict-patients-medical-condition-based-on-medicine-review-part-1-c22ea39d9976)

[Kaggle] (https://medium.com/sfu-cspmp/draw-drug-review-analysis-work-96212ed98941

[Harsh Jain] (https://towardsdatascience.com/predict-patients-medical-condition-based-on-medicine-review-part-1-c22ea39d9976)
