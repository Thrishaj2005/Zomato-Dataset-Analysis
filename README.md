# Zomato-Dataset-Analysis
Restaurant Rating Prediction using Machine Learning and NLP with Zomato Dataset. Includes EDA, text preprocessing, TF-IDF vectorization, feature engineering, regression models, hyperparameter tuning.

# 🍽️ Restaurant Rating Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict restaurant ratings using Machine Learning and Natural Language Processing (NLP) techniques. The project combines restaurant information with customer reviews from the Zomato dataset to analyze customer preferences and build accurate prediction models.

---

## 🎯 Business Objective
Restaurant ratings influence customer decisions and business growth. The objective of this project is to predict restaurant ratings based on restaurant details and customer reviews, helping restaurant owners improve their services and assisting customers in choosing restaurants.

---

## 📂 Dataset
The project uses two datasets:

- **Zomato Restaurant Dataset**
- **Restaurant Reviews Dataset**

These datasets include information such as:
- Restaurant Name
- Location
- Cuisines
- Cost for Two
- Timings
- Customer Reviews
- Reviewer Details
- Ratings

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- TextBlob
- TF-IDF Vectorizer
- Google Colab

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Missing Value Treatment
- Duplicate Removal
- Data Cleaning
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Feature Engineering
- Feature Selection

---

## 📝 Text Preprocessing

The review text was preprocessed using:

- Expand Contractions
- Lower Casing
- Remove Punctuation
- Remove URLs
- Remove Numbers
- Remove Stopwords
- Remove Extra Whitespaces
- Tokenization
- Lemmatization
- Part-of-Speech (POS) Tagging
- TF-IDF Vectorization

---

## ⚙️ Feature Engineering

New features were created, including:

- Cost Category
- Rating Category
- Date-based Features (Year, Month, Day)

Categorical variables were encoded using Label Encoding.

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Cross-validation and hyperparameter tuning were performed to improve model performance.

---

## 📈 Results

Among the implemented models, the Random Forest Regressor achieved the best overall performance with high prediction accuracy and strong generalization capability.

---

## 📁 Project Structure

```
Restaurant-Rating-Prediction/
│
├── Restaurant_Rating_Prediction.ipynb
├── README.md
├── requirements.txt
├── zomato.csv
├── reviews.csv
└── images/
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Restaurant-Rating-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

or upload the notebook to **Google Colab** and run all cells.

---

## 📌 Future Improvements

- Deep Learning models for rating prediction
- Sentiment Analysis
- Restaurant Recommendation System
- Web Application Deployment using Streamlit or Flask

---

## 👩‍💻 Author

**Thrisha J**

M.Sc. Data Science  
VIT Vellore

---

