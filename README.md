# Nurse Attrition Prediction Team Final Project for Advanced Analytics Programming Course
Nurse attrition has risen dramatically with the on-set of COVID-19 and the U.S. is expected to have a shortage of nurses in the coming years. The nurse attrition dataset is from Kaggle and it has enough variety to identify specific reasons nurses may leave a healthcare facility. Our work will benefit hospitals focused on retaining talent, nurses looking for greater fulfillment, and board of directors acting in the hospital's best interest. We aim to determine features with the greatest predictive power to help healthcare facilities retain nurses, thereby minimizing re-hiring costs while improving brand reputation. The 2022 National HealthCare Retention & RN Staffing Report argues the cost of nurse attrition is roughly $50,000 per nurse which contributes to significant losses for healthcare organizations. The broader healthcare industry will appreciate our analysis and interpretation, as it could pinpoint factors furthering nurse attrition and improve retention rates. 

# Conclusion and Future Direction
The baseline accuracy when predicting all nurses will not leave the hospital is approximately 87%, suggesting we want our model to have higher accuracy to provide predictive value. We tested the K-nearest neighbors, Logistic Regression, Decision Tree, Random Forest, and XGBoost classifiers. The Logistic Regression, Decision Tree, Random Forest, and XGBoost classifiers had testing accuracies above 90%, meaning they were able to identify patterns as to why nurses may leave their place of work. Logistic Regression is our optimal model with a training accuracy of ~96% and test accuracy of ~94%. For the positive class, the precision is low at 76% conveying the percent of nurses who were predicted to turnover out of those who actually left their place of work. Similarly, the recall score is also low at 73% reflecting the percent of nurses who actually left their place of work out of those predicted to turnover. 

According to the feature importances from the Logistic Regression model, whether nurses received an education in the medical or life sciences field, work overtime, and are heavily involved in their job are strong predictors of nurse attrition. Perhaps nurses with a background in medicine are more familiar with other career opportunities and growth potential, so they may decide to pursue a different career path. Additionally, nurses who work long hours and night shifts may feel burnout, contributing to higher attrition rates. The least valuable features were training time, marital status of single, monthly rate, and gender, likely since single female nurses have committed a significant amount of time to nursing and do not wish to learn skills for another occupation or have time to pursue a different career path. Our team was surprised that Logistic Regression is our optimal model; however, this is likely because there is limited data and the outcome variable was highly imbalanced. In the future, we aim to analyze aggregate data from various hospitals to assess the validity of our results and identify more nurse attrition patterns. To improve our results, we would experiment with more class imbalance techniques, derive features from existing ones, and interview nurses to better understand factors contributing to higher attrition rates. <br>

Team: Nidhish Nerur, Michael Crosson, Yue Taira, Megha Sengupta, Erin Kim
