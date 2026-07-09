# Personalized Healthcare & Medicine Recommendation System

## Project Overview

The Personalized Healthcare & Medicine Recommendation System is a Machine Learning-based application designed to predict diseases based on patient symptoms and provide personalized medicine recommendations, precautions, and dietary suggestions.

The system aims to assist users by providing preliminary healthcare guidance and supporting early disease identification using data-driven approaches.

---

## Features

* Disease prediction based on symptoms
* Medicine recommendation based on predicted disease
* Precaution suggestions
* Dietary recommendations
* Data visualization and analysis
* High accuracy prediction using Machine Learning algorithms

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## Dataset

The project uses a symptom-based healthcare dataset containing:

* Patient symptoms as input features
* Disease names as target labels

Dataset files:

* `Training.csv`
* `Testing.csv`

---

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Label Encoding
5. Model Training
6. Disease Prediction
7. Medicine Recommendation
8. Performance Evaluation

---

## Machine Learning Model

The project uses the **Random Forest Classifier** for disease prediction because of its high accuracy and ability to handle multiple symptom features efficiently.

---

## Project Structure

```text
Personalized-Healthcare-Medicine-Recommendation-System/
│
├── Training.csv
├── Testing.csv
├── Disease_Prediction.ipynb
├── disease_model.pkl
├── label_encoder.pkl
├── requirements.txt
├── README.md
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Personalized-Healthcare-Medicine-Recommendation-System.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open:

   ```
   Healthcare_Recommendation_System.ipynb
   ```

3. Run all cells sequentially.

4. Enter symptoms to predict diseases and receive medicine recommendations.

---

## Example

### Input Symptoms

* Itching
* Skin Rash
* Nodal Skin Eruptions

### Predicted Disease

Fungal Infection

### Recommended Medicine

Clotrimazole Cream

### Precautions

* Keep the affected area clean and dry.
* Avoid sharing personal items.

### Diet Recommendation

* Consume a balanced diet.
* Stay hydrated.

---

## Results

The Random Forest model achieved high prediction accuracy on the testing dataset, making it suitable for healthcare recommendation applications.

---

## Future Enhancements

* Streamlit Web Application
* AI Healthcare Chatbot
* Hospital Recommendation System
* Appointment Booking Integration
* Personalized Dosage Recommendation

---

## Author

Priyanshi Patel
B.Sc IT (Hons.) Student
Data Science and Analytics Enthusiast
