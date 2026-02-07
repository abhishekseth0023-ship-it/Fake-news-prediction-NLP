# Fake News Prediction Using NLP

## 📌 Project Overview
This project implements a **Fake News Prediction system** using **Natural Language Processing (NLP)** and **Machine Learning**.  
The objective is to classify news articles as **Fake** or **Real** based on their textual content.

The model is trained on labeled news data and evaluated on unseen test data.

---

## 📂 Dataset
The project uses two datasets:
- `Fake.csv`
- `True.csv`

Each file is approximately **51 MB**.

Due to GitHub size limitations, the datasets are **not included** in this repository.  
They can be obtained from publicly available fake news datasets (Kaggle).

---

## 🧠 Methodology
1. Loaded fake and real news datasets
2. Assigned labels and merged datasets
3. Converted text data into numerical features using **TF-IDF Vectorization**
4. Trained a **Random Forest Classifier**
5. Evaluated model performance on test data

---

## 📊 Results
- **Model Used:** Random Forest Classifier  
- **Test Accuracy:** **94.394%**

The model shows strong performance in distinguishing fake and real news articles.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (TF-IDF)

---

## 📁 Project Structure
Fake-news-prediction-NLP/
│── Fake News Prediction Using NLP.ipynb
│── README.md
│── .gitignore
│── LICENSE

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/abhishekseth0023-ship-it/Fake-news-prediction-NLP.git

2. Place Fake.csv and True.csv in the appropriate local directory
3. jupyter notebook "Fake News Prediction Using NLP.ipynb"
4. Update dataset paths if required and run the notebook
