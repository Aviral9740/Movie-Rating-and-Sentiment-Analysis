# Movie-Rating-and-Sentiment-Analysis
This is a Machine learning project that predicts the rating and general public sentiment according to the review that the movie gets. This is the first time I am working on a NLP project and I have used Linear Regression for the simplicity of the project.

## Project Overview

1. Preprocesses raw text reviews:

- Lowercasing

- Removing special characters

- Removing stopwords (NLTK)

- Stemming

2. Transforms reviews into numeric features using TF-IDF.

3. Trains a Logistic Regression model to predict movie ratings.

4. Maps predicted ratings to sentiments:

- Rating ≥ 7 → Positive

- Rating ≤ 4 → Negative

- Rating 5–6 → Neutral

5. Evaluates performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrices.
