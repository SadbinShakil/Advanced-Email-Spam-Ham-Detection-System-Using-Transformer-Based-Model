# 📧 Advanced Email Spam-Ham Detection System using Transformer-Based Models

A smart, feedback-driven system to detect email spam using traditional ML algorithms and a fine-tuned Transformer model — all wrapped in an interactive web app.

---

## 🚀 Features

- ✅ Fine-tuned **DistilBERT Transformer** for spam detection
- ⚙️ Compare models: Logistic Regression, Random Forest, Gradient Boosting
- 📈 Real-time predictions with confidence scores
- 🧠 Feedback system that **learns from users** over time
- 📊 Interactive visualizations using **Chart.js**
- 🌐 Flask-based web app with modern UI
- 🔐 Emails are processed **in-memory** to ensure privacy

---

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| **DistilBERT**      | 98.2%    | 97.8%     | 98.4%  | 98.1%    |
| Logistic Regression | 98.02%   | 97.5%     | 98.1%  | 97.8%    |
| Random Forest       | 98.60%   | 97.9%     | 98.6%  | 98.2%    |
| Gradient Boosting   | 97.08%   | 96.4%     | 97.0%  | 96.7%    |

---

## 🛠️ Installation & Running Locally

```bash
# Clone the repository
git clone https://github.com/SadbinShakil/Advanced-Email-Spam-Ham-Detection-System-Using-Transformer-Based-Model.git
cd Advanced-Email-Spam-Ham-Detection-System-Using-Transformer-Based-Model

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Run the Flask web application
python app.py
