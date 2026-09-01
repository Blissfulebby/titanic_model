# 🚢 Titanic Survival Prediction

## 📌 About the Classwork

This is a machine learning classwork project foc
arning model can be integrated into a simple Flask web application to make predictions.

## 🎯 Objective

The objective of this classwork is to:

* Load and prepare the Titanic dataset
* Perform basic data preprocessing
* Train a Logistic Regression model
* Save the trained model using Joblib
* Build a Flask web application
* Use the trained model to make predictions

## 📊 Dataset

The Titanic dataset used in this classwork contains information about passengers aboard the Titanic.

For this exercise, the following features were selected:

* **Sex**
* **Fare**
* **Survived**

The `Survived` column is the target variable.

## 🧹 Data Preprocessing

The dataset was prepared by:

1. Selecting the required columns.
2. Removing missing values.
3. Converting the `Sex` column into numerical values:

   * Male → `0`
   * Female → `1`
4. Separating the features (`X`) from the target variable (`y`).

## 🤖 Machine Learning Model

A **Logistic Regression** classification model from Scikit-learn was used.

The model was trained using:

* Sex
* Fare

The trained model was saved as:

```text
titanic_model.pkl
```

using the `joblib` library.

## 🌐 Flask Web Application

A Flask application was created to allow users to enter passenger information and receive a survival prediction.

The application:

1. Accepts the passenger's sex and fare.
2. Converts the information into the format expected by the model.
3. Uses the saved model to make a prediction.
4. Displays either:

   * **Survived**
   * **Did not Survive**

## 📁 Project Structure

```text
titanic_model/
│
├── app.py                  # Flask web application
├── train_model.py          # Model training script
├── titanic_model.pkl       # Trained Logistic Regression model
├── requirements.txt        # Python dependencies
├── render.yaml             # Render deployment configuration
├── README.md               # Project documentation
│
├── Templates/
│   └── index.html          # Web application page
│
└── static/
    └── style.css           # Styling for the web page
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Flask
* HTML
* CSS
* Git & GitHub
* Render

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Blissfulebby/titanic_model.git
```

### 2. Open the project folder

```bash
cd titanic_model
```

### 3. Install the required packages

```bash
pip install -r requirements.txt
```

### 4. Run the Flask application

```bash
python app.py
```

### 5. Open the application

Open the local address displayed in your terminal, usually:

```text
http://127.0.0.1:5000
```

## 🚀 Deployment

The project includes a `render.yaml` configuration file for deployment on Render.

## 📚 What I Learned

This classwork helped me practice:

* Working with a real-world dataset
* Basic data preprocessing
* Encoding categorical data
* Training a classification model
* Saving and loading a machine learning model
* Building a Flask application
* Connecting a machine learning model to a web interface
* Using Git and GitHub for version control
* Deploying a Python application

## 👩🏽‍💻 Author

**Agatha Ebelechukwu Onwudiwe**

GitHub: https://github.com/Blissfulebby
