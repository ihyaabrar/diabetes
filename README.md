# Prediksi Diabetes

Aplikasi **Streamlit** untuk memprediksi diabetes (**Sakit / Tidak Sakit**) dengan model **Decision Tree**, memakai
delapan fitur klinis ala dataset Pima Indians Diabetes.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

## Masukan

| Fitur | Keterangan |
|---|---|
| Pregnancies | jumlah kehamilan |
| Glucose | konsentrasi glukosa plasma 2 jam pada tes toleransi glukosa oral |
| BloodPressure | tekanan darah diastolik (mm Hg) |
| SkinThickness | tebal lipatan kulit trisep (mm) |
| Insulin | insulin serum 2 jam (mu U/ml) |
| BMI | indeks massa tubuh (kg/m²) |
| DiabetesPedigreeFunction | fungsi silsilah diabetes |
| Age | usia (tahun) |

## Isi repositori

| File | Isi |
|---|---|
| `app.py` | aplikasi Streamlit |
| `model_tree.pkl` | model Decision Tree terlatih |
| `Best Accuracy.ipynb` | notebook eksplorasi dan pelatihan model |
| `diabetes.csv`, `diabetes.xlsx` | dataset |

## Menjalankan

```bash
pip install -r requirements.txt
streamlit run app.py
```

> Proyek pembelajaran, bukan alat diagnosis medis.
