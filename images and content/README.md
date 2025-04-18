# 📧 Spam Email Classification using Machine Learning and Deep Learning

This project demonstrates a complete pipeline for classifying emails as **Spam** or **Ham** using both **Machine Learning** and **Deep Learning** techniques. It also includes a real-time **Streamlit web app** for end users to test the classifier with custom inputs.

---

## 🚀 Project Overview

Spam emails can be a threat to users and organizations, leading to security breaches, phishing attacks, and productivity loss. This project explores various approaches to detect spam using:
- Natural Language Processing (NLP)
- Classical Machine Learning Models
- Deep Learning Models (LSTM, GRU)
- A real-time prediction interface built with Streamlit

---

## 🧠 Models Used

| Model                   | Accuracy | Precision |
|------------------------|----------|-----------|
| Multinomial Naive Bayes| 97%      | 97%       |
| XGBoost                | 96%      | 95%       |
| LSTM                   | 95%      | 94%       |

---

## 📁 Project Structure

spam-classifier/ ├── data/ │ └── spam.csv ├── notebooks/ │ └── eda_and_modeling.ipynb ├── models/ │ └── model.pkl ├── app/ │ └── app.py ├── utils/ │ └── preprocessing.py ├── README.md ├── requirements.txt └── LICENSE


---

## 🛠️ Features

- ✅ Preprocessing pipeline with NLTK (tokenization, stopword removal, stemming)
- ✅ Feature extraction using TF-IDF
- ✅ Model comparison between 10+ classical ML algorithms
- ✅ Deep learning using LSTM and GRU models
- ✅ Real-time prediction using Streamlit
- ✅ Exported models using Pickle

---

## 🖥️ Streamlit App

Run the app locally using:
```bash
**streamlit run app.py**


📊 Dataset
Dataset used: spam.csv
5572 total messages
13.4% spam, 86.6% ham

🔮 Future Work
Use transformer-based models like BERT

Implement explainability tools like SHAP or LIME

Add email scraping for real-time classification

Support multilingual spam detection

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📜 License
This project is licensed under the MIT License.

📬 Contact
Created by Your Name – feel free to reach out!

Let me know if you want a version with your name and GitHub URL filled in!
