
# 🫀 Heart Disease Prediction using Machine Learning

This project predicts the likelihood of heart disease based on various health-related features. It uses supervised machine learning models with proper data preprocessing, visualization, and evaluation techniques. The highest accuracy of **90.49%** was achieved using the **K-Nearest Neighbors (KNN)** classifier.

---

## 📁 Project Overview

The pipeline includes:

1. Importing essential libraries  
2. Understanding and renaming dataset features  
3. Exploratory data analysis (EDA)  
4. Data preprocessing (encoding, scaling)  
5. Comprehensive data visualization  
6. Feature correlation analysis  
7. Train-test split  
8. Model training and evaluation

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **NumPy** – numerical operations  
- **Pandas** – data handling  
- **Matplotlib & Seaborn** – data visualization  
- **Scikit-learn** – ML models & evaluation  
- **Jupyter Notebook** – interactive coding (optional)

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📊 Visualizations

- BMI Distribution  
- Sex & Diabetic Population Distributions  
- Countplots: Smoking & Alcohol vs Heart Disease  
- Boxplot: BMI vs Heart Disease  
- Violinplot: Sleep Time vs Heart Disease  
- KDE Plots: PhysicalHealth & MentalHealth vs Heart Disease  
- Feature Correlation Heatmap  
- Correlation Distribution Plot  

---

## 🧠 Dataset Feature Highlights

- `BMI`: Body Mass Index  
- `Smoking`: Smoking status  
- `AlcoholDrinking`: Alcohol consumption habit  
- `PhysicalHealth`, `MentalHealth`: Number of unhealthy days  
- `SleepTime`: Average sleep hours  
- `GenHealth`: General health condition  
- `AgeCategory`, `Race`, `Sex`: Demographic info  
- `HeartDisease`: ⚠️ Target variable  

---

## 🤖 Model Performance

| Model                  | Accuracy   |
|------------------------|------------|
| K-Nearest Neighbors    | **90.49%** |
| Decision Tree Classifier | 86.00%    |

✅ The KNN model demonstrated the best overall performance.

---

## 🧪 How to Run

Clone the repository:

```bash
git clone https://github.com/mehedihasanmir/-Heart-Disease-Prediction-using-Machine-Learning.git
cd heart-disease-prediction
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook or script:

```bash
jupyter notebook
# or
python heart_disease_model.py
```

---

## 🔮 Future Enhancements

- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)  
- Add more ML algorithms (e.g., Random Forest, XGBoost)  
- Model explainability with SHAP or LIME  
- Deploy using Streamlit or Flask  

---

## 🙏 Acknowledgments

Special thanks to the open-source community and dataset providers.

---

## 👤 Author

**Your Name**  
📧 mdmehedihassanmir@gmail.com
🌐 [GitHub Profile](https://github.com/mehedihasanmir)
