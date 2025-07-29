#  📊 Sentiment-Analysis-Using-Naive-Bayes

This project implements sentiment analysis using Natural Language Processing (NLP) techniques on a dataset of customer product reviews. The goal is to classify the sentiment of each review as either **positive** or **negative** based on its associated rating.

### 🚀 Features

* Data preprocessing including:

  * Emoji-to-emotion conversion
  * Text cleaning (lowercase, punctuation removal)
  * Tokenization, stopword removal, stemming
* Label encoding based on review rating
* Train-test split for validation
* Classification performance evaluation using:

  * Confusion matrix
  * Classification report
  * ROC-AUC analysis

### 📁 Dataset

The notebook uses a CSV file named **`Data Set.csv`** which contains:

* `reviews.text`: Review content
* `reviews.rating`: Numerical rating (used for deriving sentiment)

**Labeling Rule:**

* Rating ≥ 4 → Positive (1)
* Rating < 4 → Negative (0)

### 🛠️ Libraries Used

* `pandas`, `numpy`
* `nltk` (for text preprocessing)
* `scikit-learn` (for model evaluation)

### 📈 Model Evaluation

Performance metrics such as precision, recall, F1-score, and AUC are used to evaluate the binary classification results.

### 🧪 How to Run

1. Make sure the required packages are installed:

   ```bash
   pip install pandas numpy nltk scikit-learn
   ```
2. Download NLTK data:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```
3. Run the notebook: `Sentiment Analysis.ipynb`

### 📌 Notes

* This is a basic binary sentiment classifier based on review scores.
* The model type is not specified in the code snippet (e.g., logistic regression, SVM, etc.). Please make sure to update if used.

### 👨‍💻 Author
  **Veer Saxena**
