# machine-learning-challenge

The table below shows the models I used and the scores. The Neural Network model had the highest accuracy.

# Comparisons

|                        | Logistic<br/>Regression | KNN   | Neural<br/> Network | SVM |
|------------------------|---------------------|-------|----------------|-----|
| **Train**                  | 81.6%               | 81.8% |                |     |
| **Test**                   | 80.1%               | 79.2% | 88.3%          | 80% |
| **Test Score after**<br/>**Fine-Tuning** | 82.2%               | 80.4% | 85.6%          | 82% |
|

# Summary

If I had more time to work with the parameters, I believe the accuracy rate of the Neural Network model could be improved. If this were a "real" scenario, I would not be happy with 85.6% accuracy. I think the paramaters could be fine-tuned some more to increase the percent value, either by increasing the number of epochs (currently set to 100), or by increasing the number of nodes in a layer. Currently I have 2 layers with 100 nodes in each.

|                         | file_name                            |
|-------------------------|--------------------------------------|
| **Logistic**<br/>**Regression** | terra_vaughn_logistic_regression.sav |
| **KNN**                     | terra_vaughn_knn.sav                 |
| **Neural Network**          | terra_vaughn_neural_network.pkl*     |
| **SVM**                     | terra_vaughn_svm.sav                 |
|

**First time using 'pickle' to save a file.*