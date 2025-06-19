# Hotel Reservation Cancellation Prediction

This project aims to predict whether a hotel booking will be canceled using machine learning techniques. By analyzing key features like booking details, customer behavior, and lead time, we identify patterns that indicate the likelihood of cancellation.

## 🚀 Key Features

- **EDA & Visualization**: 
  - Distribution analysis of key variables
  - Correlation heatmaps and cancellation trends

- **Data Preprocessing**:
  - Handling missing values, outlier treatment
  - Feature encoding and scaling

- **Modeling**:
  - Classification using Random Forest, XGBoost, Logistic Regression
  - Hyperparameter tuning and performance comparison

- **Evaluation**:
  - Confusion Matrix, Accuracy, Precision, Recall, F1-score
  - ROC-AUC and cross-validation

```markdown
## 📁 Project Structure
├── data/                     # Raw and processed datasets
├── code/                    # Python scripts or notebook files
│   └── hotel_cancellation.ipynb
├── results/                 # Model outputs and plots
├── requirements.txt         # Python dependencies
├── readme.md                # Project overview (this file)
```

## 📦 Setup

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

## 📊 Results Highlights
	•	Achieved over 90% accuracy using ensemble methods like Random Forest.
	•	Identified key predictors: lead_time, booking_changes, customer_type, deposit_type.
	•	Provided actionable insights for revenue management and overbooking strategy.


📌 Author

Amrita Moyade