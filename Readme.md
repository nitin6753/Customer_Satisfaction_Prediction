# Satisfaction Prediction of Customers using Airline Services
The airline is interested in predicting whether a future customer would be satisfied with their services given previous customer feedback about their flight experience. The airline would like you to construct and evaluate a model that can accomplish this goal. Specifically, they are interested in knowing which features are most important to customer satisfaction. The data for this activity includes survey responses from 129,880 customers. It includes data points such as class, flight distance, and in-flight entertainment, among others. A decision tree was modelled to predict whether or not a customer will be satisfied with their flight experience.

* The data set is provided in [Customer_Survey.csv](Customer_Survey.csv).<br>
* Decision Tree model is built in [Build_Decision_Tree.ipynb](Build_Decision_Tree.ipynb).<br>
* Random Forest model is built in [Build_Random_Forest.ipynb](Build_Random_Forest.ipynb).<br>
* Gradient Boosting model is built in [Build_Gradient_Forest.ipynb](Build_Gradient_Forest.ipynb).<br>
* [Figures](Figures) folder contains various plots.<br>

> * Tasks Performed:
>   * Conducted extensive `EDA`, `cleaned` and `structured` the dataset for analysis.
>   * `Tuned hyperparameters` of all models through `grid search` and `cross-validation`.
>   * Developed an optimal `Decision Tree`, `Random Forest`, `Gradient Boost` Model to predict the customer satisfaction using 21 features.
>   * Evaluated the model performance on validation sets, and then selected Gradient Boosting model as the champion, achieving an F1 score of 96.05% and other metrics including an accuracy of 95.70%, recall of 95.02%, and precision of 97.10%.
>   * Identified key features influencing customer satisfaction: 'Seat comfort', 'Inflight entertainment,' and 'Customer loyalty'.

> * Recommended: Enhancements in inflight entertainment, seat comfort could boost customer satisfaction.

> * Skills Demonstrated: Data Wrangling, Tree Based ML Algorithms, Hyperparameter Tuning, Statistical Analysis, Cross-validation.
