# 🛍️ Flipkart Product Review Sentiment Analysis 📈

Analyze Flipkart product reviews instantly. This project uses deep learning (BERT) to classify sentiment (Positive, Neutral, or Negative) and help you make smarter purchasing decisions.

[![Watch Demo](https://img.shields.io/badge/Watch-Project_Demo-red?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/file/d/1_ZmVVBRPaWQ5l2yJAgf1UUoNYutKuVDK/view?usp=sharing)

---

### Built With
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Model-BERT-blue?style=for-the-badge" alt="BERT" />
  <img src="https://img.shields.io/badge/BeautifulSoup-4C1130?style=for-the-badge&logo=beautifulsoup&logoColor=white" alt="BeautifulSoup" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

---

## 🎯 Project Goals

This project automates the analysis of Flipkart product reviews to:

* ✅ **Automate Sentiment Classification:** Instantly categorize reviews as positive, neutral, or negative.
* 💡 **Provide Purchase Recommendations:** Help users quickly evaluate product quality.
* 🛡️ **Avoid Low-Quality Products:** Save time by highlighting poor-performing items based on customer feedback.

## ✨ Key Features

* **Automated Review Scraping:** Pulls reviews directly from Flipkart product pages.
* **Deep Learning Power:** Utilizes a fine-tuned BERT model for state-of-the-art sentiment classification.
* **Simple UI:** A clean and simple frontend to submit a product link and view the results.
* **Informed Decisions:** Empowers customers to make better buying choices.

## 🛠️ How It Works

The project follows a four-step methodology:

1.  **1️⃣ Web Scraping:**
    * Uses `requests` and `BeautifulSoup4` to scrape customer reviews.
    * Includes logic for handling pagination and request errors.

2.  **2️⃣ Data Preprocessing:**
    * Cleans raw text data using `NLTK` and `spaCy`.
    * Handles emojis, tokenizes sentences, removes stopwords, and performs stemming/lemmatization.

3.  **3️⃣ Model Training:**
    * Compares multiple deep learning architectures (RNN, LSTM, BiLSTM) with various embeddings.
    * **BERT** was chosen as the final model for its superior performance and consistency on real-world test data.

4.  **4️⃣ Output:**
    * Presents a clear summary of the overall sentiment (e.g., 80% Positive, 10% Neutral, 10% Negative).

## 📊 Model Performance

We experimented with several models. **BERT** provided the best and most reliable performance.

| Model | Embedding | Accuracy | Validation Accuracy | Conclusion |
| :--- | :--- | :--- | :--- | :--- |
| RNN | Glove | 40% | 40% | Underfit |
| LSTM | Glove | 41% | 40% | Underfit |
| BiLSTM | Glove | 92% | 90% | Good paper accuracy, weak test performance |
| BiLSTM | Doc2Vec | 94% | 91% | High accuracy, but biased |
| **BERT** | **BERT** | **96.96%** | **91.03%** | **Best performance overall** |

## 🚀 Future Scope

We plan to continue improving this project with new features:

* **Upgrade Model:** Fine-tune a larger variant of BERT (e.g., RoBERTa) for even better accuracy.
* **Enhance UI/UX:** Create a more interactive and visually appealing frontend.
* **Product Recommendations:** Suggest alternative, higher-rated products.
* **Speed Optimization:** Improve the API response time for faster analysis.
* **Trending Products:** Add a feature to show products that are currently trending based on positive reviews.

## 🤝 Our Team

* **Chayan Ghosh** – Model Engineer & API Integration [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chayan-ghosh07/)
* **Rijwanool Karim** – Model Engineer & API Integration
* **Shouryadip Bera** – Backend & Frontend Developer
* **Sk Mahiduzzaman** – Data Cleaning & Research
* **Sayantan Saha** – Data Cleaning & Research

## 📚 References

* Adarsh Kumar, K N Ganesh – Sentiment Analysis on Flipkart
* Medium, Arsha – NLP Preprocessing
* TechTarget – BERT Language Model
* PapersWithCode – Bidirectional LSTM

---

<div align="center">

<br/>

### 🌟 Show your support
If you find this project helpful, please give it a **Star**!

<br/>

<a href="https://drive.google.com/file/d/1_ZmVVBRPaWQ5l2yJAgf1UUoNYutKuVDK/view?usp=sharing" target="_blank">
<img src="https://img.shields.io/badge/Watch_Project_Demo-red?style=for-the-badge&logo=google-drive&logoColor=white" alt="Demo Video"/>
</a>

<br/>
<br/>

<p>Made with ❤️ and Python by <strong>Chayan Ghosh</strong> & Team</p>

</div>
