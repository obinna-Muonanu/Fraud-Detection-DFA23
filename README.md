# Fraud-Detection-DFA23

## Description
Fraud Detection-DFA 23 is a project developed as part of a hackathon that took place during Datafest 2023. This competition aimed to tackle real-world challenges in fraud detection by leveraging data analysis techniques.The dataset represents transactions and user-related data collected over time from the businesses platform. The goal was to create a predictive model to identify potentially fraudulent transactions. This project showcases the solutions and insights generated during the hackathon, contributing to the broader effort to enhance online payment security.

## Data Source and Description
The dataset was provided by Data Africa community.
The dataset contains information about the transactions and user related data collected
over time from the online platform. The dataset contains 6,000,000 entries and 32
columns.
The features in the dataset includes:
- Transaction ID: A unique identifier for each transaction.
- User ID: A unique identifier for each user.
- Transaction Amount: The amount of money involved in the transaction.
- Transaction Date and Time: The date and time when the transaction
occurred.
- Merchant ID: A unique identifier for each merchant.
- Payment Method: The method used for payment (e.g., credit card, PayPal).
- Country Code: The code representing the country where the transaction took
place.
- Transaction Type: The type of transaction (e.g., purchase, refund).
- Device Type: The type of device used for the transaction (e.g., mobile, desktop).
- IP Address: The internet protocol (IP) address associated with the transaction.
- Browser Type: The web browser used for the transaction.
- Operating System: The operating system of the device used for the transaction.
- Merchant Category: The category or type of business of the merchant.
- User Age: The age of the user.
- User Occupation: The occupation or profession of the user.
- User Income: The income level of the user.
- User Gender: The gender of the user.
- User Account Status: The status of the user's account (e.g., active, suspended).
- Transaction Status: The status of the transaction (e.g., approved, declined).
- Location Distance: The distance between the user and merchant locations.
- Time Taken for Transaction: The time taken to complete the transaction.
- Transaction Time of Day: The time of day when the transaction occurred.
- User's Transaction History: Information about the user's past transactions.
- Merchant's Reputation Score: A score indicating the reputation or
trustworthiness of the merchant.
- User's Device Location: The geographical location of the user's device.
- Transaction Currency: The currency used for the transaction.
- Transaction Purpose: The purpose or reason for the transaction.
- User's Credit Score: The credit score of the user, indicating creditworthiness.
- User's Email Domain: The domain of the user's email address.
- Merchant's Business Age: The age or duration of the merchant's business.
- Transaction Authentication Method: The method used to authenticate the
transaction.
- Fraudulent Flag: The target variable indicating whether the transaction is
fraudulent (1) or not (0).

## Conclusion

The model was trained and evaluated using stratified k-fold cross-validation, ensuring balanced representation in each fold and improving the model's generalization ability. Metrics such as accuracy, F1 score, and precision were calculated for each fold, with the model achieving a perfect score of 1.0 across all these metrics.
It is important to note that such perfect scores are highly improbable in real-world scenarios, primarily due to the synthetic nature of the data used. This ideal performance is a reflection of the dataset rather than the model's true capabilities. 

Despite this, the solution earned 4th place on the leaderboard in the Data Science category, demonstrating its potential within the competition context.
