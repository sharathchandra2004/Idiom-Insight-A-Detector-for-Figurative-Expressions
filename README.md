# 💡 Idiom Insight: A Detector for Figurative Expressions

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)
![NLP](https://img.shields.io/badge/NLP-Figurative_Expressions-purple)

> 🎯 A smart and simple tool to detect idioms and figurative expressions from any paragraph using NLP and fuzzy matching.

---

## 🚀 Project Overview

**Idiom Insight** is a web-based application that:
- 📚 Accepts a paragraph as input  
- 🔍 Detects idiomatic expressions using **FuzzyWuzzy’s partial string matching**
- 🧠 Explains their meanings  
- 📌 Displays the sentence where each idiom was found  

This is particularly useful for:
- Language learners 🧑‍🎓  
- Teachers 🧑‍🏫  
- Writers ✍️  
- NLP enthusiasts 🤖

---

## 🛠️ Tech Stack

- **Python** 🐍
- **Streamlit** for building the interactive UI
- **NLTK** for sentence tokenization
- **FuzzyWuzzy** for approximate idiom detection
- **Pandas** for data handling
- **CSV** idiom database with meanings

---



## 🔧 Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/idiom-insight.git
cd idiom-insight

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Streamlit app
streamlit run app.py
