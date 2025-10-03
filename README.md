# 📊 Sentiment Analysis with Real-Time Twitter Data

This project performs **sentiment analysis on real-time Twitter (X) data** using the Twitter API and Natural Language Processing (NLP).  
It fetches live tweets based on a given keyword/hashtag, processes the text, and classifies sentiments into categories such as **Positive, Negative, or Neutral**.

---

## 🚀 Features
- Fetches **real-time tweets** using the Twitter/X API.
- Cleans and preprocesses tweet text (removes URLs, mentions, hashtags, etc.).
- Uses NLP techniques for sentiment classification.
- Visualizes sentiment distribution (charts/graphs).
- Can be extended for trend analysis and dashboards.

---

## 🛠️ Technologies Used
- **Python**
- **Tweepy** (for Twitter/X API)
- **TextBlob / NLTK / VaderSentiment** (for sentiment analysis)
- **Matplotlib / Seaborn** (for visualization)
- **Pandas & NumPy** (for data processing)
- **Jupyter Notebook**

---

## 📂 Project Structure
```
├── Sentiment_analysis.ipynb   # Sentiment analysis logic
├── X_api.ipynb                # Twitter API connection & data fetching
├── README.md                  # Project documentation
```
---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a Twitter/X Developer Account**
   - Go to [Twitter Developer Portal](https://developer.twitter.com/)
   - Generate API Keys and Access Tokens.
   - Save them in your notebook or as environment variables.

---

## ▶️ How to Run

1. Open `X_api.ipynb` to fetch live tweets.  
   - Enter your API keys and search query (keyword/hashtag).  
   - Tweets will be saved in a DataFrame.  

2. Open `Sentiment_analysis.ipynb`.  
   - Run the notebook to process the tweets.  
   - Sentiment will be classified and visualized.  

---

## 📊 Example Output

- **Input:** Tweets about `"AI"`  
- **Output:**  

| Sentiment  | Count |
|------------|-------|
| Positive   | 120   |
| Neutral    | 65    |
| Negative   | 42    |

---

## 🔮 Future Improvements
- Deploy as a **web app** with Streamlit or Flask.
- Add support for multiple languages.
- Train a custom ML/DL model (e.g., BERT, LSTM) for better accuracy.
- Store results in a database for historical sentiment tracking.

---

## 🤝 Contributing
Contributions are welcome!  
Feel free to fork this repo, raise issues, and submit pull requests.

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author
- **Sai Sabarinath K** – B.Tech AI & Data Science  
