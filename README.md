# EPL-prediction

Attempting to predict the outcome of the ongoing English Premier League (EPL) season, match statistics from the previous season were gathered using data from http://www.football-data.co.uk/. The fixture list for the current season was obtained from https://fixturedownload.com/. The selected statistics for the model included Full-Time Home Goals (FTHG) and Full-Time Away Goals (FTAG).

Data wrangling involved calculating metrics like Home Average Scored (HAS), Home Average Conceded (HAC), Away Average Scored (AAS), and Away Average Conceded (AAC) for each team based on their performance from the last season. The data was scaled to a range of [0,1] for easier computation.

For predictions, five models were utilized: Logistic Regression, Random Forest Classifier, Multinomial Naive Bayes, XGB Classifier (from the XGBoost library), and Super Vector Machine. The accuracies achieved with each model were as follows:

Logistic Regression: 0.6579
Random Forest Classifier: 0.6053
Multinomial Naive Bayes: 0.6184
XGB Classifier: 0.6316
Super Vector Machine: 0.6447
Possible improvements to enhance the model's performance include incorporating additional match stats like passes completed, corners taken, and fouls committed. Moreover, integrating betting odds and player ratings could also provide valuable insights.

In conclusion, predicting football games, especially an entire season, remains a challenging task due to numerous variables and factors influencing the outcomes. The attempt at prediction is commendable, but it's essential to acknowledge the complexity of the sport and its unpredictability.
