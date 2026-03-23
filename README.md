# 24ADI003_24BAD020_EXP-06
SCENARIO-01
DESCRIPTION OF THE CODE:
This code builds a diabetes prediction model using Decision Tree and Bagging techniques. The dataset is loaded and split into training and testing sets. A Decision Tree model is trained and its accuracy is calculated. Then, a Bagging model (using multiple Decision Trees) is trained to improve performance, and its accuracy is also computed.
The results of both models are compared using a bar graph, and a confusion matrix is displayed for the Bagging model to evaluate prediction performance.
Conclusion: Bagging usually gives better accuracy than a single Decision Tree.

SCENARIO-02
DESCRIPTION OF THE CODE:
This code builds a customer churn prediction model using AdaBoost and Gradient Boosting algorithms.
The dataset is loaded and categorical values are converted into numerical form using Label Encoding. Relevant features like Tenure, Monthly Charges, Contract Type, and Internet Service are selected, and the data is split into training and testing sets.Both models (AdaBoost and Gradient Boosting) are trained on the training data. Their performance is evaluated using ROC-AUC score, which measures how well the model distinguishes between churn and non-churn customers.A ROC curve is plotted to compare both models visually. Finally, feature importance graphs are displayed to show which features influence the prediction the most.
Conclusion: The model with higher AUC performs better in predicting customer churn.

SCENARIO-03
DESCRIPTION OF THE CODE:
This code builds an income prediction model using the Random Forest algorithm.
The dataset is loaded, and the target variable (Income) is converted into numeric form using Label Encoding. Features such as Age, Education Years, Hours Per Week, and Experience are selected, and the data is split into training and testing sets.A Random Forest model is trained and its accuracy is calculated. Then, the model is improved by testing different numbers of trees (n_estimators) to find how it affects performance. The results are shown using a line graph.Finally, a feature importance graph is plotted to identify which features contribute most to income prediction.Conclusion: Increasing the number of trees can improve accuracy, and feature importance helps understand key influencing factors.

SCENARIO-04
DESCRIPTION OF THE CODE:
This code builds a heart disease prediction model using multiple machine learning algorithms and compares their performance.The dataset is loaded, and features like Age, Cholesterol, Max Heart Rate, and Resting Blood Pressure are selected. The data is split into training and testing sets.Three models—Logistic Regression, SVM, and Decision Tree—are trained individually, and their accuracies are calculated.Then, a Stacking model is created by combining these three models, with Logistic Regression as the final estimator, to improve prediction performance.Finally, the accuracies of all models are compared using a bar graph.Conclusion: The stacking model often provides better accuracy by combining multiple models.

SCENARIO-05
DESCRIPTION OF THE CODE:
This code builds a heart disease prediction model using multiple machine learning algorithms and compares their performance.The dataset is loaded, and features like Age, Cholesterol, Max Heart Rate, and Resting Blood Pressure are selected. The data is split into training and testing sets.Three models—Logistic Regression, SVM, and Decision Tree—are trained individually, and their accuracies are calculated.Then, a Stacking model is created by combining these three models, with Logistic Regression as the final estimator, to improve prediction performance.Finally, the accuracies of all models are compared using a bar graph.Conclusion: The stacking model often provides better accuracy by combining multiple models.

