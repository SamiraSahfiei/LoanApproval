# Classifying Credible Loan Applicants

In this project I focused on analyzing loan approval data and figuring out which model to use in order to correctly classify people who are or are not likely to be approved for a loan. 
I also wanted to know what is the most important factor that influences applicant credibility.

I used a dataset from Kaggle called “Loan Eligible Dataset”. It has twelve attributes and a loan approval class variable that is binary with values of Y and N. Deciding to capture the model result without preprocessing, I ran Naive Bayes, Decision Tree, Random Forest and Logistic to later compare the accuracy results and effectiveness of preprocessing. While the dataset was relatively clean, I still had to do some preprocessing before running all the models for optimal results. Preprocessing steps included replacing null values with mean/mode, encoding and normalizing data as well as removing outliers.
