# Wine-Quality-Prediction-Using-Machine-Learning-
This project predicts the quality of wine (Good, Average, or Bad) based on its physicochemical properties using  machine learning algorithms. The model is trained and evaluated on Wine Quality dataset, and achieves high accuracy through ensemble techniques and proper feature engineering.

#🍷 Wine Quality Prediction using Machine Learning

A machine learning project that predicts the quality of wine (Good, Average, or Bad) based on its physicochemical properties. This project showcases end-to-end implementation — from data preprocessing and feature selection to model tuning and final prediction — with an interactive input system for real-time testing.

---

## 1) What This Project Does
- Classifies wine quality into **Good**, **Average**, or **Bad**
- Uses **ensemble models** (Random Forest + Gradient Boosting) for high accuracy
- Implements **SMOTE** to handle class imbalance
- Applies **Recursive Feature Elimination (RFE)** for optimal feature selection
- Combines model predictions using **weighted probability ensemble**
- Accepts **custom user input** through the terminal for live predictions
- Provides **class-wise prediction probabilities** and friendly feedback

---

## 2) Techniques & Tools Used
- Python, Pandas, NumPy
- Scikit-learn, imbalanced-learn
- Random Forest, Gradient Boosting
- GridSearchCV for hyperparameter tuning
- RFE for feature selection
- SMOTE for oversampling
- Jupyter Notebook for development and testing
- Matplotlib & Seaborn for visualizations

---

## 3) Key Highlights
- Achieved over **99% accuracy** on test data using ensemble learning
- Real-time prediction interface for user inputs via terminal
- Visualized class distribution before and after SMOTE
- Saved models for future reuse with `joblib`

---

## 4) How to Use
1. Clone this repository
2. Open the Jupyter Notebook or run the `.py` script
3. Enter custom wine feature values when prompted
4. View predicted wine quality and probability breakdown

---

## 5) Sample Input Features
Only essential features are taken via input — the rest are set to zero for simplicity.

---

## 6) Status
Academic Project (Sept 2024–Dec 2024)  
Developed as part of Course Requirement

---

## 7) Author
**Sindhu R**  
📧 sindhu.ramapriya@gmail.com  


---

⭐ If you find this project helpful, feel free to give it a ⭐!

