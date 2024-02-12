**Project Description: Sentiment Analysis on Amazon Fine Food Reviews**

The provided Python notebook demonstrates a sentiment analysis project focused on Amazon Fine Food Reviews. Here is a step-by-step overview of the project:

**Step 0: Read in Data and NLTK Basics**
- Reads the Amazon Fine Food Reviews dataset using Pandas.
- Performs a quick exploratory data analysis (EDA) by visualizing the distribution of review scores using a bar chart.

**Step 1: Basic NLTK**
- Tokenizes and tags words using the Natural Language Toolkit (NLTK).
- Utilizes NLTK's part-of-speech tagging and named entity chunking to extract linguistic features from the reviews.

**Step 2: VADER Sentiment Scoring**
- Implements VADER sentiment analysis using NLTK's SentimentIntensityAnalyzer to calculate compound, negative, neutral, and positive scores for each review.
- Visualizes the compound scores by Amazon star reviews.

**Step 3: Roberta Pretrained Model**
- Utilizes a pre-trained RoBERTa model from the Hugging Face Transformers library for sentiment analysis.
- Compares the RoBERTa model's sentiment scores with VADER scores for each review.

**Step 4: Combine and Compare**
- Combines VADER and RoBERTa sentiment scores into a DataFrame for comparison.
- Creates a pair plot to visually compare sentiment scores from both models.

**Step 5: Review Examples: Positive 1-Star and Negative 5-Star Reviews**
- Examines specific examples where the sentiment model scores and review scores differ significantly.

**Extra: The Transformers Pipeline**
- Demonstrates the usage of the Transformers library pipeline for sentiment analysis, providing a quick and easy way to obtain sentiment predictions using pre-trained models.

Overall, this project showcases the application of both traditional rule-based sentiment analysis (VADER) and transformer-based deep learning models (RoBERTa) on Amazon Fine Food Reviews, offering insights into the sentiment behind customer feedback. Additionally, the notebook explores specific examples where sentiment analysis models might diverge from the assigned review scores.
