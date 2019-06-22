# predict-daily-range-direction-ML
predict (increase_decrease) daily range in the German Dax using ML classifiers
The script takes historical daily data from Yahoo, build, in this case (the German DAX), 5 lag of features to predict if next day range will be above/below today's range (H-L), it splits the data to train/test, check different classifiers (with their default hyperparameters)  and then produce the results in a new dataframe with highlights + plotting the ROC curve (TPR vs FPR).

Example:
![gdaxi_roc](https://user-images.githubusercontent.com/46570219/59966855-aae7e500-952a-11e9-863c-cba155ebb901.jpg)
