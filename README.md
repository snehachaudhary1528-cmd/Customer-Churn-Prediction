# 📉 Customer Churn Prediction

**A Machine Learning Project for Predicting Customer Churn**
*Built with Logistic Regression during my internship at LinuxWorld Informatics Pvt. Ltd.*

---

## 🎯 About the Project
This project predicts whether a customer will **churn (leave)** or **stay** based on their behavior and demographics. The goal is to help businesses **retain at-risk customers** by identifying them early and taking proactive actions (e.g., discounts, support, or personalized offers).

---

## 📊 Dataset
- **Source**: E-commerce customer data
- **Size**: 50,000+ records
- **Features**: Tenure, WarehousetoHome, NumberOfDeviceRegistered, PreferedOrderCat, SatisfactionScore, MaritalStatus, NumberOfAddress, Complain, DaySinceLastOrder, CashbackAmount
- **Target Variable**: Churn (0 = Stay, 1 = Leave)
- **Class Imbalance**: Fewer churners than non-churners

---

## 🛠️ Tech Stack
| Category | Tools/Libraries |
|----------|-----------------|
| Language | Python |
| Data | Pandas, NumPy |
| Visualization | Matplotlib |
| Model | Scikit-learn (Logistic Regression) |
| Environment | Jupyter Notebook |

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical features
- Applied StandardScaler for feature scaling

### 2. Exploratory Data Analysis (EDA)
- Visualized churn distribution
- Created correlation heatmaps
- Analyzed feature importance

### 3. Model Training
- Used **Logistic Regression** (80-20 train-test split)
- Adjusted decision threshold from **0.5 to 0.3** to improve recall for churn class

### 4. Evaluation
- **Default Threshold (0.5)**: Accuracy: **71.51%**
- **Tuned Threshold (0.3)**: Accuracy: **54.81%**, Recall for Churn Class: **90%** (Catches most at-risk customers)

---

## 🚀 How to Run

1. **Clone the repository**: `git clone https://github.com/snehachaudhary1528-cmd/Customer-Churn-Prediction.git`
2. **Install dependencies**: `pip install -r requirements.txt`
3. **Open and run the notebook**: `jupyter notebook Customer_Churn_Prediction.ipynb`

---

## 📁 Project Structure
- Customer_Churn_Prediction.ipynb
- Customer_Churn_Dataset.csv
- churn_model.pkl
- requirements.txt
- README.md

---

## 💡 Key Learnings
- **Class imbalance matters**: Accuracy alone can be misleading
- **Recall > Precision for churn**: Better to flag more at-risk customers than miss them
- **Logistic Regression is powerful**: Simple yet effective for binary classification

---

## 📬 Connect with Me
[LinkedIn](https://linkedin.com/in/sneha-chaudhary) | [GitHub](https://github.com/snehachaudhary1528-cmd)

⭐ **Star this repo if you found it helpful!**
