# EA - Twitter Sentiment Classification
## Project Overview
Objective: Predict an individual’s belief in climate change based on their tweets.

#### Context:
Many companies prioritize environmental sustainability and wish to understand public sentiment regarding climate change. This project, named EA - Twitter Sentiment Classification, focuses on creating a machine learning model to classify whether a person believes in climate change based on their tweets.

### Importance
####Market Research:
This project adds value to companies' market research efforts, helping them gauge how their eco-friendly products or services may be received. It provides insights into consumer sentiment across demographics and geographic locations.

### Evaluation Metric
#### Metric:
The model's performance is evaluated using the Mean F1-Score. F1-Score combines precision and recall, providing a balanced measure of the model's effectiveness.

### Explanation:

- Precision: Ratio of true positives to all predicted positives.
- Recall: Ratio of true positives to all actual positives.
- F1-Score: Balances precision and recall, favoring moderately good performance on both.

### Data Analysis Insights
#### Word Frequencies:

- Most common bi-gram: ['climate' 'change'], indicating prevalent discussions.
  ![word](https://github.com/AndisiweJ/Twitter-Sentiment-Classification/assets/107894108/fd460d5b-890a-4c9f-9755-6d271d8be47c)
  
- Occurrence of ['http' 'co'] suggests links in tweets.
 ![words](https://github.com/AndisiweJ/Twitter-Sentiment-Classification/assets/107894108/513da45a-b240-435b-8b78-85d733bdb020)

- Other significant bi-grams: ['global' 'warming'], ['believe' 'climate'], ['change' 'real'].
- Presence of potential encoding issues: ['â' 'Â'], ['Ã' 'â'], ['â' 'â'].

### Text Cleaning Operations
- Lowercasing
Purpose:
- Normalization and standardization of text data.

- Stopword Removal
Stopwords:
- Common words like articles and prepositions are removed to focus on meaningful words.

- Punctuation Removal
Purpose:
- Elimination of noise; emphasis on words and meanings.

### Model Selection
- Classification Models
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- Naive Bayes
- K-Nearest Neighbours

### Model Evaluation
#### Feature Scaling:
Applied to Logistic Regression, Support Vector Machine, and K-Nearest Neighbours for consistent model performance.

#### Metrics:
Classification reports used for performance assessment, providing precision, recall, and F1-Score.

### Weather Hub App
#### Introduction:
Weather Hub is introduced as an application offering real-time insights into climate change sentiment derived from tweets.

### Key Features:

- Predicts sentiments accurately using tweet keywords.
- Enables customization of marketing strategies based on sentiment analysis.
- Assists in understanding customer needs for informed decision-making.

### Conclusion
EA - Twitter Sentiment Classification provides a valuable tool for companies seeking to understand public beliefs about climate change. The combination of effective text processing, diverse classification models, and insightful analysis allows companies to adapt their strategies, engage with customers, and stay aligned with evolving sentiments. Weather Hub, the resulting application, further simplifies this process, offering a user-friendly experience for accessing real-time climate change sentiment data.

