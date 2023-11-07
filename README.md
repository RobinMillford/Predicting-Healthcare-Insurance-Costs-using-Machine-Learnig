# Predicting-Healthcare-Insurance-Costs-using-Machine-Learnig

In this project, I embarked on a journey to estimate healthcare insurance expenses through machine learning, addressing the escalating costs of health insurance. My goal was to leverage data-driven solutions to gain insights into the complex web of health insurance expenses. I explored various machine learning algorithms, including Random Forest, Decision Tree, XGBoost, and LightGBM, to predict medical costs based on factors such as age, sex, BMI, number of children, smoking habits, and region.

I began my exploration by preprocessing the data, checking for duplicates, encoding categorical features, and splitting the dataset into training and testing sets. Afterward, I implemented and evaluated the performance of several machine learning models. The models I experimented with include:

1. **Random Forest Regression:** I utilized the Random Forest algorithm with 50 decision trees to predict healthcare expenses. The model demonstrated its effectiveness in capturing complex relationships within the data.

2. **Decision Tree Regression:** A Decision Tree model was constructed to predict charges. This simple yet interpretable model served as a benchmark for evaluating more complex models.

3. **XGBoost (Extreme Gradient Boosting):** I employed the powerful XGBoost algorithm, which is known for its accuracy and efficiency. This model was capable of handling the complexities of the data, offering competitive performance.

4. **LightGBM:** LightGBM, another gradient boosting framework, was applied to the task. Its speed and ability to handle large datasets made it a valuable addition to my modeling toolkit.

Each model was fitted, tested, and evaluated for its performance using metrics such as Mean Squared Error (MSE) and R-squared (R2) scores. The results indicated that these machine learning models could provide accurate estimates of healthcare insurance expenses.

To visually assess the performance of each model, I created comparison plots that allowed me to observe how the models' predictions aligned with the actual values. I generated bar plots to compare actual and predicted charges for the first ten instances, providing a straightforward visualization of each model's accuracy.

In summary, this project demonstrated the effectiveness of machine learning in estimating healthcare insurance expenses. By exploring various algorithms and evaluating their performance, I gained valuable insights into the factors influencing medical costs. The application of Random Forest, Decision Tree, XGBoost, and LightGBM models showcased the potential of data-driven solutions in the healthcare domain, ultimately contributing to more informed decision-making and a better understanding of insurance expenses.
