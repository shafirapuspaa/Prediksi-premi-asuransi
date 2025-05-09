
# Prediksi Premi Asuransi (Insurance Charges Prediction)

## 1. Project Overview
Proyek ini bertujuan untuk memprediksi **biaya premi asuransi (`charges`)** berdasarkan atribut pelanggan seperti usia, jenis kelamin, status merokok, dan lainnya. Prediksi ini sangat berguna bagi perusahaan asuransi untuk:

- Menentukan premi secara adil dan akurat
- Mengidentifikasi faktor-faktor yang mempengaruhi besarnya premi
- Mengoptimalkan strategi underwriting dan pricing

### Key Objectives:
👉 [Lihat SHAP Force Plot interaktif](shap_force_plot_10.html)

- **Objektif 1:** Memprediksi biaya premi dengan berbagai model regresi  
- **Objektif 2:** Mengevaluasi performa masing-masing model untuk memilih yang terbaik

---

## 2. Data Sources

- **Dataset:** [Insurance Claim Prediction - Top ML Models (Kaggle)](https://www.kaggle.com/code/yasserh/insurance-claim-prediction-top-ml-models)

### Deskripsi Kolom:

| Kolom       | Tipe Data  | Deskripsi |
|-------------|------------|-----------|
| `age`       | Integer    | Usia pemegang polis (tahun) |
| `sex`       | Kategori   | Jenis kelamin (`male`, `female`) |
| `bmi`       | Float      | Body Mass Index |
| `children`  | Integer    | Jumlah anak tanggungan |
| `smoker`    | Kategori   | Status perokok (`yes`, `no`) |
| `region`    | Kategori   | Wilayah tempat tinggal |
| `charges`   | Float      | **Target:** Biaya premi asuransi (USD) |

---

## 3. Technologies Used

- **Bahasa Pemrograman:** Python
- **Library Machine Learning:**  
  - Scikit-learn  
  - XGBoost  
  - CatBoost  
  - Gradient Boosting  
- **Visualisasi:** Seaborn, Matplotlib
- **Pengelolaan Proyek:** Jupyter Notebook, Git

---

## 4. Summary of Findings

### 4.1 Business Insight

- Perokok membayar premi yang **jauh lebih tinggi** dibanding non-perokok.
- Usia dan BMI memiliki korelasi positif terhadap biaya premi.
- gender perempuan membayar premi lebih tinggi
- orang yang memiliki banyak anak memiliki premi lebih tinggi
- Wilayah tinggal tidak terlalu berpengaruh secara signifikan terhadap premi.

---

## 5. Models Used & Evaluation

### Model Regresi yang Digunakan:

- Linear Regression  
- K-Nearest Neighbors Regressor  
- Decision Tree Regressor  
- CatBoost Regressor  
- XGBoost Regressor  
- Gradient Boosting Regressor  
- Lasso Regression  
- Ridge Regression

### Metrik Evaluasi:

- Mean Squared Error (MSE)  
- Mean absolute error (MAE)
- Root Mean Squared Error (RMSE)  
- Mean absolute percentage error(MAPE)
- R² Score (Coefficient of Determination)


