## Project Description :

<p align="justify">Churn prediction uses big data to detect customers who are likely to cancel their subscriptions and is used by most of the large subscription businesses to identify customers most at-risk of churning. Done well, it leads to huge business savings, regardless of size. Churn (loss of customers to competition) is a problem for companies because it is more expensive to acquire a new customer than to keep your existing one from leaving. This problem statement is targeted at enabling churn reduction using analytics concepts. We have to predict Churn Rate on the basis of their data usage.</p>

<p align="justify">Each row represents a customer, each column contains customer’s attributes described on the column Metadata.</p>

### The data set includes information about:

- <p align="justify">Customers who left within the last month – the column is called Churn</p>
- <p align="justify">Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies</p>
- <p align="justify">Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges</p>
- <p align="justify">Demographic info about customers – gender, age range, and if they have partners and dependents</p>

### Results 

#### Data Balancing using Downsampling Method:
| Churn Class | Random Forest | Logistic Regression | AdaBoost | Linear Discriminant Analysis | GBoost | XGBoost |
|-------------|---------------|---------------------|----------|------------------------------|--------|---------|
| Precision   | 0.87          | 0.72                | 0.79     | 0.77                         | 0.88   | 0.88    |
| Recall      | 0.73          | 0.68                | 0.69     | 0.68                         | 0.81   | 0.80    |
| F1- Score   | 0.80          | 0.70                | 0.74     | 0.72                         | 0.84   | 0.84    |

#### Data Balancing using Upsampling Method:
| Churn Class | Random Forest | Logistic Regression | AdaBoost | Linear Discriminant Analysis | GBoost | XGBoost |
|-------------|---------------|---------------------|----------|------------------------------|--------|---------|
| Precision   | 0.98          | 0.76                | 0.85     | 0.79                         | 0.98   | 0.98    |
| Recall      | 0.99          | 0.75                | 0.84     | 0.75                         | 0.99   | 1.00    |
| F1- Score   | 0.98          | 0.75                | 0.85     | 0.77                         | 0.98   | 0.99    |

#### Data Balancing using SMOTE Method:
|Churn Class| Random Forest | Logistic Regression | AdaBoost | Linear Discriminant Analysis | GBoost | XGBoost |
|-----------|---------------|---------------------|----------|------------------------------|--------|---------|
| Precision | 0.95          | 0.67                | 0.80     | 0.72                         |  0.96  |  0.97   |
| Recall    | 0.92          | 0.71                | 0.77     | 0.79                         |  0.96  |  0.96   |
| F1- Score | 0.93          | 0.69                | 0.78     | 0.75                         |  0.96  |  0.97   |
