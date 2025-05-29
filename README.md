# DL_DIABETES.PREDICTION

## 📊 Project Overview
This project uses Deep Learning techniques to predict the likelihood of diabetes in patients based on diagnostic data. The model incorporates regularization strategies such as L1, L2, dropout, and early stopping to improve accuracy and generalization.

## 🧠 Techniques Used
- Artificial Neural Networks (ANN)
- L1 and L2 Regularization
- Dropout Layers
- Early Stopping
- Data Normalization

## 📁 Project Structure
```
DL_DIABETES.PREDICTION/
├── edit/                    # Notebooks and scripts
│   ├── diabetes_prediction.ipynb
│   └── README.md            # ← Paste this file here
├── data/                    # Dataset (diabetes.csv)
├── models/                  # Saved models
├── results/                 # Evaluation outputs
└── requirements.txt         # Python dependencies
```

## 🚀 How to Run
1. **Clone the repository**
```bash
git clone https://github.com/pranjalshrivastavaa/DL_DIABETES.PREDICTION.git
cd DL_DIABETES.PREDICTION/edit
```

2. **Install dependencies**
```bash
python -m venv venv
source venv/bin/activate        # For Windows: venv\Scripts\activate
pip install -r ../requirements.txt
```

3. **Run the Notebook**
Open `diabetes_prediction.ipynb` in Jupyter Notebook or any IDE like VS Code.

## 📉 Dataset
Uses the Pima Indians Diabetes Dataset with the following features:
- Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin
- BMI, DiabetesPedigreeFunction, Age
- Target: Outcome (0 = No diabetes, 1 = Diabetes)

## 📈 Model Evaluation
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score
- Loss/Accuracy Curves

## 🛠 Regularization Techniques
- **L1/L2 Regularization**: Reduces model complexity by penalizing large weights.
- **Dropout**: Prevents overfitting by randomly disabling neurons.
- **Early Stopping**: Stops training once validation loss stagnates.

## 👩‍🔬 Author
**Pranjal Shrivastava**  

---
