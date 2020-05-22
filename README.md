# Fake-News-Detection

This project of detecting fake news deals with fake and real news. 
Using sklearn, we build a TfidfVectorizer on our dataset.

Then, we initialize a PassiveAggressive Classifier and fit the model. 
In the end, the accuracy score and the confusion matrix tell us how well our model fares.

The dataset used has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE.

## Analysis

### Confusion Matrix

![alt text](https://github.com/sandeepan1999/Fake-News-Detection/blob/master/cm.png)

[588,  50],

[ 44, 585]


### Report

              precision    recall  f1-score   support

        FAKE       0.93      0.92      0.93       638
        REAL       0.92      0.93      0.93       629
