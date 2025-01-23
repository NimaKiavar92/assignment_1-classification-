# assignment_1-classification-
Natural Language Processing 
#Overview
This project leverages the Wikipedia API to fetch text content from Wikipedia pages, processes the data using scikit-learn, and classifies the text into one of two categories:

Geographic: Content related to geographic locations (e.g., Paris, Mount Everest).
Non-Geographic: Content unrelated to geography (e.g., Albert Einstein, Quantum Mechanics).
The model is built using:

TF-IDF Vectorizer for text feature extraction.
Multinomial Naive Bayes for classification.

#Features
Fetches text from Wikipedia pages with a custom user-agent.
Splits data into training and testing sets for evaluation.
Uses a pipeline with TF-IDF and Naive Bayes for efficient processing.
Outputs classification results with a detailed evaluation report.
Allows classification of new text samples.

#How It Works
Fetching Data: Wikipedia API is used to fetch text data from specified page titles.
Data Preparation:
Geographic and non-geographic texts are labeled and combined.
The dataset is split into training and testing sets.
Model Training:
A pipeline consisting of TF-IDF Vectorizer and Multinomial Naive Bayes is created and trained on the data.
Evaluation: The trained model is tested on the test set, and a classification report is generated.
Prediction: The model can classify new text input as either "geographic" or "non-geographic."

#Future Improvements
Add more diverse Wikipedia pages for better training and generalization.
Fine-tune the TF-IDF vectorizer and Naive Bayes hyperparameters.
Explore advanced models like Support Vector Machines or Transformers for improved accuracy.
Handle edge cases where Wikipedia pages might not exist or have limited content.


