# Learning Journey 

Took a long break after doing ML specialization on Coursera so, I'll be revising the ML concepts daily through CampusX 100 days of ML and I'll use other resourses too while building projects.



## 📌 Machine Learning & AI Learning Resources  

| Topic                                       | Resources/Links                                       
|---------------------------------------------|------------------------------------------------------|
| CampusX (100 Days of Machine Learning)      | [100 Days of ML](https://campusx.in/) |
| Pytorch           | [Pytorch](https://www.youtube.com/watch?v=Z_ikDlimN6A) |



### Day 1


Revised tensors, axes, and ranks from 1D to 5D.

✅ Key Points:
Tensor: Multi-dimensional array.

Rank: Number of dimensions (axes).

📊 Examples:
0D: Scalar → x = 5

1D: Vector → [1, 2, 3]

2D: Matrix → [[1, 2], [3, 4]]

3D: shape = (2, 3, 4)

4D: Image batch → (10, 3, 64, 64)

5D: Video batch → (16, 10, 3, 64, 64)


### Day 2

Today did a project based on Logistic regression where I understood the overall ML process from beginning to the end. I used 100 datas (CSV) to take IQ and CGPA as a input from the sutdents and predict the Placement at a company. 


### Day 3


Today, I learned how to frame a Machine Learning (ML) problem effectively.
The key steps I focused on were:

Understanding the Problem: Before thinking about models or data, it's important to clearly define the goal. For example, if the objective is to lower the churn rate, I first need to deeply understand what churn means in the specific context.

Identifying the Problem Type: Once the goal is clear, I work on framing it as an ML task — for instance, predicting whether a customer will churn (a classification problem).

Thinking About Solutions: After identifying the problem, I brainstorm different ways ML could help solve it, such as building a model to predict churn early so interventions can be made.

Overall, the big idea is:
Understand first, model later.


### Day 4

Used pandas to work with CSV files.

Learned to read CSVs from local files and URLs using pd.read_csv().

Explored data with head(), tail(), shape, info(), and describe().

Handled missing values using isnull(), dropna(), and fillna().

Saved DataFrames to CSV using to_csv().


### Day 5

Learned how to work with Json Files and tried few example datasets form kaggle.

Learned how to work with SQL data and tried it one example dataset from kaggle.

Mostly learned about reaading the data in Pandas.

Learned about torch.tensors from documentation.


### Day 6

Today I learned how to Fetch data using an API and convert into a CSV format.

I used API from a TMDP (movie website) and used most popular movies, then I used the API to gather all the data into CSV form.


### Day 7

I started learning Pytorch so today I learned about tensor creation and learned about tensor datatypes.

![image](https://github.com/user-attachments/assets/faa9ac65-ef94-4418-bfe0-355f78f17bb0)


### Day 8

Today I learned about Univariate EDA and did some EDA on titanic datasets, on the other hand I learned more about dtype in pytorch.


### Day 9

Today I completed multivariate analysis from CompusX videos and simultaneously also leanred some more tensor manipulation and matrix multiplication in Pytorch.


### Day 10

Today I learned how to use one of the most useful tool for data analysis 'pandas profiling'. I used titanic dataset and heart disease dataset. It shows the report of the whole dataset and performs univariate and multivariate analysis. I also learned about feature engineering (Just started introduction). 

On the other hand, I learned some basic opration like mean, median, max and min in Pytorch.


### Day 11 


Today I learned about standardization in Feature scaling and saw how it maked difference in the accuracy. Mostly it is used in algorithms where we need to calculate the Euclidean distances like K-means, K_nearest means etc. 

![image](https://github.com/user-attachments/assets/b7270a85-4642-4734-99bb-9cb3b6f45458)


I used a dataset with columns salary, age and purchased (Y) and observed the graph after the standardization and found main difference that the graph is not changed but the range of values will be significantly reduced (Mean becomes 0 and Standard Deviation becomes 1).
