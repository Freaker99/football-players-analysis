**Correlation analysis of football players**.

For the purpose of the project, data on the statistics of football players in the 2017/18 season downloaded from the Kaggle platform was analyzed. The database was modified, and then several parameters of the analyzed players were selected. A statistically based analysis was carried out, and the normality of the parameter distributions and the correlation between them were examined. A model was then created and trained on the aforementioned database.

A model was obtained that was able to distinguish and correctly classify one of the three basic positions on the field (defender, midfielder, striker) with an accuracy of 46%. Various combinations of model parameters were tested to obtain the highest possible accuracy. A confusion matrix was performed, which shows that the model did the best job of correctly classifying defenders.

It turns out that the classifier had trouble dividing the data according to certain rules. The most related classes were "midfielder" and "striker," which the classifier had the most trouble with. In addition, a sizable number of midfielders were classified as defenders.

The studied sample relationship of position on the field with the number of fouls did not show clear analogies and correlations.

Source:\
https://www.kaggle.com/datasets/kriegsmaschine/soccer-players-values-and-their-statistics?fbclid=IwAR2JiBG5gZbEpoM3FmYfmIgI0uWuyjouXgnKjJ5e4nGfdem2hij6P1krnCU
