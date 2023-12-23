<h1>Machine Learning </h1>
<p> This dataset was retrieved from the page https://ai-jobs.net/salaries/download/
This site collects salary information anonymously from professionals all over the world in the AI, ML, Data Science space and makes it publicly available for anyone to use, share and play around with.
The primary goal is to have data that can provide better guidance in regards to what's being paid globally. So newbies, experienced pros, hiring managers, recruiters and also startup founders or people wanting to make a career switch can make better informed decisions.
</p>
<p>
Given the various attributes in the dataset, we can formulate a regression problem to predict the salary_in_usd of professionals in the AI/ML/Data Science field. This problem is interesting because it allows us to understand the factors that influence salaries in this industry and can provide insights for both job seekers and employers.
</p>
<p>
Features/Attributes:
work_year (Numerical)
experience_level (Categorical: EN, MI, SE, EX)
employment_type (Categorical: PT, FT, CT, FL)
job_title (Categorical)
employee_residence (Categorical)
remote_ratio (Numerical: 0, 50, 100)
company_location (Categorical)
company_size (Categorical: S, M, L)
Target Variable:
salary_in_usd (Numerical)
This problem involves both categorical and numerical features, meeting your requirement. Also, since the dataset is from Kaggle and specific to your request, it’s unlikely that it has been used in your class before.
We used various machine learning algorithms for this regression problem, such as Linear Regression, Decision Trees, Random Forest, or Gradient Boosting.
</p>
<h1>Steps:</h1>
<div>
  <ol>
    <li>The project begins with reading the data and finding out some important details about it. We look at the number of unique values for each feature, the data size, the feature category and the data type.</li>
    <li>We apply the following steps to prepare the data for analysis. First, we remove any rows that have null or duplicate values. Second, we use Label Encoder to convert categorical data into numerical data. Third, we normalize the data to have a common scale. Finally, we split the data into train and test sets.</li>
    <li>To explore the data and the relationships between the features and the target variable, we plotted some graphs and performed some statistical tests. Then, we applied a RandomForestRegressor model to estimate the importance of each feature in predicting the outcome. We used the feature_importances_ attribute of the model to rank the features by their contribution to the prediction. </li>
    <li>We used different ML models (such as Linear Regression, Decision Tree, Random Forest, Gradient Boosting, etc.) to train and predict the data. Then we visualized the results to see how they compared. We also tried an ensemble model to optimize the predictions.</li>
    <li>We used different types of neural networks to build our model, such as feed-forward neural networks (FFNN) and recurrent neural networks (RNN). To avoid overfitting, we implemented some techniques like early stopping, model checkpointing, and feature selection. These methods help us to stop the training when the validation loss stops decreasing, save the best model parameters, and reduce the number of input features respectively.</li>
    <li>We applied feature selection and grid search techniques to enhance the performance of the gradient boosting model in this section. We aimed to achieve a higher score by optimizing the model parameters and reducing the feature space.</li>
  </ol>
</div>
