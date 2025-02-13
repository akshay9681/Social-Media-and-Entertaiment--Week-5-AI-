# Social Media and Entertaiment (Week 5 AI)

 # Social Media and Entertaiment (Week 5 AI)

**Project Overview & Explanation**
This project focuses on Natural Language Processing (NLP) Workloads for text analysis using data wrangling, exploratory data analysis (EDA), and feature engineering techniques. The dataset contains users' preferred content types on social media and entertainment platforms (e.g., movies, news, short videos, series). The goal is to analyze patterns, trends, and sentiment distribution to gain insights into digital consumption behavior.

**Business Problem**
Understanding Digital Content Consumption Patterns
Companies in entertainment, media, and social platforms need to understand:
What type of content users prefer? (e.g., news, movies, series, short videos)
How sentiment varies across different content types?
What are the most frequently used words in users' preferences?
How to utilize NLP techniques like Bag of Words (BoW) & TF-IDF for predictive modeling?

**Potential Business Applications**
Personalized Recommendations: Streaming platforms (Netflix, YouTube, etc.) can use these insights to recommend content.
Marketing Strategies: Brands can identify popular content types to target the right audience.
Content Optimization: Media platforms can produce content based on user preferences.

 **Data Wrangling**
 Loaded the dataset from social_media_entertainment_data.csv.
 Extracted relevant text columns (e.g., "Preferred Content Type").
 Cleaned the text data (removed special characters, punctuation, extra spaces, and converted to lowercase).
 Stored cleaned text for further processing.

 **Exploratory Data Analysis (EDA)**
 Word Frequency Analysis: Identified the most common words in content preferences.
 Bigram Analysis: Found most frequently occurring two-word phrases (bigrams).
 Sentiment Distribution: Counted how many users prefer each content type.

 **Graphs Generated:**
 Word Frequency Bar Chart: Displays the top 10 most common words in user preferences.
 Bigram Frequency Bar Chart: Highlights the most frequently used two-word combinations.
 Sentiment Distribution Bar Chart: Shows the popularity of content types like movies, series, news, and short videos.

 **Feature Engineering**
To prepare the dataset for machine learning, we converted text into numerical representations:

**Bag of Words (BoW)**
What it does? Counts word occurrences in each text.
Why use it? Simple and effective for text classification models.

**TF-IDF (Term Frequency-Inverse Document Frequency)**
What it does? Measures how important a word is relative to the dataset.
Why use it? Reduces the weight of commonly used words.

**Conclusion & Next Steps**
Most users prefer movies, short videos, series, and news.
Frequent words & bigrams indicate popular digital trends.
Sentiment analysis helps understand content demand & engagement.

**Next Steps**
Apply Machine Learning models (e.g., classification, clustering) on BoW/TF-IDF features.
Use Topic Modeling to identify emerging content trends.
Improve recommendation systems using advanced NLP techniques.


