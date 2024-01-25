Project Name: Clickbait Detection




Description:
This project focuses on building a clickbait detection system using a combination of exploratory data analysis (EDA), text preprocessing, and machine learning techniques. The implementation includes supervised learning with logistic regression and decision tree classifiers, as well as unsupervised learning using k-means clustering. The goal is to identify clickbait headlines and evaluate the performance of the models.



Usage:

Run the Jupyter notebook or open in Colab `TextMining.ipynb` for a step-by-step walkthrough of the project.



Project Structure:
- `TextMining.ipynb`: notebook containing the main project code.
- `Text Mining and Search Report.pdf`: contains the report of the project.



Dependencies:
- pandas
- seaborn
- nltk
- scikit-learn
- matplotlib

Data:
The project uses a clickbait dataset (`clickbait_data.csv`). https://www.kaggle.com/datasets/amananandrai/clickbait-dataset

Exploratory Data Analysis:
EDA is performed to gain insights into the dataset, visualize the distribution of clickbait and non-clickbait headlines, and check for missing values.

Text Preprocessing:
Text preprocessing converting raw text into a format suitable for machine learning.

Supervised Learning:
Logistic regression and decision tree classifiers are trained on preprocessed text data. 

Unsupervised Learning:
K-means clustering is applied to group headlines based on TF-IDF vectors. 

Evaluation Metrics:
The project uses various evaluation metrics, including accuracy, precision, recall, F1-score, ARI, and V-Measure Score, to assess the performance of both supervised and unsupervised learning models.

