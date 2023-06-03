**Football players analysis**

For the purposes of the project, data on the statistics of football players in the 2017/18 season collected from the Kaggle platform was analyzed. An analysis of the modified database was carried out, and then several parameters of the analyzed players were selected. The analysis was carried out, the normality of the parameter distributions and the correlation between them were examined. Then a model was created, which was trained on the said base.

A model was obtained that was able to distinguish and properly classify one of the three basic positions on the field (defender, midfielder, striker) with an accuracy of 46%. Various combinations of the model's parameters were tested to obtain the highest possible accuracy. A confusion matrix was performed, which shows that the model did the best job of properly classifying defenders.

It turns out that the classifier had trouble dividing the data according to certain rules. The most closely related classes were "midfielder" and "striker," with which the classifier had the biggest problem. In addition, a sizable number of midfielders were classified as defenders.

The examined sample relationship of position on the field to the number of fouls did not show clear analogies and relationships.
