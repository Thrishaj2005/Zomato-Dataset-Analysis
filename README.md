# Zomato-Dataset-Analysis
Restaurant Rating Prediction using Machine Learning and NLP with Zomato Dataset. Includes EDA, text preprocessing, TF-IDF vectorization, feature engineering, regression models, hyperparameter tuning.

## 📖 Overview
This project analyzes the Zomato Restaurant Dataset using Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and Machine Learning techniques. The goal is to understand restaurant characteristics, customer reviews, and predict restaurant ratings based on restaurant metadata and user reviews.

---

## 🎯 Objectives
- Analyze restaurant information and customer reviews.
- Perform data cleaning and preprocessing.
- Apply NLP techniques to process review text.
- Engineer and select important features.
- Build and evaluate machine learning models for restaurant rating prediction.

---

## 📂 Dataset

This project uses two datasets:

- **Zomato Restaurant names and Metadata.csv**
- **Zomato Restaurant reviews.csv**

The datasets contain information such as:

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
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- TextBlob

---

## 📊 Exploratory Data Analysis

The project includes:

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Feature Engineering
- Feature Selection

---

## 📝 Text Preprocessing

The customer reviews were preprocessed using:

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

Cross-validation and hyperparameter tuning were also performed.

---

## 📁 Repository Structure

```
Zomato-Dataset-Analysis/
│
├── README.md
├── Zomato_Project.ipynb
├── Zomato Restaurant names and Metadata.csv
└── Zomato Restaurant reviews.csv
```

---

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/Thrishaj2005/Zomato-Dataset-Analysis.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk textblob
```

3. Open **Zomato_Project.ipynb** in Jupyter Notebook or Google Colab and run all cells.

---

## 📈 Results

The project successfully predicts restaurant ratings using machine learning models. Feature engineering, NLP preprocessing, and TF-IDF vectorization improved the model's ability to learn meaningful patterns from restaurant reviews and metadata.

---

## 🔮 Future Scope

- Deep Learning-based rating prediction
- Restaurant recommendation system
- Sentiment analysis dashboard
- Web application deployment using Streamlit or Flask

---

## 👩‍💻 Author

**Thrisha J**

M.Sc. Data Science  
VIT Vellore

GitHub: https://github.com/Thrishaj2005

---

