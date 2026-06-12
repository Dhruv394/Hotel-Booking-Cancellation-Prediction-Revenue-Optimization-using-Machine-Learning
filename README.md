# Hotel Booking Cancellation Prediction and Revenue Optimization using Machine Learning

## 📌 Project Overview

Hotel booking cancellations create major revenue loss and occupancy planning issues for hotels. This project focuses on predicting booking cancellations using Machine Learning and analyzing customer booking behavior to help hotels improve revenue management and business strategies.

The project includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Model Building
* Revenue Loss Analysis
* Model Performance Comparison

The final model helps hotels identify high-risk bookings and reduce cancellation-related losses.

---

## 📊 Dataset Information

* Dataset Size: **119,390 hotel booking records**
* Final Cleaned Records: **87,229**
* Features: **34 columns**
* Dataset includes:

  * Booking details
  * Customer information
  * Lead time
  * ADR (Average Daily Rate)
  * Market segment
  * Deposit type
  * Special requests
  * Cancellation status

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Google Colab

---

## 🔍 Key Steps Performed

### 1. Data Cleaning & Preprocessing

* Removed ~31K duplicate records
* Handled missing values
* Removed invalid guest records
* Treated ADR outliers
* Converted data types

### 2. Feature Engineering

Created new useful features:

* `total_guests`
* `total_nights`
* `revenue`

### 3. Exploratory Data Analysis

Performed detailed business analysis including:

* Hotel type distribution
* Cancellation trends
* Lead time analysis
* Seasonal booking trends
* Revenue leakage analysis
* Market segment behavior
* Deposit type impact
* Repeat guest analysis

---

## 💡 Business Insights

* City Hotels receive more bookings than Resort Hotels
* Longer lead time increases cancellation probability
* No-deposit bookings show higher cancellation rates
* July and August are peak booking months
* Repeat customers are very low
* Around **33% revenue loss** occurs due to booking cancellations

---

## 🤖 Machine Learning Models Used

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 79.81%   |
| Decision Tree       | 80.35%   |
| Random Forest       | 84.88%   |
| XGBoost             | 85.35%   |

### 🏆 Best Model

**XGBoost** achieved the best performance with:

* Accuracy: **85.35%**
* ROC-AUC Score: **0.92**

---

## 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Curve
* Confusion Matrix

---

## 📉 Revenue Optimization

The project also analyzes:

* Lost revenue due to cancellations
* Customer booking behavior
* Risk factors affecting occupancy

This can help hotels:

* Improve cancellation prediction
* Reduce revenue leakage
* Optimize pricing strategies
* Improve occupancy planning

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Deployment using Streamlit/Flask
* Real-time cancellation prediction system
* Integration with hotel booking platforms
* Deep Learning implementation

---

## 📂 Project Structure

```bash
├── hotel_booking_prediction.ipynb
├── dataset/
├── visualizations/
├── models/
├── README.md
```

---

## ▶ How to Run the Project

1. Clone the repository

```bash
git clone <your-github-repo-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

3. Run the notebook

```bash
jupyter notebook
```

---

## 🎯 Conclusion

This project demonstrates how Machine Learning can help the hospitality industry predict booking cancellations and reduce revenue loss. Among all models, XGBoost delivered the best predictive performance and proved highly effective for cancellation prediction.

---

## 👨‍💻 Author

Dhruv Bhatia
Data Science & AI Enthusiast
