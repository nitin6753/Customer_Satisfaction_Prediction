# Satisfaction Prediction of Customers using Airline Services
The airline is interested in predicting whether a future customer would be satisfied with their services given previous customer feedback about their flight experience. The airline would like you to construct and evaluate a model that can accomplish this goal. Specifically, they are interested in knowing which features are most important to customer satisfaction. The data for this activity includes survey responses from 129,880 customers. It includes data points such as class, flight distance, and in-flight entertainment, among others. A decision tree was modelled to predict whether or not a customer will be satisfied with their flight experience.

The data set is provided in [Customer_Survey.csv](Customer_Survey.csv).<br>

Decision Tree model is built in [Build_decision_tree.ipynb](Build_decision_tree.ipynb).<br>
[Images](Images) folder contains various plots like [confusion Matrix]('Images/Confusion Metrics.png'), Decision Tree Plot, Feature Importances, and Evaluation Metrics
> * Tasks Performed:
>   * Conducted extensive EDA, cleaned and structured the dataset for analysis.
>   * Tuned model hyperparameters such as max_depth and min_samples_leaf through grid search and cross-validation.
>   * Developed a Decision Tree Model to predict the customer satisfaction using 21 features.
>   * Evaluated model performance, achieving an average F1 score of 94.5% and other metrics including an accuracy of 94.0%, recall of 93.5%, and precision of 95.5%.
>   * Identified key features influencing customer satisfaction: 'Inflight entertainment,' 'Seat comfort,' and 'Ease of Online booking'.

> * Key Result Areas:
>   * Highlighted the critical impact of 'Inflight entertainment,' 'Seat comfort,' and 'Ease of Online booking' on customer satisfaction.
>   * Demonstrated the efficacy of decision trees in predicting customer satisfaction metrics accurately.

> * Recommended: Enhancements in inflight entertainment, seat comfort, and online booking could boost customer satisfaction.

> * Skills Demonstrated: Data Wrangling, Decision Tree Algorithms, Hyperparameter Tuning, Statistical Analysis, Cross-validation.
