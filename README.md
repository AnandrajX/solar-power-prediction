☀️ Solar Power Generation Prediction

A machine learning project that predicts solar power output using environmental and electrical parameters. The project focuses on understanding and implementing Linear Regression from scratch, followed by a comparison with Scikit-learn.

🚧 Status: In Development

🎯 Objective

The goal is to build a regression model capable of predicting solar panel power generation from factors such as:

* Solar irradiance
* Temperature
* Humidity
* Wind speed
* Panel voltage
* Panel current

The project emphasizes understanding the mathematics and implementation of Linear Regression, rather than simply using a pre-built model.

🧠 Approach

The project will follow this workflow:

Dataset
   ↓
Data Exploration
   ↓
Data Cleaning & Preprocessing
   ↓
Feature Engineering
   ↓
Linear Regression From Scratch
   ↓
Scikit-learn Comparison
   ↓
Model Evaluation
   ↓
Prediction & Visualization

🤖 Machine Learning

Linear Regression From Scratch

Implemented using NumPy, including:

* Weights and bias
* Predictions
* Mean Squared Error (MSE)
* Gradient Descent
* Parameter optimization

Scikit-learn

The custom implementation will be compared with:

from sklearn.linear_model import LinearRegression

📊 Evaluation

The models will be evaluated using:

* MAE — Mean Absolute Error
* MSE — Mean Squared Error
* RMSE — Root Mean Squared Error
* R² — Coefficient of Determination

Results will be added after model training.

🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* Git & GitHub

📁 Project Structure

solar-power-prediction/
├── data/
├── notebooks/
├── src/
├── models/
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md

🚀 Getting Started

Clone the repository:

git clone https://github.com/AnandrajX/solar-power-prediction.git
cd solar-power-prediction

Install dependencies:

pip install -r requirements.txt

Run the notebooks in the notebooks/ directory.

📈 Results

Results and visualizations will be added after completing model training.

🔮 Future Work

* Compare Ridge and Lasso Regression
* Experiment with Polynomial Regression
* Compare multiple ML algorithms
* Build an interactive Streamlit dashboard
* Integrate real solar-panel sensor data using ESP32

👨‍💻 Author

Anand Raj
Engineering Student | AI/ML Enthusiast

📄 License

This project is licensed under the MIT License.
