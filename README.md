# Ford Car Price Prediction 🚗

A Machine Learning project that predicts the selling price of Ford cars using **Linear Regression** based on vehicle specifications and features.

## 📊 Project Overview

- **Dataset:** Ford Used Car Dataset
- **Records:** 17,966
- **Features:** 8 input features
- **Target Variable:** `price`
- **Algorithm:** Linear Regression
- **Problem Type:** Supervised Learning – Regression

## 🔍 Exploratory Data Analysis (EDA)

Performed data analysis and visualization to understand the relationship between car features and prices.

- Price distribution analysis
- Correlation heatmap
- Price comparison by year, model, transmission and fuel type
- Mileage and engine size analysis

## ⚙️ Data Preprocessing

- Separated independent and dependent variables.
- Applied One-Hot Encoding to categorical features.
- Applied Label Encoding for comparison.
- Used StandardScaler for feature scaling.
- Split the dataset into training (67%) and testing (33%) sets.

## 🤖 Model Performance

Compared Linear Regression using two encoding techniques.

| Encoding Technique | R² Score | Adjusted R² |
|---|---:|---:|
| One-Hot Encoding | 83.97% | 83.87% |
| Label Encoding | 73.10% | 73.07% |

**Best Result:** One-Hot Encoding achieved an R² score of approximately 83.97%.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 How to Run

1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. Ensure the dataset is available at `../datasets/ford.csv` relative to the notebook.
4. Open `ford.ipynb` in Jupyter Notebook.
5. Run all cells.

## 📁 Project Structure

```text
Ford-Car-Price-Prediction/
│
├── ford.ipynb
├── datasets/
│   └── ford.csv
└── README.md
```

## 🎯 Conclusion

The project demonstrates how exploratory data analysis, categorical encoding, feature scaling and Linear Regression can be used to predict used Ford car prices. One-Hot Encoding produced better results than Label Encoding in this experiment.
