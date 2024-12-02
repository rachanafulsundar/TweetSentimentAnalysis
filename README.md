# Investigating the Impact of Social Media Sentiment on Stock Prices

---

## **Abstract**
This project explores how sentiment analysis of Twitter data influences stock prices. By leveraging tools like VADER and analyzing real-time tweets, it identifies trends in social media sentiment and correlates them with stock market fluctuations for companies like Tesla and Apple.

---

## **Motivation**
The project aims to assist investors by providing insights into how public sentiment impacts stock prices. Social media platforms like Twitter reflect real-time user opinions, making them valuable for investment strategies and market analysis.

---

## **Modules and Scope**

### **1. Data Collection and Preprocessing**
- **Twitter Data Extraction**: Tweets were fetched using the `twython` library via the Twitter API.
- **Data Cleaning**:
  - Merged multiple datasets into a single dataframe.
  - Filled missing values with relevant data.
  - Removed special characters, emojis, and duplicates.

### **2. Sentiment Analysis**
- **Methodology**:
  - Used `nltk.sentiment.vader` for text analysis and polarity detection.
  - Classified tweets into positive, negative, and neutral sentiments.
  - Accounted for intensifiers, negations, and punctuation during analysis.
- **Objective**:
  - Correlate sentiment trends with stock market performance.

### **3. Correlation with Stock Prices**
- **Stock Data Integration**:
  - Extracted open and close values for Tesla and Apple stocks.
  - Mapped sentiment scores to stock performance.
- **Analysis**:
  - Visualized sentiment trends and stock valuations.
  - Observed the impact of spikes in positive/negative tweets on stock price movements.

---

## **Key Observations**
1. **Tesla**:
   - Positive tweets strongly correlate with increased stock valuation.
   - Negative tweets often result in stock price drops, though "price_gain" log values were used for better understanding.
2. **Apple**:
   - Positive tweets significantly influence stock valuation.
   - No clear correlation between negative tweets and stock price drops.

---

## **Tools and Technologies**

### **Programming Languages**
- Python

### **Libraries and Frameworks**
1. **`numpy`**: For mathematical operations.
2. **`twython`**: To fetch Twitter data using the Twitter API.
3. **`nltk` and `nltk.sentiment.vader`**: For natural language processing and sentiment analysis.
4. **`pandas`**: For data manipulation and processing.

### **Sentiment Analysis Framework**
- **VADER (Valence Aware Dictionary and Sentiment Reasoner)**:
  - Pre-built lexicon for analyzing social media text.
  - Accounts for modifiers like intensifiers and negations.

---

## **System Requirements**

### **Software Requirements**
- Python 3.8+
- Twitter Developer Account (for API access)

------------
![Screenshot 2024-12-02 013013](https://github.com/user-attachments/assets/61a34344-3023-4e09-8d82-73c309d75eca)
![Screenshot 2024-12-02 013028](https://github.com/user-attachments/assets/6b8e80b5-7fce-47e5-9b21-093003794515)


