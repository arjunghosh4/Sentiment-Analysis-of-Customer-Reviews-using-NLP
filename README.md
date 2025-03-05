# Sentiment Analysis and Topic Modelling of Amazon Echo Reviews Using NLP

## Overview
This project focuses on analyzing **Amazon Echo customer reviews** using **Natural Language Processing (NLP)**. The primary objectives are:
- **Sentiment Analysis**: Determine whether reviews are **positive, neutral, or negative**.
- **Topic Modelling**: Identify key themes in customer feedback using **unsupervised learning**.
- **Business Insights**: Leverage insights to enhance product features and improve the customer experience.

## Problem Statement
Customer reviews contain valuable insights that businesses can use to refine their products and services. However, manually analyzing thousands of reviews is inefficient. **This project automates sentiment and theme detection**, allowing businesses to:
- Understand **common customer pain points**.
- Identify **product strengths and weaknesses**.
- Improve **marketing and product development strategies**.

## Data Source
- **Dataset**: Amazon Echo Reviews Dataset
- **Public Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/haitaox503/amazonreviewscsv?select=amazon_reviews.csv)
- **Data Format**: Contains customer reviews, ratings, and metadata.

## Project Structure
This repository contains:
### 1. **Sentiment_Analysis_and_Topic_Modelling_of_Amazon_Echo_Reviews_Using_NLP.ipynb**
- Loads and preprocesses **Amazon Echo reviews**.
- Performs **sentiment analysis** using NLP techniques.
- Applies **topic modelling (LDA, NMF, or BERTopic)** to extract recurring themes.
- Generates **visual insights** to interpret findings.

## Installation & Dependencies
To run the project, install the required dependencies:
```sh
pip install pandas numpy nltk scikit-learn matplotlib seaborn wordcloud spacy gensim
```

## Usage Instructions
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/sentiment-analysis-amazon-echo.git
   cd sentiment-analysis-amazon-echo
   ```
2. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook Sentiment_Analysis_and_Topic_Modelling_of_Amazon_Echo_Reviews_Using_NLP.ipynb
   ```
   - This will perform sentiment analysis and topic modelling on the dataset.

## Expected Outputs
- **Sentiment Classification:** Positive, Neutral, or Negative sentiment per review.
- **Topic Insights:** Key recurring themes in customer reviews.
- **Data Visualizations:** Word clouds, bar plots, and topic distributions.

## Future Enhancements
- **Deploy as an API for real-time sentiment analysis.**
- **Fine-tune NLP models using transformers (BERT, RoBERTa).**
- **Expand dataset to analyze multiple product categories.**

## Business Impact
✅ **Automates sentiment classification** for Amazon Echo reviews.
✅ **Identifies critical product improvement areas.**
✅ **Supports data-driven decision-making for product teams.**

## License
This project is for **educational and research purposes** only.
