# **AI Product Review Sentiment Analyzer**
An end-to-end NLP project that **scrapes product reviews from e-commerce sites**, cleans and preprocesses the text, and uses **Machine Learning + BERT** to classify reviews as ⭐ Positive, 🤷 Neutral, or 👎 Negative. Includes an interactive **Streamlit dashboard** with visualizations, word clouds, and review insights.

## **Features**
- 🔎 **Web Scraping** from Amazon/Flipkart/BestBuy  
- 🧹 **Data Cleaning & Preprocessing** (stopwords, lemmatization, normalization)  
- 🤖 **Machine Learning Models** (Logistic Regression, Naive Bayes, SVM)  
- 🧠 **Advanced BERT Model** for high-accuracy sentiment classification  
- 📊 **Interactive Dashboard** (Streamlit)  
- ☁️ **Easy Deployment** (Streamlit Cloud / HuggingFace Spaces)  
- 📈 **Visual Insights** (word clouds, sentiment distribution, charts)

## 📂 **Project Structure**
```
sentiment-analyzer/
│
├── data/
│   ├── raw_reviews.csv
│   └── cleaned_reviews.csv
│
├── scraper/
│   └── scraper.py
│
├── preprocessing/
│   └── preprocess.py
│
├── models/
│   ├── baseline_model.pkl
│   └── bert_model/
│
├── dashboard/
│   └── app.py
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
└── README.md
```

## 🧰 **Tech Stack**
**Python** – core language  
**BeautifulSoup / Selenium** – scraping  
**pandas / numpy** – data handling  
**scikit-learn** – ML models  
**Transformers (HuggingFace)** – BERT  
**Matplotlib / Plotly / wordcloud** – visualizations  
**Streamlit** – dashboard UI  

## 🗂️ **How It Works**
### **1. Scrape Reviews**
Use `scraper.py` to collect:
- Review text  
- Rating  
- Title  
- Date  
- Reviewer  

Saves to `data/raw_reviews.csv`.

### **2. Preprocess Text**
Run `preprocess.py` to clean:
- Stopwords  
- Lemmatization  
- Lowercasing  
- Emoji & symbol removal  
- Rating → sentiment labels  

Outputs `data/cleaned_reviews.csv`.

### **3. Train Models**
Use notebooks:
- `EDA.ipynb` → visual insights  
- `Model_Training.ipynb` → train baseline & BERT models  

Models saved to `models/`.

### **4. Run Dashboard**
```
streamlit run dashboard/app.py
```

Dashboard includes:
- Sentiment stats  
- Review table  
- Word clouds  
- Charts  
- URL input for live scraping  

## 📊 **Screenshots**
_Add your visuals here._

## 🚀 **Deployment**
Recommended deployment platforms:
- Streamlit Cloud  
- HuggingFace Spaces  
- Render.com  
- Docker  

## 🧪 **Future Improvements**
- Multi-product comparison  
- Topic modeling (LDA)  
- Automatic summary generation  
- Database to store scraped products  
- Browser extension integration  

## 🏆 **Why This Project Matters**
This project demonstrates:
- Real-world NLP skills  
- Web scraping  
- ML + deep learning (BERT)  
- Data engineering  
- Interactive UI design  
- Deployment workflow  


