# 🩺 Diabetes Prediction using Machine Learning

This project aims to predict whether a person is likely to develop diabetes based on a set of health parameters. The machine learning model uses historical medical data to make predictions, and the app can be deployed on **Streamlit** for easy accessibility and interaction.

## 🎯 Objective

The goal of this project is to build a machine learning model that predicts diabetes in individuals based on several features, such as:
- Glucose levels
- Blood pressure
- BMI (Body Mass Index)
- Age
- And more...

The model was trained on a dataset of patient health records, and predictions are made based on input parameters from the user.

## 📂 Files and Structure

```
diabetes-prediction/
├── diabetes_prediction_model.py # Python script for training and testing the model
├── diabetes_data.csv # Dataset used for training the model
├── app.py # Streamlit app for prediction interface
├── requirements.txt # Python dependencies for the project
└── README.md # Project documentation
```

## 🛠️ Tools & Technologies

- **Python**  
- **Streamlit**  
- **Pandas** (for data manipulation)  
- **Scikit-learn** (for machine learning models)  
- **Matplotlib & Seaborn** (for data visualization)  
- **Jupyter Notebooks** (for initial exploratory data analysis)

## 🚀 How to Run Locally

1. Clone this repository to your local machine:
```
git clone https://github.com/niskriti1/diabetes-prediction.git
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

3. Run the Streamlit app:
```
streamlit run streamlit.py
```

After running the command, the app will be available at `http://localhost:8501` in your web browser.

## 📊 Model Evaluation

The model was evaluated using common classification metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The model achieved a high accuracy in predicting diabetes status based on the input features.

## 🌐 Streamlit Deployment (Coming Soon)

The app will be deployed on Streamlit soon. Once deployed, it will be available at a public link.

## 💬 How to Use

- Input the required health parameters in the form (e.g., glucose levels, age, BMI, etc.).
- Click the "Predict" button to get the prediction on whether the person is likely to develop diabetes or not.

The model returns a prediction  based on the input data.

## 📚 Dataset

The dataset used for this project is available in the `diabetes_data.csv` file. It contains health records of individuals, with the target column being whether the individual has diabetes.

## 👨‍💻 Author

**Niskriti Paudel**  
📧 niskritipaudel@gmail.com  













