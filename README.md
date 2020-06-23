# IPL-Seasonal-Predictions
Using feature engineered IPL data to predict of the IPL on a seasonal basis.
The data I obtained included the results of every match in the IPL from 2008-2019. Tthe data also included every delivery in each of those matches. 
The features I wanted to obtain were guided by, https://arxiv.org/ftp/arxiv/papers/1511/1511.05837.pdf, and these were Net Run Rate and Win Percentage.
The final preprocessing was used to scale the data using MinMaxScaler.
The algorithms I used were, RandomForrestClassifer, LogisticRegression, DecisionTreeClassifier and XGBClassifer.
