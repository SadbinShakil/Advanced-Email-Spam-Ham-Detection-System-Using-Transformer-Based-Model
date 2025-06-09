<div align="center">

# 📧 Advanced Email Spam-Ham Detection System  
### 💡 Powered by Transformers, Fine-Tuning, and Real-Time Feedback

<img src="https://img.shields.io/badge/Transformer-DistilBERT-green?style=flat-square"/>
<img src="https://img.shields.io/badge/Framework-Flask-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Language-Python3.8-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/License-MIT-purple?style=flat-square"/>

</div>

---

## 🎥 Live Demo Preview

> 📽️ Here's a walkthrough of the interactive web app in action:

![Demo](demo.gif)  
<!-- Replace demo.gif with your actual GIF file uploaded to the repo -->

---

## 🚀 Features at a Glance

- 🤖 **Fine-tuned DistilBERT** spam detector
- 🧠 Real-time predictions with **confidence scores**
- 🔄 Continuous **learning from user feedback**
- 📊 Compare: Logistic Regression, Random Forest, Gradient Boosting
- 🌐 Sleek Flask web interface with interactive charts (Chart.js)
- 🔒 Emails processed **in-memory** for privacy

---

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| **DistilBERT**      | 98.2%    | 97.8%     | 98.4%  | 98.1%    |
| Logistic Regression | 98.02%   | 97.5%     | 98.1%  | 97.8%    |
| Random Forest       | 98.60%   | 97.9%     | 98.6%  | 98.2%    |
| Gradient Boosting   | 97.08%   | 96.4%     | 97.0%  | 96.7%    |

---

## 💻 Screenshots

<p float="left">
  <img src="screenshots/predict.png" width="45%" />
  <img src="screenshots/chart.png" width="45%" />
</p>

_screenshots _

---

## 🛠️ Installation Guide

```bash
# 1. Clone the repo
git clone https://github.com/SadbinShakil/Advanced-Email-Spam-Ham-Detection-System-Using-Transformer-Based-Model.git
cd Advanced-Email-Spam-Ham-Detection-System-Using-Transformer-Based-Model

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py
