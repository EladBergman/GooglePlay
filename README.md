# GooglePlay Apps Analysis

## The Applications' Market for Android OS is fast growing in the past few years.
In this project, we are working for a development team that wants to create a popluar app which will capture a niche in the Android market.
We will explore the features of the applications in "Google Play" store and create a model that predicts the number of installs for each app.

## Our project includes the following steps:
1. Uploading the dataset and examing its rows and columns.
2. Cleaning and processing the data in our dataset- including the sub pahses below:
  A. we removed non-english apps ,null values and redundant chars.
  B. We processed some columns to present their values as one-scale-unit.
  C. we chose columns for analysis and converted their types to numeric or categorial. 
3. Analysis of the relevant data & dealing with ourliers.
4. Creating liniar regression and Random forest models to predict the number of installs for each app.

## Summary Of Results:
A. Although 90% of apps are free of charge, users tend to pay for apps from genres Tools, Entertainment and Education.
B. 50% of apps were installed each more than 1M times. We suggest our development team to aim for installing their app 1M or more times in order to define the success of app.
C. The most popular genres are: Communication, Productivity, Social, Tools and Arcade.
D. Strategy games are the most reviewed among all genres.
E. On average, around 6% of users who download an app write reviews in the Google Play Store.
F. Liniar regression algorithm with certain genres as features has the best performance while predicting the apps' installs among the examined alternatives.

## Real-world usage of this project
Development teams can use our findings to think about what kind of app they want to develop.
When having in mind an idea, we can discuss with them about further analysis they need to proceed.

Below some suggestions for future projects:
1. Building clusters for potential users may install our app based on presonal features.
2. Investigating the reaction of users to apps using two alternatives:
  A. Suggesting them features as part of in-app purchases in free apps.
  B. Suggesting them improved features as part of in-advance payment before app installing.
3. Exploring for key words in review contents to understand the experience of users.
