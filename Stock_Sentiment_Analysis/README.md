**Stock Sentiment Analysis Project**

**Key Program Description:**

	•	Performs sentiment analysis on financial news headlines to predict stock market sentiment (positive vs. negative).
	•	Uses `CountVectorizer` for text feature extraction and a `RandomForestClassifier` for supervised classification.
	•	Evaluates model performance with a confusion matrix, accuracy score, and detailed classification report.
 
**Output Summary:**

	•	Dataset Loaded: Example run with 4,101 samples comprising 25 headline columns plus a label.
	•	Confusion Matrix: Breakdown of true/false positives and negatives.
	•	Accuracy Score: Overall classification accuracy.
	•	Classification Report: Precision, recall, and F1-score for each sentiment class.
 
**Usage Note:**  When running the notebook, upload the supplied `Data.csv` file, or a csv file which must include
Headline columns (`Top1`–`Top25`),
A `Label` column (0 = negative, 1 = positive),
A `Date` column (not used in modeling).
