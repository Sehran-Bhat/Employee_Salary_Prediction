
# 💼 Employee Salary Prediction

A machine learning project that predicts employee salaries based on individual work-related attributes. This project includes both a Jupyter Notebook for model development and a fully interactive **Streamlit web app** for real-time salary prediction.

---

## 🚀 Overview

This project uses regression modeling to estimate an employee's salary based on three main features:
- **Years at Company**
- **Satisfaction Level**
- **Average Monthly Hours**

The project follows a complete machine learning pipeline from data preprocessing and model training to deploying a user-friendly web interface.

---

## 📁 Project Structure

```
employee-salary-prediction/
│
├── CAPSTONE_PROJECT_EMPLOYEE_SALARY_PREDICTION.ipynb   # Jupyter Notebook with model development
├── app.py                                              # Streamlit web application
├── model.pkl                                           # Trained regression model
├── scaler.pkl                                          # Feature scaler (StandardScaler/MinMax)
├── requirements.txt                                    # Python dependencies
└── README.md                                           # Project documentation
```

---

## 🧪 Features Used

- **Satisfaction Level** (`float`) – Employee's job satisfaction (0.0 to 1.0)
- **Average Monthly Hours** (`int`) – Number of hours worked per month
- **Years at Company** (`int`) – Total years of experience at the company

---

## 📊 Model Development

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) using `Seaborn` and `Matplotlib`
- Feature scaling using `StandardScaler`
- Model training using **Linear Regression**
- Performance metrics: `MAE`, `MSE`, `R² Score`

_All steps are documented in the Jupyter Notebook._

---

## 🌐 Web App

The **Streamlit app** allows users to:
- Enter custom values for satisfaction, hours, and experience
- Predict salary using the trained model
- Visualize inputs and predictions with interactive charts
- Compare predicted salary with average
- Receive alerts for high workload and low satisfaction

### 🖥️ To run the app locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/employee-salary-prediction.git
   cd employee-salary-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## 📷 App Preview

![App Screenshot](https://img.freepik.com/premium-photo/concept-artificial-satellites-viewed-from-space-forming-network-earth-providing-internet-services-3d-rendering_651547-1600.jpg)

---

## ✅ Requirements

- Python 3.x
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Plotly

_Install all dependencies using the `requirements.txt` file._

---

## 🙋‍♂️ Author

**Sehran Sajad Bhat**  
📧 your-email@example.com  
🌐 [GitHub](https://github.com/your-username) | [LinkedIn](#)

---

## 📌 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Acknowledgments

This capstone project was developed to apply machine learning concepts to real-world HR analytics, aiming to demonstrate the full deployment cycle of an ML model.
