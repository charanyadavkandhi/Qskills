# 🚀 QSkills - Machine Learning Projects

Welcome to my **QSkills Machine Learning Projects Repository**.

This repository contains Machine Learning projects developed using **Python**, **Scikit-learn**, **Pandas**, **NumPy**, and **Matplotlib** as part of my AI & Machine Learning learning journey.

---

# 👨‍💻 Author

**Kandhi Charan Yadav**

🎓 B.Tech Computer Science and Engineering  
🏫 SR University, Warangal

- GitHub: https://github.com/charanyadavkandhi
- LinkedIn: https://www.linkedin.com/in/kandhicharanyadav/

---

# 🛠️ Technologies Used

- Python
- Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Natural Language Processing (NLP)
- Random Forest
- Naive Bayes
- TF-IDF Vectorization

---

# 📂 Projects

## 🏠 1. House Price Prediction Using Machine Learning

### 📌 Overview

This project predicts house prices using the California Housing Dataset.

A **Random Forest Regressor** is trained on housing data to estimate property prices based on multiple features such as income, house age, rooms, population, latitude and longitude.

### Dataset

California Housing Dataset

### Features

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

### Machine Learning Algorithm

- Random Forest Regressor

### Libraries Used

- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Model Performance

| Metric | Value |
|---------|-------|
| R² Score | **80.62%** |
| Mean Squared Error | **0.254** |

### Output

- Actual vs Predicted House Prices Graph
- Sample Price Prediction

---

## 📧 2. Spam Mail Detector Using Machine Learning

### 📌 Overview

This project classifies SMS messages as **Spam** or **Ham** using Natural Language Processing and Machine Learning.

The text is converted into numerical vectors using **TF-IDF Vectorization**, and a **Multinomial Naive Bayes** classifier predicts whether a message is spam.

### Dataset

SMS Spam Collection Dataset

### Machine Learning Algorithm

- Multinomial Naive Bayes

### NLP Techniques

- Text Cleaning
- TF-IDF Vectorization

### Libraries Used

- Pandas
- Scikit-learn
- Matplotlib

### Model Performance

| Metric | Value |
|---------|-------|
| Accuracy | **96.86%** |
| Precision | **97%** |
| Recall | **97%** |
| F1 Score | **97%** |

### Output

- Spam vs Ham Distribution
- Confusion Matrix
- Classification Report
- Custom Spam Prediction

---

# 📁 Repository Structure

```
Qskills
│
├── README.md
│
├── House Price Prediction-ML
│   ├── README.md
│   ├── house_price_prediction.py
│   ├── housing.csv
│   ├── Output.png
│   ├── actual_vs_predicted_prices.png
│   ├── House Price Prediction.pdf
│   └── House Price Prediction.docx
│
└── Spam Mail Detector-ML
    ├── README.md
    ├── spam_detector.py
    ├── spam.csv
    ├── Accuracy.png
    ├── Confusion Matrix.png
    ├── Spam vs Ham.png
    ├── Spam Mail Detector.pdf
    └── Spam Mail Detector.docx
```

---

# ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/charanyadavkandhi/Qskills.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run House Price Prediction

```bash
python house_price_prediction.py
```

### Run Spam Mail Detector

```bash
python spam_detector.py
```

---

# 📊 Results

## House Price Prediction

- Random Forest Regression
- R² Score: **80.62%**
- Mean Squared Error: **0.254**

---

## Spam Mail Detector

- Accuracy: **96.86%**
- Precision: **97%**
- Recall: **97%**
- F1 Score: **97%**

---

# 🎯 Learning Outcomes

Through these projects, I learned:

- Data Preprocessing
- Feature Engineering
- Regression Models
- Classification Models
- Natural Language Processing
- Model Evaluation
- Data Visualization
- Machine Learning Workflow

---

# 🔮 Future Improvements

- Deploy models using Flask or Streamlit
- Improve model accuracy
- Add interactive web interface
- Explore Deep Learning models
- Integrate real-time prediction APIs

---

# ⭐ Support

If you found this repository useful,

⭐ Star this repository.

Thank you for visiting!

---

## 📜 License

This project is intended for educational and learning purposes.
