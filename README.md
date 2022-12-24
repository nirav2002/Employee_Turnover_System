# Employee_Turnover_System
"Employee turnover" is broadly used everywhere in the various business organizations around the world. Hence, we have developed a system which will examine the causes and leading factors of turnover in a particular organization.

The main purpose of this study is to determine the reasons and key factors in the perspectives of the relevant literature and identify the intention of employee turnover.
Huge chunks of data will be gathered among various diverse groups, and Python and its libraries such as Pandas, Matplotlib and seaborn will help us analyze the causes of Employee Turnover in an organization and thus, giving us more clarity and ultimately recommending ways to prevent the turnover in major organizations.

We have taken the dataset from kaggle, whose link is also present in the Repository.

The first step we have performed is Data Pre-Processing. It's said that data scientists spend 80% of the time in Data Pre-Processing! It is one of the most crucial steps which will determine the accuracy of various Machine Learning Models.

Note that we have dropped the Employee count column from the dataset as the value is the same for different departments throughtout the dataset. The attrition column is added into the dataset, which contains the dummy values.

Visualisation tools such as Piechart comes in handy when we want to plot the attrition rates for the three most attitious departments. We find out that the Sales Department is the most attritious one.

Similarly, find out about the most attition education field as well.

Start the model building phase, split the dataset into training and testing data.

Apply different Machine Learning Algorithms on the dataset to check the accuracy of the model. We found that the maximum accuracy is acheived in the XGBoost model.
