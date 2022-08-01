# Machine Learning for Genre Classification

*Note:* The datasets and guidance for this project have been sourced from [DataCamp](https://datacamp.com). Prerequisite scikit-learn knowledge and application has been done through the completion of the 'Supervised Learning With scikit-learn' course offered on DataCamp, the certificate of which may be found on my [LinkedIn](https://www.linkedin.com/in/speesapaty/).

<b>Objective:</b> Use machine learning methods to create and train a classification model that can identify Spotify song genres using non-genre data.

<b>Key Learning Points:</b> Principal Component Analysis (PCA), Logistic Regression, Decision Trees, K-means Clustering, K-Fold Cross Validation, libraries including seaborn, scikit-learn, pandas.

· According to the cumulative explained variance plot, 6 non-genre features are required to explain 85% of the variance in genre.

· Initial average precision report of Logistic Regression and Decision Tree model showed 87% each. 

· However, according to the classification report, hip-hop songs are disproportionately misclassified as rock songs. Thus, dataset balancing was required.

· Post balancing and ultimately, the Logistic Regression model performed better than the Decision Tree model, with average K-Fold cross-validation scores of 0.773 and 0.722 respectively.
