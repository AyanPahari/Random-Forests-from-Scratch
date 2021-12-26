
# Random Forests from Scratch

We are going to implement our own random forests classifier from scratch and apply 
to the Spam dataset(https://hastie.su.domains/ElemStatLearn/datasets/spam.data)

We will analyze it's performance on the following:

    (a) Explore the sensitivity of Random Forests to the parameter m (the number of features
    used for best split).

    (b) Plot the OOB (out-of-bag) error and the test error against a suitably chosen range of values for m.
## Spam Dataset

Data : https://hastie.su.domains/ElemStatLearn/datasets/spam.data

Information : https://hastie.su.domains/ElemStatLearn/datasets/spam.info.txt
## Analysis

Checking the Test Accuracy and Time Taken(secs) of our Random Forests Implementation

    Test Accuracy : 94.56% 
    Time Taken : 379.75 secs

Checking Test Accuracy using Sklearn's RandomForestClassifier

    Test Accuracy : 95.14%
    Time Taken : 1.0 secs

- So, based on test accuracy our model performs almost as good as the sklearn’s model but the main differnce is the time taken by both the models. Sklearn’s model is approx 380X faster than our model.

Plots of OOB vs m can be found in the Report.

### Note: 

Here due to Computation Infeasibility we are limiting the number of trees and depth to 10 (on full depth and 100 trees it takes hours to plot the behaviour) but that doesn't affect the sensitivity of Random Forests but accuracy of the model does get affected.

## Authors

- [@AyanPahari](https://github.com/AyanPahari)

