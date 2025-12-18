# Exploring Customer Sentiments on Amazon Kindle
Reviews
Data Analysis & Sentiment Mining Project Report
1. Introduction
Online customer reviews play a critical role in understanding product performance and customer satisfaction.
This project analyses a large-scale Amazon Kindle review dataset to uncover sentiment patterns, reviewer
behaviour, and product-level insights using Python-based data analysis and Natural Language Processing
(NLP) techniques.
2. Project Objectives
- Perform sentiment analysis on Amazon Kindle reviews to classify them as Positive, Neutral, or Negative.
- Clean and preprocess large volumes of unstructured text data.
- Analyse rating distributions, reviewer activity, and frequently reviewed products.
- Visualise insights using plots and word clouds to support decision-making.
3. Dataset Description
The dataset consists of 982,619 Amazon Kindle reviews. Each record includes reviewer details, product
identifiers (ASIN), review text, rating scores, and timestamps. Key attributes include reviewerID, asin,
reviewText, overall rating, summary, and reviewTime.
4. Data Quality and Preparation
Initial data quality checks confirmed no missing values in key identifier fields (reviewerID and ASIN).
Duplicate reviews were analysed and retained where timestamps differed. Text preprocessing steps
included punctuation removal, lowercasing, stopword removal, and lemmatization to standardise review text
for analysis.
5. Exploratory Data Analysis
Exploratory analysis showed a highly imbalanced rating distribution, with the majority of reviews rated 5
stars. Over 68,000 unique reviewers were identified, with a small subset contributing a large number of
reviews. Products with more than 200 reviews were filtered to ensure reliable product-level insights.
6. Sentiment Analysis Methodology
Sentiment analysis was performed using the VADER Sentiment Intensity Analyzer from NLTK. Each review
was assigned a polarity score and classified as Positive, Neutral, or Negative based on predefined
thresholds. This lexicon-based approach is well-suited for analysing short, opinionated text such as product
reviews.
7. Key Findings
- Approximately 89.7% of reviews expressed positive sentiment, indicating high customer satisfaction.
- Negative sentiments accounted for about 8.8%, highlighting potential improvement areas.
- Higher-rated reviews generally contained longer and more descriptive text.
- Word cloud analysis revealed negative keywords such as 'waste' and 'boring' in low-rated reviews, while
positive reviews featured words like 'love' and 'great book'.
8. Business Value and Use Cases
The insights generated from this analysis can help publishers and sellers identify well-performing books,
detect recurring customer pain points, and improve product quality. Sentiment trends can also be used for
recommendation systems, customer experience monitoring, and marketing strategies.
9. Limitations
The analysis relies on lexicon-based sentiment detection, which may struggle with sarcasm or contextual
nuances. Additionally, the dataset is skewed towards positive ratings, which may bias overall sentiment
interpretation.
10. Recommendations
- Apply advanced machine learning or transformer-based models (e.g., BERT) for deeper sentiment
understanding.
- Perform aspect-based sentiment analysis to pinpoint specific strengths and weaknesses.
- Monitor sentiment trends over time to track changes in customer perception.
11. Conclusion
This project demonstrates how large-scale customer review data can be transformed into actionable insights
using Python and NLP. The findings highlight strong customer satisfaction within the Amazon Kindle store
while also revealing opportunities for targeted improvements. Overall, sentiment analysis proves to be a
powerful tool for data-driven decision-making.
