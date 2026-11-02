# Wine Quality Prediction

I compared a random forest, SGD and SVC for predicting quality scores across 1,143 wines. Random forest did best at 68% accuracy, ahead of SGD at 53% and SVC at 49%.

That headline hides a weakness: the macro F1 score was only 0.41, because the model struggled with rarer quality scores. I'd look at handling that class imbalance next. The dataset isn't in this repo.
