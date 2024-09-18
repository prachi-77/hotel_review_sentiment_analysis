**Hotel Review Sentiment Analysis**

This project focuses on Aspect-Based Sentiment Analysis for hotel reviews, allowing us to determine the sentiment associated with specific aspects like food, cleanliness, staff, room, location, and amenities. The analysis leverages transformer models using the **transformers** library in Python to classify the sentiment of reviews into positive, negative, or neutral categories based on their content and rating.

**Why Sentiment Analysis of Guest Reviews is Essential**

Analyzing guest reviews helps hoteliers and travel agencies understand guest satisfaction or dissatisfaction. By identifying sentiments tied to specific aspects of the hotel experience, businesses can gain actionable insights to improve services and customer satisfaction.

**Types of Sentiment Analysis**

1. **Emotional Analysis:** Identifying emotions (e.g., happiness, frustration).
2. **Multilingual Sentiment Analysis:** Handling reviews in different languages.
3. **Fine-Grained Sentiment Analysis:** Differentiating sentiments beyond just positive and negative (e.g., very positive, neutral, etc.).
4. **Aspect-Based Sentiment Analysis:** Analyzing sentiment for specific features of a product or service.
5. **Intent-Based Sentiment Analysis:** Understanding the goals and motivations expressed in the review.

**Model Used**

**BERTweet**: The finiteautomata/bertweet-base-sentiment-analysis model was used to perform the sentiment analysis, a state-of-the-art transformer model for text classification.

**Code Breakdown**

The project uses the transformers library to create a pipeline for sentiment analysis. Aspect-based sentiment analysis is implemented by searching for specific keywords in reviews and assigning sentiment based on user ratings.

**How it Works**
1. **Aspect Detection:** The code scans a review for specific keywords related to different hotel aspects (e.g., food, cleanliness, room).
2. **Sentiment Classification:** Depending on the rating provided, the detected aspects are classified as either positive, negative, or neutral.
3. **Transformer Model:** The BERTweet model is used to perform sentiment classification on reviews.
