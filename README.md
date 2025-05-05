# 🧠 Task 7: Support Vector Machines (SVM) - Breast Cancer Classification

## 📌 Objective
Build a classification model using **Support Vector Machines (SVM)** to distinguish between malignant and benign tumors using the **Breast Cancer Wisconsin Dataset**.

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** `sklearn.datasets.load_breast_cancer()`
- **Type:** Binary classification (Benign = 1, Malignant = 0)

---

## 🧪 Workflow

### 1️⃣ Load & Explore Data
- Loaded dataset using `scikit-learn`.
- Converted to a Pandas DataFrame for easier manipulation and analysis.

### 2️⃣ Preprocessing
- Feature scaling using `StandardScaler`.
- Train-test split (80-20) using `train_test_split`.

### 3️⃣ Model Training
- Trained two SVM models using:
  - **Linear Kernel**
  - **RBF Kernel (Radial Basis Function)**

### 4️⃣ Evaluation Metrics
- **Accuracy**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**
- **Cross-validation (CV)** for model stability

### 5️⃣ Hyperparameter Tuning
- Tuned `C` and `gamma` using `GridSearchCV`.

### 6️⃣ Visualization
- Plotted decision boundaries using two selected features.
- Used contour plots to demonstrate the SVM’s margin and support vectors.

---

## 📊 Results

| Model         | Accuracy | Precision | Recall | F1-Score |
|---------------|----------|-----------|--------|----------|
| SVM (Linear)  | ~96%     | High      | High   | High     |
| SVM (RBF)     | ~98%     | Higher    | Higher | Higher   |

---

## ✅ Conclusion
- SVM is a powerful model for binary classification, especially with proper kernel and parameter tuning.
- The **RBF Kernel** gave better generalization performance than the Linear Kernel for this dataset.

---



