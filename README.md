# 🎣 PhishCatcher

### Client-Side Defense Against Web Spoofing Attacks Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)

![XGBoost](https://img.shields.io/badge/XGBoost-99%25_Accuracy-brightgreen?style=for-the-badge)

![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn)

![BPUT](https://img.shields.io/badge/BPUT-Final_Year_Project_2026-red?style=for-the-badge)

---

## 🚀 Live Demo

👉 **[View GitHub Repository](https://github.com/abhipsapanigrahi86/PhishCatcher)**

---

## 📌 About The Project

**PhishCatcher** is a machine learning-based phishing URL detection system that classifies any given URL as **Safe** or **Phishing** in real-time — without inspecting the webpage content at all.

It works purely by analyzing the **structural features of the URL** — length, dots, hyphens, special characters, HTTPS usage, and more — to catch phishing attacks before the user even visits the site.

> 🏆 Achieved **99% accuracy** using XGBoost — the best among all tested models.

---

## 📊 Model Performance

| Algorithm | Accuracy | Precision | Recall | F1 Score |
|-----------|----------|-----------|--------|----------|
| SVM (Baseline) | 96% | 95.8% | 95.2% | 95.5% |
| Random Forest | 98% | 97.9% | 97.7% | 97.8% |
| **XGBoost ⭐** | **99%** | **98.9%** | **98.8%** | **98.9%** |

---

## ⚙️ How It Works

1. **URL Parsing** — Split URL into protocol, domain, path, query, and fragment using `urllib.parse`.

2. **Feature Extraction** — Extract 17+ structural signals from URL components.

3. **Normalization** — Scale all features to `[0,1]` using `MinMaxScaler`.

4. **Classification** — XGBoost model predicts whether the URL is **Legitimate** or **Phishing**.

---

## 🧪 Features Extracted

| Feature | Description |
|---------|-------------|
| URL Length | Longer URLs often indicate phishing |
| Dot Count | Excess dots can indicate subdomain abuse |
| Hyphen Count | Hyphens may be used to mimic legitimate brands |
| @ Symbol | Can cause the browser to treat preceding text as user information |
| HTTPS | Checks whether HTTPS is used |
| IP Address | Detects raw IP addresses in URLs |
| Query Params | Analyzes URL query parameters |
| Subdomain Depth | Measures the number of subdomain levels |
| Slash Count | Measures the depth of the URL path |

---

## 🛠️ Tech Stack

- **Language** — Python 3
- **ML Models** — SVM, Random Forest, XGBoost
- **Libraries** — scikit-learn, pandas, NumPy, Matplotlib, Seaborn
- **Dataset** — PhishTank (`phish_tank_storm.csv`)
- **Tools** — Jupyter Notebook, pickle, urllib.parse

---

## 🎓 Academic Information

> **B.Tech CSE · BPUT · Final Year Major Project · 2026**

> 🏅 **Project Score: 09/10 SGPA**

This project was developed as an academic project under BPUT university guidelines, focusing on the application of machine learning techniques to phishing URL detection.

---

## 👩‍💻 Author

**Sushri Abhipsa Panigrahi**

GitHub:  
https://github.com/abhipsapanigrahi86

---

## 📄 License

This project was built for academic and educational purposes under BPUT university guidelines.

---

### 🎣 PhishCatcher 2026