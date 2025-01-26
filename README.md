# Sentiment Analysis Project

## Introduction
This project is a sentiment analysis system designed to classify text into positive, negative or neutral sentiments. Sentiment analysis is a key application in natural language processing (NLP) used widely for tasks such as opinion mining, social media analysis, and customer feedback evaluation.

## Techniques and Models Used
- **Natural Language Processing (NLP)**: Text preprocessing techniques such as tokenization, stopword removal, and stemming/lemmatization.
- **Machine Learning Algorithm**: Logistic Regression was used for classification. This algorithm is well-suited for binary classification tasks.

## Data Preprocessing
1. **Text Cleaning**: Removed special characters, numbers, and unwanted symbols from the dataset to retain only meaningful text.
2. **Tokenization**: Split sentences into individual words for easier analysis.
3. **Stopword Removal**: Removed commonly used words like "and", "is", "the" that do not contribute to the sentiment.
4. **Vectorization**: Transformed text data into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)** for better model performance.

## Model Training
- **Logistic Regression** was employed to build the predictive model.
- The dataset was split into training and testing sets using an 80-20 ratio.
- The TF-IDF features served as the input to the logistic regression model.

## Evaluation Metrics
The following metrics were used to evaluate the model's performance:
- **Accuracy**: Percentage of correctly predicted samples.
- **Confusion Matrix**: Evaluated true positives, true negatives, false positives, and false negatives.

## Results
- **Prediction Accuracy**: The model achieved an accuracy of approximately 88% on the testing data.
- **Precision and Recall**: These metrics were also calculated to assess the balance between false positives and false negatives.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sentiment-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Sentiment_Analysis.ipynb
   ```

## Dependencies
- **Libraries**:
  - pandas
  - numpy
  - sklearn
  - nltk

## Conclusion
This project demonstrates the use of NLP techniques and logistic regression for sentiment analysis. By applying preprocessing steps and leveraging TF-IDF for feature extraction, the model achieved high accuracy in predicting text sentiment. It serves as a foundational system for tasks like social media monitoring or customer feedback analysis.

---

### Author
Faraz Ashraf
