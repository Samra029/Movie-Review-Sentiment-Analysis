# Movie-Review-Sentiment-Analysis
A sentiment analysis model that classifies IMDB movie reviews as positive or negative using machine learning
# **Movie Review Sentiment Analysis**

## **Overview**
This project builds a sentiment analysis model to classify IMDB movie reviews as **positive** or **negative** using machine learning techniques.
## ** Dataset** ##
 https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
## **Features**
- **Preprocessing:** Lowercasing, punctuation & stopword removal, tokenization.
- **Feature Extraction:** TF-IDF (top 5,000 words).
- **Models Trained:**
  - Logistic Regression (**Best Model**: ~89% accuracy)
  - Naive Bayes (~85% accuracy)
- **User Interface:** Command-line interface for real-time sentiment prediction.

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Samra029/Movie-Review-Sentiment-Analysis.git
   cd movie-review-sentiment
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**
Run the script to enter a movie review and get sentiment predictions:
```bash
python movie_review_sentimental_analysis.py
```
## **Future Improvements**
- Deploy as a **web app** (Flask/Streamlit).
- Implement **deep learning** (RNNs, Transformers).
- Add **explainability** (highlight key words influencing sentiment).

## **License**
This project is licensed under the [MIT License](LICENSE).

## **Contributors**
- **Samra Zubair** - Developer

## **Acknowledgments**
- IMDB dataset for training data.
- Scikit-learn, NLTK for model development.



