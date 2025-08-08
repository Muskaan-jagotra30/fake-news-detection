# 📰 Fake News Detection App

An advanced **Machine Learning** application built with **Streamlit**, leveraging **Naive Bayes classification** and **TF-IDF vectorization** to classify news articles as *Fake* or *Real*.  
The app provides a clean, interactive UI, making it simple for anyone to verify the authenticity of news content.

---

## ✨ Features
- **Real-Time Detection** – Instant classification of any news article.
- **ML-Powered Accuracy** – Uses TF-IDF and Naive Bayes for reliable results.
- **Streamlit Interface** – User-friendly and interactive.
- **Docker Support** – Deploy anywhere effortlessly.
- **Lightweight & Fast** – Quick response even on low-end machines.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the application
```bash
streamlit run app.py
```

### 🐳 Run with Docker
```bash
docker build -t fake-news-detection .
docker run -p 8501:8501 fake-news-detection
```

---

## 📂 Project Structure
```
fake-news-detection/
│-- app.py                # Main Streamlit application
│-- Fake_Real_Data.csv    # Dataset
│-- requirements.txt      # Dependencies
│-- Dockerfile            # Docker configuration
│-- README.md             # Project documentation
```

---

## 🛠 Tech Stack
- **Python** (Data processing & ML model)
- **scikit-learn** (ML algorithms & TF-IDF vectorizer)
- **Pandas** (Data handling)
- **Streamlit** (Web interface)
- **Docker** (Optional container deployment)

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author
**Muskaan** - Software Engineer passionate about AI & real-world applications.
