# ✈️ Flight Delay Prediction using Machine Learning

An end-to-end Machine Learning project that predicts flight delays using historical airline, airport, and weather data. The project compares multiple machine learning algorithms to identify the most accurate model for predicting whether a flight will be delayed.

---

## 📖 Overview

Flight delays affect millions of passengers every year and result in significant operational costs for airlines. This project aims to build a predictive model that estimates flight delays before departure by analyzing historical flight information and external factors such as weather conditions.

The project follows the complete Machine Learning pipeline, including data preprocessing, feature engineering, model training, evaluation, and prediction.

---

## 🚀 Key Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Multiple Machine Learning model comparison
- Hyperparameter tuning
- Model evaluation using multiple metrics
- Feature importance visualization
- Ready for deployment

---

## 📂 Dataset

The dataset consists of historical flight records containing operational and weather-related information.

### Features

- Airline
- Flight Number
- Origin Airport
- Destination Airport
- Scheduled Departure Time
- Scheduled Arrival Time
- Distance
- Day of Week
- Month
- Weather Conditions
- Temperature
- Visibility
- Wind Speed
- Humidity
- Previous Flight Delay

### Target Variable

| Value | Meaning |
|-------|---------|
| 0 | On Time |
| 1 | Delayed |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 🏆 Results

Among all the models, **XGBoost** achieved the best performance.

| Metric | Score |
|---------|--------|
| Accuracy | **89%** |
| ROC-AUC | **0.93** |
| F1-Score | **0.88** |

---

## 📁 Project Structure

```
Flight-Delay-Prediction/
│
├── data/
│   ├── raw_data.csv
│   └── processed_data.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── predict.py
│
├── models/
│   └── xgboost_model.pkl
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Flight-Delay-Prediction.git
```

Navigate to the project folder:

```bash
cd Flight-Delay-Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Train the model:

```bash
python src/train_model.py
```

Predict flight delays:

```bash
python src/predict.py
```

---

## 📈 Exploratory Data Analysis

The project includes several visualizations to better understand the dataset, including:

- Flight delay distribution
- Airline-wise delay analysis
- Monthly delay trends
- Correlation heatmap
- Feature importance plot
- ROC Curve
- Confusion Matrix

---

## 🎯 Future Enhancements

- Live flight delay prediction using Flight APIs
- Real-time weather API integration
- Deep Learning models (LSTM)
- Streamlit Dashboard
- Flask REST API
- Docker support
- Cloud deployment (AWS, Azure, or GCP)

---

## 📌 Applications

- Airline scheduling
- Airport operations
- Passenger travel planning
- Aviation analytics
- Logistics optimization

---

## 📸 Sample Output

```
Flight Status Prediction

Flight Number : AI-302
Origin         : Delhi
Destination    : Mumbai
Prediction     : Delayed
Probability    : 92%
```

---

## 👨‍💻 Author

**Shivam Tiwari**

M.Tech in Artificial Intelligence & Data Analytics  
National Institute of Technology Calicut

- GitHub: https://github.com/mavihs08
- LinkedIn: https://linkedin.com/in/shivam008

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates future improvements.

---

## 📄 License

This project is licensed under the MIT License.
