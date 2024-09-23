# neural-network-challenge-1
Module 18 Challenge Assignment

### This Challenge project is designed to develop a neural network model to determine whether to approve or disapprove of a loan application to refinance student debt, predicting likelihood of loan repayment, using a database of previous loan recipients:

### The challenge employs the following tools for the purpose of generating the data for evaluation:
* Pandas for utilizing Pandas notebooks
* Tensorflow for preprocessing, training, and optimizing the data
* Keras to be used with Tensorflow to build a neural network model with optimal layers, activation functions, and loss functions.
* Train_Test_Split and Classification Report from Sklearn to create training and test data sets to evaluate the accuracy of the model.
* StandardScaler() from Sklearn is used to scale the training data to ultimately transform the testing data set to a more uniform scale to apply the model attributes.

### In the classification report, the accuracy of the model is indicating that the accuracy of making the correct choice whether to approve or disappove the loan, is near 75% in all classification fields, i.e. precision, recall, f1-score, etc.

### My answers in the discussion session include the below thoughts and documentation...

**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

Relevant data for building a student loan recommendation system would likely require the following...
- The chosen major course of study can indicate career stability and earning potential based upon needed skillsets in the workforce.  This could also be compared with the loan history of others with the same major.
- GPA would be a good indicator of a Student's ambition, commitment and accountability, comparable to others with loan approval history.
- STEM score, as noted in the original data frame above, is further evidence of a student's likelihood to provide stability of future contributions to the workforce, supporting the likelihood of earning potential and future ability to make payments.
- W-2 earnings would be an demonstration that a student has been employable, and can maintain a job in the future. 
- History of payment defaults or payment amounts would be an indication of likelihood to pay.
- Credit score could also be used, but may be misleading due to inability of a young applicant to have established a credit history.


**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

Based on the inputs that I would intend to collect, I recommend a content-based filtering system.  The content would essentially make up the details of a profile for each applicant.  And, based on the profile data, the evaluation of users that have shared similar profiles would provide a basis for determining evidence of likelihood to pay.  The model would prediction whether the student should be approved for a loan or not.




**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**
1. History of making payments is typically among the best data points to consider when recommending a loan.  Unfortunately, most applicants won't have any history of paying off debt or loans.
2. Credit score, typically a reliable source of data in support of paying future loans, may be misleading due to inability of a young applicant to have established a credit history.

Both of the above challenges are of concern because, without much history of evidence regarding ability to pay or earn cash, other (available) factors are less direct or reliable in assessing future cash availability to pay the loans.


### Note that I completed all work in this challenge without requiring outside assistance...
