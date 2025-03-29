# Twitter Sentiment Analysis using Logistic Regression

## 📌 Overview
This project performs **sentiment analysis on Twitter data** using **TF-IDF vectorization** and **Logistic Regression**, optimized with **SMOTE for class balancing** and **GridSearchCV for hyperparameter tuning**.


## 🔥 Features
- **Data Preprocessing**: Tokenization, Lemmatization, Stopword removal  
- **TF-IDF Vectorization**: Converts text into numerical form  
- **Class Balancing**: Uses **SMOTE** to handle data imbalance  
- **Hyperparameter Tuning**: Uses **GridSearchCV** to find the best C value  
- **Model Evaluation**: Generates accuracy, classification report, and confusion matrix  
- **Predict Function**: Allows real-time sentiment prediction for new tweets  

## 🛠 Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Hkcoder14/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Model**
   ```bash
   python main.py
   ```

4. **Test Sentiment Prediction**
   ```python
   from main import predict_sentiment
   print(predict_sentiment("This is amazing!"))
   ```

## 💡 Credits
Developed by **Harsh Kumar** 🚀  
