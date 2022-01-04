# NLP-Stock-Sentiment-Analysis
Kaggle-Stock-Sentiment-Analysis-Problem 
Where with the headline we need to Predict weather the stock is going up or down.
We are adding new Column Label where 0 = Decrease in stock, 1 = increase in stock Prediction.
Here we are taking the raw data of past 16 years of data from 2001 to 2016. But we can Automate this ML process and change the Weekly bases
Here, we are checking NLP concepts and then using the RandomForest Classifier for checking the Accuracy Precision nad Recall.
Below is Result what we got 
[[140  46]
 [ 14 178]]
0.8412698412698413
              precision    recall  f1-score   support

           0       0.91      0.75      0.82       186
           1       0.79      0.93      0.86       192

    accuracy                           0.84       378
   macro avg       0.85      0.84      0.84       378
weighted avg       0.85      0.84      0.84       378
So Accuracy is 84%, so we can schedule this machine learning program with Batch Scheduler AIRflow ( schedule and monitor workflows) 
