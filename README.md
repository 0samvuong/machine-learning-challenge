# machine-learning-challenge

sam vuong week 21 homework

# findings

## RANDOM FOREST

- random forest test score: 0.7116704805491991

- Training Data Score: 0.46976921609765404

- Testing Data Score: 0.45652173913043476


Parameter tuning = {'min_samples_leaf': 2, 'n_estimators': 200}

Best parameter score: 0.7127615176940598

- The random forest test scores performed much better than the scaled training and testing scores. This probably suggests that scaling is unessecary.
- the best score after fine tuning the min_samples_leaf and n_estimators parameters was only equal to the forest test score


## SVM 
- SVM Test Score: 0.489

- Training Data Score: 0.5052450886896814

- Testing Data Score: 0.4891304347826087


Parameter tuning = {'C': 1, 'gamma': 0.001}
Best parameter score: 0.5809664238569631

- SVM score performed around the same as the scaled training and testing scores, perhaps implying SVM is not a good model to use for this task
- fine tuning the C and gamma parameters did improve the SVM test score, but not by much. 



# overall findings

neither random forest or SVM models proved to be effective measures in predicting new planets. Perhaps trying another type of model would work, or selecting different columns (less columns) would prove effective

