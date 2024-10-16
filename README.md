# **SMS Spam Detection Model Using NLP** 

## **Goal of the Model**

The main objective of this project is to classify SMS messages as **Spam** or **Ham** (not spam) using various Natural Language Processing (NLP) techniques and machine learning algorithms.

## **Source of Data**

The dataset used for this project is sourced from **Kaggle**.

---

## **Work Flow**

1. **Importing the required libraries**
2. **Loading the Dataset**
3. **Basic Understanding of Data**
4. **Data Preprocessing**
5. **Exploratory Data Analysis (EDA) & Text Preprocessing**
6. **Model Training, Building, and Evaluation**

---

### **Key Tasks in Text Preprocessing:**

- **Lowercasing** all text data
- **Tokenization**: Splitting text into individual words
- **Removing special characters**, stopwords, and punctuation
- **Stemming**: Reducing words to their root form
- **Finding most common words** in Ham and Spam messages
- Analyzing **30 most frequent words** in Ham and Spam messages

### **Feature Engineering in EDA:**

- Calculated the **number of characters, words, and sentences** in each message
- Performed **Univariate/Bivariate Analysis** to explore the dataset
- **SMOTE** technique was applied to handle the imbalance in the dataset

---

## **Modeling and Algorithms**

We trained, built, and evaluated the model using the following algorithms:

- **Naive Bayes**
- **Support Vector Machine**
- **K-Nearest Neighbors**
- **Decision Tree**
- **Logistic Regression**
- **Random Forest**
- **AdaBoost**
- **Bagging Classifier**
- **Extra Trees Classifier**
- **Gradient Boosting**
- **XGBoost**

Additionally, applied for improving the performance

- **Voting Classifier**
- **Stacking Classifier**


## **Model Performance Evaluation**

### **Model Performance Observation**

- **Cross-Validation Accuracy:**
  - The average accuracy from cross-validation is **99.85%**, with minimal variation, which indicates high consistency in performance.
  
- **Training Accuracy:**
  - The model achieved a perfect **100% accuracy** on the training data, showcasing its ability to learn the data effectively.
  
- **Test Accuracy:**
  - The test accuracy is **99.89%**, confirming that the model generalizes well on unseen data.
  
- **Precision & Recall:**
  - Both precision and recall are **99.89%**, meaning the model is highly accurate in predicting spam and non-spam messages.

### **Conclusion:**

The model shows **excellent performance** with high accuracy, precision, and recall, making it a robust solution for SMS Spam Detection.
