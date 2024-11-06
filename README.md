# Academic Assignments and Projects Repository

This repository contains assignments and mini-projects for the subjects **Design and Analysis of Algorithms**, **Machine Learning**, and **Blockchain Technology**. Each section includes mandatory assignments and one mini-project. Below are the details for each subject, including assignment descriptions and dataset links for machine learning projects.

---

## Group A: Design and Analysis of Algorithms

This group focuses on classic algorithm design techniques, including dynamic programming, greedy methods, and backtracking.

### Assignments

1. **Fibonacci Sequence and Step Count**  
   - Program to calculate Fibonacci numbers and compute the step count for analysis.

2. **Job Sequencing with Deadlines (Greedy Method)**  
   - Implement the job sequencing algorithm using the greedy approach to maximize profit.

3. **Fractional Knapsack Problem (Greedy Method)**  
   - Solve the fractional knapsack problem using a greedy algorithm to maximize value.

4. **0-1 Knapsack Problem (Dynamic Programming or Branch and Bound)**  
   - Solve the 0-1 knapsack problem using either dynamic programming or the branch-and-bound strategy.

5. **Binomial Coefficients (Dynamic Programming)**  
   - Generate binomial coefficients using dynamic programming to analyze their behavior.

6. **8-Queens Problem (Backtracking)**  
   - Design an 8-Queens matrix with the first Queen placed, using backtracking to position the remaining queens.

### Mini Project

- **Matrix Multiplication**  
   - Implement standard matrix multiplication and multithreaded matrix multiplication (using one thread per row or cell) and compare their performance.
   - **OR**: Implement merge sort and multithreaded merge sort to compare performance.
   - **OR**: Implement Naive and Rabin-Karp algorithms for string matching and observe their differences.

---

## Group B: Machine Learning

This group covers machine learning algorithms and projects for prediction, classification, and clustering. 

### Assignments

1. **Uber Ride Fare Prediction**  
   - Predict the price of an Uber ride based on pickup and drop-off locations.
   - Tasks include pre-processing, outlier detection, correlation check, implementing Linear Regression and Random Forest Regression, and evaluating models.
   - [Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)

2. **Email Spam Detection**  
   - Classify emails as spam or not using K-Nearest Neighbors and Support Vector Machine algorithms and analyze their performance.
   - [Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)

3. **Bank Customer Churn Prediction**  
   - Build a neural network classifier to predict customer churn using a structured dataset.
   - Tasks include data pre-processing, model building, and performance evaluation.
   - [Dataset](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

4. **Gradient Descent Algorithm**  
   - Implement the Gradient Descent algorithm to find the local minima of the function \( y = (x+3)^2 \) starting from \( x = 2 \).

5. **Diabetes Prediction using KNN**  
   - Implement the K-Nearest Neighbors algorithm on the diabetes dataset, calculating metrics such as confusion matrix, accuracy, error rate, precision, and recall.
   - [Dataset](https://www.kaggle.com/datasets/abdallamahgoub/diabetes)

6. **K-Means Clustering**  
   - Implement K-Means or hierarchical clustering on the sales dataset and determine the optimal number of clusters using the elbow method.
   - [Dataset](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

### Mini Project

- **Stock Market Prediction**  
   - Analyze and predict stock price trends based on Indian market data from 2000 to 2020.
   - **OR**: Predict Titanic survival based on passenger data.
   - [Stock Data Dataset](https://www.kaggle.com/datasets/sagara9595/stock-data)
   - [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## Group C: Blockchain Technology

This group explores blockchain technology fundamentals, smart contracts, and decentralized applications.

### Assignments

1. **Metamask Installation**  
   - Install Metamask and study Ether spending per transaction.

2. **Creating a Wallet with Metamask**  
   - Create a personal wallet using Metamask for crypto transactions.

3. **Smart Contract for Bank Account**  
   - Write a smart contract on a test network for a customer’s bank account operations (Deposit, Withdraw, Show Balance).

4. **Smart Contract for Student Data**  
   - Write a Solidity program to create and manage student data using structures, arrays, and a fallback function. Deploy as a smart contract on Ethereum and observe transaction fees and gas values.

5. **Blockchain Types Survey Report**  
   - Write a report on various blockchain types and their real-time applications.

### Mini Project

- **Decentralized Voting System (dApp)**  
   - Create a decentralized application (dApp) for an e-voting system using blockchain technology.

---

## Repository Structure

```plaintext
.
├── Group_A_Algorithms
│   ├── Assignment1_Fibonacci.py
│   ├── Assignment2_JobSequencing.py
│   ├── Assignment3_FractionalKnapsack.py
│   ├── Assignment4_0_1Knapsack.py
│   ├── Assignment5_BinomialCoefficients.py
│   ├── Assignment6_8Queens.py
│   └── MiniProject_MatrixMultiplication.py
├── Group_B_MachineLearning
│   ├── Assignment1_UberFarePrediction.ipynb
│   ├── Assignment2_EmailSpamDetection.ipynb
│   ├── Assignment3_CustomerChurnPrediction.ipynb
│   ├── Assignment4_GradientDescent.py
│   ├── Assignment5_DiabetesPrediction_KNN.ipynb
│   ├── Assignment6_KMeansClustering.ipynb
│   └── MiniProject_StockMarketPrediction.ipynb
├── Group_C_Blockchain
│   ├── Assignment1_MetamaskInstallation.md
│   ├── Assignment2_CreateWallet.md
│   ├── Assignment3_BankSmartContract.sol
│   ├── Assignment4_StudentDataSmartContract.sol
│   ├── Assignment5_BlockchainTypesSurvey.md
│   └── MiniProject_eVoting_dApp.sol
└── README.md
```

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

