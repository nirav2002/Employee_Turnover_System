Employee turnover is an expression that is used broadly in the business organazations around the world. Despite the face that there have been numerious studies which have been performed on this topic, there has not been any significant steps taken to examine the causes and leading factors of employee turnover in a particular organization.

In our project, huge chunks of data will be gathered among various diverse groups, and the programming language such as Python and its libraries including Pandas, Matplotlib, seaborn will help us analyze the causes of Employee Turnover in an organization, thus giving us more clarity and ultimately recommending ways to prevent the turnover in major orgainzations.

The first step is to understand our dataset, and then we can proceed with Pre-Processing which takes up to 80% of the whole project duration!
We can drop the Employee count table in this step, as the Employee count is the same for all the departments int he dataset.

Now, we have inserted a new column attition_dummies into the dataset. Its value is 1 if Attrition is Yes, its value is 0 if Attrition is No.

Now, we take the departments which have the maximum mean attrition values. Here, we have selected the top 3 departments, and we have represented it in the form of a pie-chart. This helps us find out that the Sales Department is the one with the most Attrition.

Taking the education field, we can group the fields according to descending order of the mean Attrition values. This is then represented in the form of pie chart, which helps us understand that the most Attrition education field is Human Resources.

Now, we split the dataset into testing and training data. We can apply various Machine Learning Models to our dataset, and can get to know its accuracy.

For our dataset, XGBoost will show the maximum accuracy of all the models.
