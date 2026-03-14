# 🎵 Music Recommendation System

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.44.1-red?style=for-the-badge&logo=streamlit)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.6.1-orange?style=for-the-badge&logo=scikit-learn)
![NLTK](https://img.shields.io/badge/NLTK-3.9.1-green?style=for-the-badge)

A content-based music recommendation engine that analyzes song features and suggests music tailored to your taste — wrapped in a clean, interactive Streamlit web app.

---

## 📸 Screenshots

> _Add your app screenshots here after running the app_
> 
> Example:
> ```
> screenshots/home.png
> screenshots/recommendations.png
> ```

---

## ✨ Features

- 🎧 **Content-Based Filtering** — recommends songs based on musical similarity
- 🧠 **NLP Processing** — uses NLTK to extract and clean song metadata features
- 📊 **Similarity Modeling** — powered by scikit-learn's cosine similarity
- ⚡ **Fast Load Times** — model serialized with joblib for instant startup
- 🖥️ **Interactive UI** — built with Streamlit, no frontend experience needed

---

## 🛠️ Tech Stack

| Tool | Version | Purpose |
|------|---------|---------|
| Python | 3.10+ | Core language |
| Streamlit | 1.44.1 | Web interface |
| scikit-learn | 1.6.1 | Similarity modeling |
| NLTK | 3.9.1 | NLP preprocessing |
| pandas | 2.2.3 | Data manipulation |
| joblib | 1.4.2 | Model serialization |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/music-recommendation-system.git
cd music-recommendation-system
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download NLTK data
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

### 4. Run the app
```bash
streamlit run app.py
```

Then open your browser at `http://localhost:8501` 🎉

---

## 📁 Project Structure
```
music-recommendation-system/
│
├── Music_RecommendationPSystem.ipynb  # Main notebook (EDA + model building)
├── app.py                             # Streamlit web app
├── requirements.txt                   # Python dependencies
├── model/                             # Saved model files (joblib)
└── README.md
```
