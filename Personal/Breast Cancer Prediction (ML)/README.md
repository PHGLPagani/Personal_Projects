# Breast Cancer Prediction

For ease of access, the file has been uploaded into a Google Colab notebook that can be found here:

https://colab.research.google.com/drive/1m3hHUQhAtKfaBFoADEqmS0fZuHcm1FIl?usp=sharing

This project uses data from a public dataset uploaded to Kaggle, that can be found here:

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

*The API connection's username and key were removed for privacy reasons. You can get a username and key by creating your Kaggle account.*

It uses Logistic Regression to train a model on about 30 parameters to predict breast cancer.

The final output of the code uses Seaborn to plot a heat map of a confusion matrix

#[TruePositive,FalsePositive]-->[TP,FP]-->[GOOD,Type1Error]

#[FalseNegative,TrueNegative]-->[FN,TN]-->[Type2Error,GOOD]

This is what it may look like:

![Confusion Matrix](https://user-images.githubusercontent.com/35358634/222785742-1c25cd24-d695-44eb-85f5-0a406e0c685c.png)

In this instance, the model was able to correctly predict breast cancer in the testing data with 96.49% accuracy
