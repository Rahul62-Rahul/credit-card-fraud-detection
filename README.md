# Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset is highly imbalanced, requiring techniques like undersampling or SMOTE to handle class imbalance.

## 📊 Dataset Details
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Features:**
  - `V1, V2, ..., V28` (Anonymized principal components)
  - `Amount` (Transaction amount, scaled)
  - `Class` (0 = Normal, 1 = Fraud)

## 🛠️ Technologies Used
- Python (Pandas, NumPy, Scikit-Learn, Imbalanced-learn)
- Logistic Regression & Random Forest
- Jupyter Notebook

## 🔧 Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone <your-github-repo-url>
   cd credit-card-fraud-detection
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**
   ```sh
   jupyter notebook
   ```
4. **Train & Evaluate the Model**
   - Open `fraud_detection.ipynb`
   - Run all cells

## 🎯 Model Performance
| Metric      | Logistic Regression | Random Forest |
|------------|---------------------|--------------|
| Accuracy   | 95%                 | 98%          |
| Precision  | 90%                 | 96%          |
| Recall     | 85%                 | 93%          |
| F1-Score   | 87%                 | 94%          |

## 📂 File Structure
```
📁 credit-card-fraud-detection
├── 📄 fraud_detection.ipynb   # Jupyter Notebook with code
├── 📄 fraud_detection_model.pkl   # Saved Machine Learning model
├── 📄 README.md   # Project documentation
└── 📂 data
    ├── creditcard.csv  # Original dataset
```

## 📜 License
This project is for educational purposes only.

## 📞 Contact
For any queries, reach out at [your-email@example.com].

