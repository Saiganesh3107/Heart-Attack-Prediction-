# Heart Attack Prediction using Machine Learning

This project aims to predict the likelihood of a heart attack in patients using various machine learning models. The dataset contains multiple features related to patient health metrics, and the goal is to classify whether a patient is at risk of a heart attack.

---

## 📊 Dataset

The dataset used in this project includes the following features:

- **Age**: Age of the patient
- **Sex**: Gender of the patient (1 = male; 0 = female)
- **cp**: Chest pain type (1-4)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol (in mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (1-3)
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- **target**: Presence or absence of heart disease (1 = presence; 0 = absence)

---

## ⚙️ Machine Learning Models Used

The following machine learning algorithms were implemented to predict heart attack risk:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **Naive Bayes**

---

## 📈 Performance Metrics

Each model's performance was evaluated using accuracy, precision, recall, and F1-score. The Random Forest Classifier achieved the highest accuracy among all models.

---

## 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Saiganesh3107/Heart-Attack-Prediction-
   cd Heart-Attack-Prediction-
   
2.Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```


3.Run the Jupyter notebook:
```bash
jupyter notebook heart_attack_prediction_using_different_ml_models.ipynb
``` 

---

## References

[Heart Disease UCI Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

[Machine Learning Algorithms Overview](https://scikit-learn.org/stable/supervised_learning.html)
