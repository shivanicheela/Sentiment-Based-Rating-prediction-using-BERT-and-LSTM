# Sentiment-Based-Rating-prediction-using-BERT-and-LSTM
This project aims to predict a numerical rating (like 1 to 5 stars) based on the sentiment of user-written text reviews. Instead of just saying whether a review is positive or negative, we try to understand how positive or how negative the review is—just like how real users rate products or services on websites.

To achieve this, we combine the power of:
	•	BERT (Bidirectional Encoder Representations from Transformers)
	•	LSTM (Long Short-Term Memory, a type of Recurrent Neural Network)
Most sentiment analysis projects classify reviews as just positive or negative, but this is not enough for platforms like Amazon, Flipkart, Zomato, etc., which work based on star ratings.

This project goes one step further and predicts actual star ratings (e.g., 1 to 5) by understanding the depth of sentiment in the review.
How it works : 
1.	Input: User writes a review (text)
	•	Example: "The food was delicious and service was excellent!"
	2.	BERT Embedding:
	•	The review is passed into BERT, which converts it into a context-aware vector (embedding) that captures the meaning and emotion behind the text.
	3.	LSTM Prediction:
	•	The BERT embeddings are then fed into an LSTM model, which analyzes the sequence and predicts the most appropriate rating (e.g., 5 stars).
Output:
	•	A star rating is predicted (e.g., 4, 5, etc.)
