# Fashion Forward Forecasting

**StyleSense** is a rapidly growing online women's clothing retailer, known for its trendy and affordable fashion. With the recent surge of new customers, StyleSense has encountered a new challenge: a backlog of product reviews with missing data.  

While customers continue to leave valuable feedback in the form of review text, they don’t always indicate whether they would recommend the product. The goal of this project is to build a **machine learning pipeline** that can predict whether a customer would recommend a product based on numerical, categorical, and text features from the review data.

---

## 🚀 Getting Started

Use the provided dataset to train and evaluate your prediction model. Your pipeline should:

- Handle **numerical**, **categorical**, and **text** features appropriately.  
- Incorporate proper preprocessing steps for each feature type.  
- Train a classifier to predict product recommendation.  
- Evaluate model performance using appropriate metrics.  

---

## 📦 Dependencies

The project requires the following libraries:

- [scikit-learn](https://scikit-learn.org/stable/)  
- [pandas](https://pandas.pydata.org/)  
- [spaCy](https://spacy.io/)  
- [Jupyter Notebook](https://jupyter.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

---

## 📦 Project Workflow

Exploratory Data Analysis (EDA)

- Distribution of numeric features (Age, Feedback Count).

- Missing value analysis.

- Word frequency clouds for reviews.

Pipeline & Preprocessing

- Numeric: imputation (median) + scaling.

- Categorical: imputation (most frequent) + encoding.

- Text: TF-IDF, character counts.

Model Training & Evaluation

- Base model: RandomForestClassifier.

- Evaluation: accuracy score.

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
python -m pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

---

## 📊 Results

Accuracy: ~ 0.87

---

## License

[License](LICENSE.txt)
