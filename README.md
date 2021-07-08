# Machine Learning in Emotion Consulting Service

> Shall we meet up? - sent 3 days ago 

The message was sent three days ago to the potential date that you have chatted for some days from the dating apps. Guess you have been "ghosted" (Oh.. the pain..). This is a common occurrence that happen in the dating scene these days. While the technology and the internet, has increase more opportunities than ever, a lot of people still suffer from the difficulties to find a match for date. For most of people, it is a let down, but for us, this smells like an opportunity.

**Objectives** This project is to address the painpoints of our customer in finding dates. It is packaged as an Emotion Consulting Service that provide different products for their customer. 

**Data**: utilizing the Speed Dating dataset https://www.kaggle.com/annavictoria/speed-dating-experiment

### Features

![Business Model.jpg](/BusinessModel.jpg)

#### 1. Feature #1: Likability Estimator

to address the pain point of "Difficulties in knowing their position in courtship market". We use different machine learning regression models that able to translate from the 6 qualities of a person into the percentage of likability of the person. 

&emsp;**Models:** Logistic Regression, Decision Tree, Random Forrest, XGBoost

&emsp;**Tools:** GridSearch, K-Fold, SHAP

#### 2. Feature #2: Interest to Attributes

Lasso regression is used to predict the 6 qualities of the person, from the hobbies that they have. This feature aim to address the pain point of "Difficulties in improving their popularity"

&emsp;**Models:** Lasso Regression

#### 3. Feature #3: Group Lounge

From the hobbies that each participant have, unsupervised machine learning K-means are implemented to group our clients based on the similarities that they have with their partner to address the pain points of "Lack of social circle to find potential partner"

&emsp;**Models:** K-Means Clustering

#### 4. Marketing Strategy

Last but not least, Marketing strategy is developped based on machine learning to increase personalize the package to different groups through the means of Unsupervised Clustering method. 

&emsp;**Models:** K-Means Clustering

This project is from Master of Science in Business Analytics
