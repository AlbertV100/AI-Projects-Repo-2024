**Synopsis: Loan Default prediction using TensorFlow and Keras**

1.  The dataset contains 9578 entries with 14 columns, including
    features like credit policy, purpose, interest rate, instalment,
    annual income, debt-to-income ratio, FICO score, etc.

2.  There are no missing values in the dataset.

3.  The target variable \"not.fully.paid\" is imbalanced, with 83.99% of
    loans being fully paid and 16.00% not fully paid.

4.  To handle the imbalanced dataset, the minority class (not fully
    paid) was up sampled to match the number of instances in the
    majority class.

5.  Feature transformation was performed, including label encoding of
    categorical variables.

6.  Correlation analysis revealed significant correlations between the
    target variable and interest rate, FICO score, credit policy, and
    inquiries in the last 6 months.

7.  A neural network model with three hidden layers was designed,
    comprising 256 neurons each, with dropout regularization to prevent
    overfitting.

8.  The model was trained using the Adam optimizer and binary
    cross-entropy loss function.

9.  Early stopping was implemented to prevent overfitting, resulting in
    a trained model with a validation binary accuracy of around 76.79%.
