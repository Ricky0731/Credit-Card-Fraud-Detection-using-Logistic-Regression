
# Credit Card Fraud Detection using Logistic Regression

![Credit Card Fraud Detection](https://via.placeholder.com/800x200.png)

## 📄 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model](#model)
- [Evaluation](#evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Introduction
Credit card fraud detection is a crucial task in the financial industry to prevent unauthorized transactions and protect users. This project utilizes Logistic Regression, a fundamental machine learning algorithm, to classify transactions as fraudulent or legitimate.

## 📊 Dataset
The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013 by European cardholders.

- **Number of Instances:** 284,807
- **Number of Features:** 30 (28 anonymized features, Time, and Amount)

## 🔄 Data Preprocessing
Data preprocessing steps include:
- Handling missing values
- Feature scaling
- Splitting the dataset into training and testing sets
- Balancing the dataset using techniques like SMOTE (Synthetic Minority Over-sampling Technique)

## 🧠 Model
Logistic Regression is used to model the relationship between the transaction features and the binary outcome (fraud or legitimate).

### Model Parameters:
- **Solver:** lbfgs
- **Maximum Iterations:** 100

## 📈 Evaluation
The model's performance is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

## 🛠️ Installation
To get a local copy up and running, follow these simple steps.

1. Clone the repo
   ```sh
   git clone https://github.com/your_username/credit-card-fraud-detection.git
   ```
2. Install the required packages
   ```sh
   pip install -r requirements.txt
   ```

## 🚀 Usage
Follow these steps to use the project:

1. Navigate to the project directory
   ```sh
   cd credit-card-fraud-detection
   ```
2. Run the script
   ```sh
   python main.py
   ```

## 📊 Results
Here are some of the key results from the Logistic Regression model:

- **Accuracy:** 99.8%
- **Precision:** 92%
- **Recall:** 88%
- **F1 Score:** 90%
- **ROC-AUC Score:** 98%

These results indicate the model's high performance in detecting fraudulent transactions.

## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact
saitulasi0731@gmail.com

Project Link: https://github.com/Ricky0731/Credit-Card-Fraud-Detection-using-Logistic-Regression
