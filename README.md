# 🚜 Bulldozer Price Prediction using Machine Learning

This project aims to predict the auction sale price of used bulldozers using historical data and regression techniques. Built during a learning phase, the notebook focuses on experimenting with real-world datasets, data preprocessing, feature engineering, and model evaluation.

> ⚠️ **Note**: This project was developed while learning data science concepts. Some parts may lack full documentation or modular design, but it demonstrates practical applications of regression models and data wrangling.

---

## 📊 Project Description

- **Dataset**: Sourced from the Blue Book for Bulldozers competition on Kaggle.
- **Goal**: Predict bulldozer sale prices based on features like model, usage hours, manufacturing year, and auction information.
- **Techniques**:
  - Exploratory Data Analysis (EDA)
  - Handling missing values
  - Feature engineering (date processing, categorical encoding)
  - Time series-aware validation
  - Model training and evaluation using `scikit-learn` regressors

---

## 🚀 Key Features

- Real-world tabular dataset for regression
- Preprocessing of temporal and categorical data
- Train-validation split considering time-dependency
- Baseline and advanced model evaluation
- Performance visualization

---


### 📁 Expected File Structure

When running this notebook, make sure your project files are arranged like this:

```bash
Bulldozer-Price-Prediction/
├── bulldozer_price_prediction.ipynb     # This Notebook
├── data/
│   ├── TrainAndValid.csv                # Required dataset file
│   └── Machine_Appendix.csv             # (Optional) additional data
```

> Make sure to place the dataset files inside a folder named `data/` in the same directory as the notebook. If you're using **Google Colab**, you can create this folder and upload the CSVs manually using `files.upload()`.

📦 Dataset Source: [Kaggle - Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers)

---

## 🧪 Usage Instructions

1. Clone the repository or upload notebook to Colab
2. Download dataset from Kaggle:

   * [Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers)
3. Upload `TrainAndValid.csv` to a folder named `data/`
4. Run the notebook

---

## ⚙️ Dependencies

Install with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 👨‍💻 Author

**Hassan Mroueh**
Master's Student – TU Dortmund University
This notebook reflects exploration and hands-on practice in machine learning for tabular data regression.

---

## 📌 Acknowledgments

* Kaggle: [Blue Book for Bulldozers Competition](https://www.kaggle.com/c/bluebook-for-bulldozers)

```

---

Would you like a `requirements.txt` file to match the notebook's imports?
```
