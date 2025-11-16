# 🌟 Flipkart Product Review Sentiment Analysis

A modern deep-learning powered system that **scrapes**, **analyzes**, and **classifies** Flipkart product reviews into **Positive**, **Neutral**, and **Negative** sentiments. Built with state‑of‑the‑art NLP models and a clean web interface, this project helps users make smarter and faster buying decisions.

---

## 🚀 Project Overview

This project automates the entire workflow of:

* 🔍 **Scraping** Flipkart reviews
* 🧹 **Cleaning & preprocessing** the text
* 🤖 **Analyzing sentiment** using multiple deep learning models
* 📊 **Comparing model performances**
* 🌐 **Providing real-time predictions** through a simple UI

The final system uses **BERT**, achieving **96.96% accuracy**, making it the most reliable model for product sentiment analysis.

📌 **Video Demo:** [Project Demo (Google Drive)](https://drive.google.com/file/d/1GCZzpe-t29QAWzkp3ZV0K3h4yZP6JyUy/view)

📌 **Developer Profile:** [Chayan Ghosh – LinkedIn](https://www.linkedin.com/in/chayan-ghosh07/)

---

## 🎯 Project Objectives

* ⭐ Automatically classify product reviews (Positive / Neutral / Negative)
* 🛍️ Help users make informed purchase decisions
* 🚫 Prevent buying low-quality products
* ⚙️ Provide accurate sentiment summarization

---

## 🛠️ Technologies Used

### 🔧 Backend

* **Python** – Core development
* **BeautifulSoup4** – Web scraping
* **Flask** – API creation

### 🧠 Deep Learning / NLP

* **BERT** (Best performing model)
* **RNN**, **LSTM**, **BiLSTM** with Glove / Word2Vec / Doc2Vec
* **TensorFlow GPU** – Accelerated training
* **NLTK**, **spaCy** – Text preprocessing

### 🎨 Frontend

* **HTML**, **CSS**, **JavaScript** – Review submission & result UI

---

## 📊 Model Performance Comparison

| Model    | Embedding | Accuracy   | Validation Accuracy | Conclusion                        |
| -------- | --------- | ---------- | ------------------- | --------------------------------- |
| RNN      | Glove     | 40%        | 40%                 | ❌ Underfit                        |
| LSTM     | Glove     | 41%        | 40%                 | ❌ Underfit                        |
| BiLSTM   | Glove     | 92%        | 90%                 | ⚠️ Good on paper, weak in testing |
| BiLSTM   | Doc2Vec   | 94%        | 91%                 | ⚠️ High but biased                |
| **BERT** | **BERT**  | **96.96%** | **91.03%**          | 🏆 **Best overall**               |

---

## 🧩 Methodology

### 1️⃣ **Web Scraping**

* Collects reviews using `requests` + `BeautifulSoup4`
* Handles pagination and invalid links

### 2️⃣ **Data Preprocessing**

* Emoji & noise removal
* Tokenization
* Stopword removal
* Stemming / Lemmatization

### 3️⃣ **Model Training**

* Multiple NLP models compared
* BERT selected as final model due to consistent results

### 4️⃣ **Output**

* Sentiment summary (Positive / Neutral / Negative)
* Clean UI showing classification results

---

## ✨ Features

* 🔄 Automated Flipkart review scraping
* 🧠 Deep-learning based sentiment prediction
* 📈 Model comparison dashboard (optional)
* 🧼 End‑to‑end clean preprocessing pipeline
* 🌐 Simple and intuitive UI
* 🛍️ Helps users avoid low‑quality products

---

## 🔮 Future Scope

* 🔼 Upgrade BERT to larger variants
* 🎨 Improve UI/UX
* 🧠 Add product recommendation engine
* ⚡ Optimize API response time
* 📊 Add trending product insights

---

## 👥 Contributors

* **Chayan Ghosh** – Model Engineer & API Integration
* **Rijwanool Karim** – Model Engineer & API Integration
* **Shouryadip Bera** – Backend & Frontend Developer
* **Sk Mahiduzzaman** – Data Cleaning & Research
* **Sayantan Saha** – Data Cleaning & Research

---

## 📚 References

* Adarsh Kumar, K N Ganesh – Sentiment Analysis on Flipkart
* Medium (Arsha) – NLP Preprocessing
* TechTarget – BERT Model Overview
* PapersWithCode – Bidirectional LSTM

---

## ⭐ Show Your Support!

If you like this project, feel free to ⭐ **star the repository** and connect with me on **LinkedIn**!

📌 **Chayan Ghosh LinkedIn:** [https://www.linkedin.com/in/chayan-ghosh07/](https://www.linkedin.com/in/chayan-ghosh07/)

---

## 📝 Project Lines — Stylish Footer

A few neat lines you can add at the bottom of the README to highlight the project, team and useful links.

> **Project:** Flipkart Product Review Sentiment Analysis — Deep‑learning driven sentiment classification (BERT)
>
> **Team:** Chayan Ghosh • Rijwanool Karim • Shouryadip Bera • Sk Mahiduzzaman • Sayantan Saha
>
> **Demo:** [https://drive.google.com/file/d/1GCZzpe-t29QAWzkp3ZV0K3h4yZP6JyUy/view](https://drive.google.com/file/d/1GCZzpe-t29QAWzkp3ZV0K3h4yZP6JyUy/view)
>
> **LinkedIn:** [https://www.linkedin.com/in/chayan-ghosh07/](https://www.linkedin.com/in/chayan-ghosh07/)
>
> **Portfolio:** [https://www.chayanghosh.com/](https://www.chayanghosh.com/)

---

## 💻 HTML / CSS Footer Snippet

You can copy-paste this footer into any project site or HTML README preview to show a polished footer with team credits and links.

```html
<!-- Project Footer -->
<footer class="project-footer">
  <div class="container">
    <p class="title">Flipkart Product Review Sentiment Analysis</p>
    <p class="team">Team: <strong>Chayan Ghosh</strong> • Rijwanool Karim • Shouryadip Bera • Sk Mahiduzzaman • Sayantan Saha</p>
    <div class="links">
      <a href="https://drive.google.com/file/d/1GCZzpe-t29QAWzkp3ZV0K3h4yZP6JyUy/view" target="_blank" rel="noopener">Demo Video</a>
      <a href="https://www.linkedin.com/in/chayan-ghosh07/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://www.chayanghosh.com/" target="_blank" rel="noopener">Portfolio</a>
    </div>
  </div>
</footer>
```

```css
/* Minimal footer styles */
.project-footer{
  background: linear-gradient(90deg, rgba(2,6,23,1) 0%, rgba(9,57,120,1) 100%);
  color: #ffffff;
  padding: 24px 16px;
  border-radius: 8px;
  margin-top: 24px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
}
.project-footer .container{max-width:900px;margin:0 auto;text-align:center}
.project-footer .title{font-weight:700;font-size:18px;margin-bottom:6px}
.project-footer .team{opacity:0.95;margin-bottom:8px}
.project-footer .links a{display:inline-block;margin:0 8px;padding:8px 12px;background:rgba(255,255,255,0.08);border-radius:6px;text-decoration:none;color:#fff}
.project-footer .links a:hover{background:rgba(255,255,255,0.14)}
```

---

If you'd like, I can:

* Convert this footer into a ready-to-use React component (Tailwind style)
* Add a dark/light toggle example
* Include social icons (SVG) next to links

Tell me which you prefer and I will add it right into the README.
