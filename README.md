# 🌾 Crop Yield Prediction using Machine Learning

This project builds a machine learning pipeline to predict agricultural crop yield (in tons per hectare) using environmental and farm-related data. It demonstrates end-to-end preprocessing, modeling, and evaluation using a **Random Forest Regressor**.

---

## 📊 Dataset

The dataset contains synthetic agricultural data sourced from Kaggle, including:

- **Categorical features**: Region, Soil Type, Crop, Weather, Fertilizer, Irrigation  
- **Numerical features**: Rainfall, Temperature, Days to Harvest  
- **Target**: `Yield_tons_per_hectare`

📁 `data/crop_yield.csv`

---

## 🔧 Technologies Used

- Python, Jupyter Notebook  
- Pandas, NumPy, Seaborn, Matplotlib  
- Scikit-Learn (Pipelines, OneHotEncoding, RandomForestRegressor)

---

## 🧪 Model Workflow

1. **Preprocessing**
   - Scales numerical features
   - Encodes categorical features using OneHotEncoder
   - Pipeline built using `ColumnTransformer`

2. **Model**
   - Random Forest Regressor (with default params)

3. **Evaluation**
   - Mean Absolute Error (MAE)
   - R² Score
   - Feature Importance plot

---

## 📈 Results

| Metric | Score |
|--------|-------|
| MAE    | ~ (actual value from notebook) |
| R²     | ~ (actual value from notebook) |

> Random Forest performs robustly and gives insights into the most influential features affecting yield.

---

## 🗂 Project Structure

```
Crop_Yield_Prediction/
├── data/
│   ├── crop_yield.csv
├── notebook/
│   ├── Crop_Yield_Prediction.ipynb
├── requirements.txt      
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/crop-yield-prediction.git
cd crop-yield-prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook notebook/Crop_Yield_Prediction.ipynb
```
---

## 📌 Acknowledgements

- [Kaggle Dataset Source](https://www.kaggle.com/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)

---

## 📄 License

MIT License
## 📌 Acknowledgements
 Kaggle Dataset Source
 Scikit-Learn Documentation
