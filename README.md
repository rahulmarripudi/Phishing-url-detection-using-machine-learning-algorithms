# Phishing-url-detection-using-machine-learning-algorithms
Automated phishing URL detection using machine learning algorithms to enhance cybersecurity. This project leverages lexical, host-based, and content-based features of URLs, employing Supervised learning models for accurate, real-time identification of phishing sites.
Phishing is a type of cyber attack used to trick individuals  into providing sensitive information, such as login  credentials or financial details, through deceptive emails,  messages, or websites.
This project presents a phishing attack detection system which concentrates on detection of phishing using Machine  Learning (ML). It makes use of ML techniques which  include Logistic Regression, Naive Baye’s Classifier,  Random Forest, Decision Tree, SVM, Gradient Boosting  Classifier  to  detect the phished messages.
Advantages:-
• High Accuracy
• Handling Non-linearity
• Scalability
• Robustness to outliers etc.

Machine learning is a branch of Artificial Intelligence (AI) where computers learn to act, adapt to new data without being programmed to do so. The computer is able to act independently of human interaction.

Types of Machine Learning Algorithms:
 Supervised Algorithm: The algorithm learns from labeled data, where each input is associated with a corresponding target label. The goal is to learn a mapping from inputs to outputs .
 Unsupervised Algorithm: The algorithm learns patterns from unlabeled data, identifying hidden structures or relationships within the data.
 Reinforcement Algorithm: The algorithm learns to make decisions by interacting with an environment. It receives feedback in the form of rewards or penalties and adjusts its actions to maximize cumulative reward.

Algorithms Used:

 Logistic Regression: Suited for predicting categorical outcomes, logistic regression distinguishes itself from linear regression by focusing on classification problems.
 K-Nearest Neighbors (KNN): Operating under supervised learning, KNN relies on similarity between new and existing data points to assign the new point to a category most similar to its neighbors.
 Support Vector Machine (SVM): Widely-used for classification and regression tasks, SVM aims to create optimal decision boundaries in n- dimensional space to segregate data points into distinct classes.
 Naive Bayes: Leveraging Bayes' theorem, naive Bayes is effective for text and image classification tasks, providing fast and accurate predictions even with high-dimensional datasets.
 Decision Trees: Suitable for both classification and regression, decision trees represent hierarchical decision rules based on input features, leading to straightforward interpretation.
 Random Forest: An ensemble learning algorithm, random forest combines multiple decision trees to enhance accuracy and mitigate overfitting by aggregating predictions.
 Gradient Boosting: Another ensemble method, gradient boosting sequentially builds decision trees to correct errors of previous trees, improving predictive performance with each iteration.
 CatBoost: Developed by Yandex, CatBoost integrates with deep learning frameworks and can handle diverse data types to address various business challenges effectively.
 XGBoost: Known for its speed and performance, XGBoost implements gradient boosted decision trees, making it dominant in competitive machine learning.
 Multi-layer Perceptron (MLP) Classifier: These classifiers offer diverse capabilities and can be chosen based on the specific requirements and characteristics of the dataset and problem at hand.

Methodology:
1. Data Collection
2. Data preprocessing
3. Feature Extraction
4. Model Selection
5. Model Training
6. Model Evaluation and Prediction

Conclusion:
--> In conclusion, After evaluating various machine learning models, the Gradient Boosting Classifier achieves an impressive 97.4% classification accuracy for URLs, reducing the risk of malicious attachments. Its ability to sequentially enhance weak learners and optimize predictive accuracy makes it particularly effective for discerning between legitimate and malicious URLs. The model exhibits robust performance in detecting subtle patterns indicative of phishing attacks, thereby enhancing overall security.
--> This method involves two main steps: feature extraction and classification. In feature extraction, specific rules for phishing feature extraction are defined and utilized to obtain relevant features. Certain features such as "HTTPS", "AnchorURL", and "WebsiteTraffic" hold significant importance in classifying URLs as phishing or not.


