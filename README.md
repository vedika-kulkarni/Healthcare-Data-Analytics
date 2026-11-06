# 🫀 Healthcare Data Analytics & Cardiovascular Risk Prediction

An interactive healthcare analytics dashboard built using Python and Streamlit to explore patient health data, analyze clinical indicators, and predict cardiovascular risk using Machine Learning.

## 📌 Project Overview

Healthcare data contains valuable information that can help identify patterns and understand cardiovascular risk factors. This project provides an interactive dashboard to explore patient records, visualize clinical trends, analyze risk distributions, and generate cardiovascular risk predictions.

The application combines data analysis, machine learning, and interactive visualization in a single interface.

## ✨ Features

- **Executive Overview:** Summary of patient records and important healthcare indicators.
- **Patient Explorer:** Explore and filter patient information.
- **Risk Analysis:** Analyze cardiovascular risk patterns and distributions.
- **Clinical Analytics:** Visualize clinical attributes such as age, BMI, glucose, cholesterol, and blood pressure.
- **Cardiovascular Risk Prediction:** Enter patient details and obtain a model-based risk prediction.
- **Model Performance:** View machine-learning evaluation metrics.
- **Data Quality & Export:** Inspect dataset quality and export analytical data.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive dashboard |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Scikit-learn | Machine-learning algorithms |
| Plotly | Interactive visualizations |
| CSV | Healthcare dataset storage |

## 📂 Project Structure

```text
healthcare_project/
│
├── app.py
├── healthpulse_backend.py
├── healthcare_data.csv
└── README.md
```

- `app.py` – Streamlit dashboard and user interface.
- `healthpulse_backend.py` – Backend processing and model-related functionality.
- `healthcare_data.csv` – Healthcare dataset used by the application.
- `README.md` – Project documentation.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd healthcare_project
```

### 3. Install dependencies

```bash
pip install streamlit pandas numpy plotly scikit-learn
```

If your backend uses additional libraries, install those as well.

### 4. Run the application

```bash
streamlit run app.py
```

### 5. Open the dashboard

Streamlit will provide a local URL, usually:

```text
http://localhost:8501
```

## 📊 Dataset

The project uses a healthcare dataset containing patient-related attributes, including:

- Age and gender
- Body Mass Index (BMI)
- Blood glucose levels
- Cholesterol levels
- Systolic and diastolic blood pressure
- Heart rate
- Smoking status
- Physical activity
- Diabetes indicator
- Hypertension
- Cardiovascular risk label

The dataset contains synthetic patient records and is intended for academic and analytical demonstration.

## 🖥️ Dashboard Preview

Screenshots of the dashboard will be added here.

### Executive Overview
<img width="1464" height="792" alt="image" src="https://github.com/user-attachments/assets/cec16919-dca4-4bed-aeb4-7c828c5b0812" />


### Patient Explorer
<img width="1459" height="791" alt="image" src="https://github.com/user-attachments/assets/97bc0f45-6d37-413c-a226-10ec97b984e0" />


### Risk Analysis
<img width="1458" height="785" alt="image" src="https://github.com/user-attachments/assets/02930511-c1b1-435c-b8f6-75035d4a82e8" />


### Clinical Analytics
<img width="1464" height="789" alt="image" src="https://github.com/user-attachments/assets/1009fb96-f09f-4107-8d8c-bcb400aa1b08" />


### Cardiovascular Risk Prediction
<img width="1456" height="795" alt="image" src="https://github.com/user-attachments/assets/7dd55c36-bfc9-4324-a5b1-00d85c971e38" />


### Model Performance
<img width="1461" height="790" alt="image" src="https://github.com/user-attachments/assets/4a0ead4f-d563-4dfd-81c1-fafdf1c87031" />


## 🎯 Project Objectives

- Analyze healthcare data efficiently.
- Identify patterns in clinical indicators.
- Explore relationships between patient attributes and cardiovascular risk.
- Apply machine learning for risk classification.
- Present analytical results through an interactive dashboard.
- Make healthcare data exploration easier through visualizations.

## 🚀 Future Enhancements

- Integration with real-world healthcare datasets.
- Enhanced machine-learning models and explainability.
- Integration with distributed data processing.
- Improved patient data management.
- Deployment with secure database connectivity.

## ⚠️ Disclaimer

This project is developed for academic and educational purposes. The dataset contains synthetic patient information, and predictions should not be considered medical diagnoses or used as a substitute for professional medical advice.

## 👩‍💻 Author

**Vedika Kulkarni**

B.Tech – Computer Science and Engineering (AI & Data Science)

GitHub: [vedika-kulkarni](https://github.com/vedika-kulkarni)

---

⭐ If you find this project interesting, consider giving the repository a star!
