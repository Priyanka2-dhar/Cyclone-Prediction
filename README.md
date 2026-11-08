# 🌪️ Cyclone Formation Prediction System

## 📌 Project Overview

The **Cyclone Formation Prediction System** is a machine learning-based project designed to predict the possibility of cyclone formation using atmospheric and oceanographic parameters.

The project analyzes environmental factors such as sea surface temperature, atmospheric pressure, humidity, wind shear and vorticity to identify conditions associated with cyclone formation.

The objective is to explore how machine learning algorithms can support early identification of potential cyclone formation and contribute to weather-related risk assessment.

## 🎯 Objectives

- Analyze atmospheric and oceanographic conditions associated with cyclone formation.
- Build machine learning models to classify potential cyclone formation.
- Compare the performance of different classification algorithms.
- Develop a simple web interface to make predictions through user input.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn, XGBoost |
| Algorithms | XGBoost, Support Vector Machine (SVM), Decision Tree |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Backend | Flask |
| Frontend | HTML, CSS, JavaScript |
| Development Environment | Jupyter Notebook, VS Code |

## 📊 Dataset Features

The model uses the following environmental parameters:

| Feature | Description |
|---|---|
| Sea Surface Temperature | Temperature of the ocean surface |
| Atmospheric Pressure | Air pressure in the atmosphere |
| Humidity | Amount of moisture present in the air |
| Wind Shear | Variation in wind speed or direction with altitude |
| Vorticity | Measure of atmospheric rotation |
| Latitude | Geographical position |
| Ocean Depth | Depth of the ocean |
| Proximity to Coastline | Distance from the coastline |

**Target Variable:** Cyclone Formation (classification target indicating whether cyclone formation is predicted).

## ⚙️ Methodology

The project follows these major steps:

1. **Data Collection:** Obtained a dataset containing atmospheric and oceanographic parameters.
2. **Data Preprocessing:** Prepared the dataset for machine learning by handling missing values and preparing relevant features.
3. **Exploratory Data Analysis:** Examined feature distributions and relationships using data visualization techniques.
4. **Model Development:** Implemented three machine learning algorithms:
   - XGBoost
   - Support Vector Machine (SVM)
   - Decision Tree
5. **Model Evaluation:** Compared model performance using classification accuracy.
6. **Web Application Development:** Integrated the prediction model with a Flask-based application and created a user interface using HTML, CSS and JavaScript.

## 🤖 Machine Learning Models

The following algorithms were implemented and compared:

- **XGBoost:** A gradient boosting algorithm used for classification.
- **Support Vector Machine (SVM):** A supervised learning algorithm used to classify data.
- **Decision Tree:** A tree-based algorithm that makes predictions using decision rules.

### Model Performance

The XGBoost model achieved a reported accuracy of **98%** during project evaluation.

*Note: This is the accuracy reported during the project. The evaluation split and other metrics should be documented alongside it for a complete performance assessment.*

## 💻 Application Features

- User-friendly web interface.
- Input fields for environmental parameters.
- Machine learning-based cyclone formation prediction.
- Flask backend for connecting the trained model with the web interface.
- Prediction results displayed to the user.

## 📁 Project Structure

```text
Cyclone-Project/
│
├── app.py                  # Flask application
├── templates/
│   └── index.html          # Web interface
├── static/
│   ├── style.css           # Styling
│   └── script.js           # Frontend functionality
│
├── model/
│   └── model.pkl           # Trained model (if included)
│
├── dataset/                # Dataset (if included)
├── notebooks/              # Model development notebooks
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

*The structure above is illustrative. Adjust the filenames and folders to match the actual repository.*

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Priyanka2-dhar/Cyclone-Project.git
```

### 2. Navigate to the project directory

```bash
cd Cyclone-Project
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask application

```bash
python app.py
```

### 5. Open the application

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 🔮 Future Improvements

- Integrate real-time meteorological data from reliable weather sources.
- Evaluate the models using precision, recall, F1-score and ROC-AUC.
- Improve prediction reliability using larger and more diverse datasets.
- Develop a more interactive dashboard for visualizing prediction results.
- Explore deployment on a cloud platform.

## ⚠️ Disclaimer

This project is developed for educational and research purposes. Its predictions should not be used as a substitute for official meteorological forecasts or cyclone warnings issued by authorized weather agencies.

## 👩‍💻 Contributors

Developed as a collaborative machine learning project by a team of four members.

**Project Domain:** Machine Learning | Weather Prediction | Classification

**Developed using:** Python, XGBoost and Flask
