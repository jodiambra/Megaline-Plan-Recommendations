# Megaline-Plan-Recommendations

## Skills Demonstrated
    Pandas
    Random Forest Classifier
    Decision Tree Classifier
    Logistic Regression
    Classification Report
    Mean Squared Error

## Purpose
The purpose of this project is to aid Megaline, a mobile carrier, in developing a model that will analyze subscribers' behavior. Once the behavior is analyzed, subscribers on a legacy plan can be recommended one of Megaline's newer plans: Smart or Ultra. We are provided with behavior data from subscribers who have already switched to the new plans. A successful model will classify a correct new plan to a legacy plan customer. We will be working with data that we've used previously, so the data will be clean. 

## Conclusions
We successfully created a model to predict which plan a legacy customer should upgrade to. The choices were the Ultra plan, or not the Ultra plan. Our model accurately predicted the correct classes 80% of the time. Accuracy was determined to be the key metric to evaluate the model, as it considers both precision and recall. This is important because we want to ensure customer satisfaction by recommending the correct plan for their needs. The model worked best with not Ultra classifications, as it had high specificity. The precision of the model was fair, correctly predicting Ultra 73.6% of the time. The model was optimized for the number of estimators and max depth to a reasonable degree that would not make the model training extremely long. Other hyperparameters were experimented with to determine what the best model should have. Overall, the model can be improved by further increasing the range  of estimators and max depth. Also, we believe the model would work better with a more balanced dataset, so more data on customers that migrated to the Ultra plan. This could prove difficult if customers prefer to migrate to not Ultra, so this model may be close to the final product.  

https://jodiambra.github.io/Megaline-Plan-Recommendations/