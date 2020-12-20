![ccba_rj](ccba_rj.png)

# Climate Change Belief Sentiment Analysis from Tweets

Predict an individual’s belief in climate change based on historical tweet data & provide insights into the various climate change sentiment classes.

Climate change has long been acknowledged by the scientific community as a critical issue facing mankind. However, even with scientific consensus around Climate Change, public opinion on the subject may vary. The goal of this challenge is to build a Classification Machine Learning model that will determine whether a person believes in Climate Change using tweet data. This project also provides insights of public opinion of Climate Change & consumer sentiment to companies looking to market their new or improved products or services to consumers, in response to CER.

# Uses
This sentiment classification model identifies these potential customers and could be used any business or organisation committed to carbon neutrality & wanting to inform marketing strategies. This includes, but is not limited to companies in the retail, automotive, government, agriculture & food, pharmaceutical spheres. The model could also be used by sectors in government wanting to identify the various belief sentiments in order to better direct environmental awareness and education campaigns in alignment with their legislative directives and climate change response plans.

# Prerequisites
- Programming fundamentals and the basics of the Python programming language (Python 3.x), Numpy, Pandas, Matplotlib, Seaborn
- Fundamentals of Supervised Learning: Classification 
- [advertools](https://advertools.readthedocs.io/en/master/)
- [WordCloud](https://amueller.github.io/word_cloud/)
- [NLTK](https://www.nltk.org/)
- [Scikit-learn](https://scikit-learn.org/)

# Key Insights
- Several sentiment classification machine learning models were trained and tested on tweet data. The tweets were cleaned, pre-processed and the data was balanced using the SMOTE algorithm.
- Logistic Regression & SVC were the top performing model choices, with SVC producing the best f1-scores.
- Balancing and Cleaning of tweet data may not always result in better prediction performance as features are lost and the data balance may reflect the underlying distribution of tweets in real life.
- After training and model evaluation it was discovered that the Neutral tweet class did indeed have lower recall than other classes regardless of classification method, balancing or data processing. A subsequent Vader Analysis showed that the majority of neutral tweets echoed Pro or Anti Sentiment Classes. This overlap into Pro aand Anti classes affects model performance significantly.
