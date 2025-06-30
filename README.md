# Decisiontree_randomforests
# Task 5: Decision Trees and Random Forests - Heart Disease Prediction

## 📌 Objective
This project demonstrates how to apply tree-based machine learning models, specifically **Decision Trees** and **Random Forests**, for binary classification using the **Heart Disease dataset**.

---

## 🧰 Tools & Libraries
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- graphviz (for tree visualization)

---

## 🧪 Dataset
The dataset used is `heart.csv`, containing patient data to predict the presence (`1`) or absence (`0`) of heart disease.

---

## ✅ Steps Performed

1. **Data Preprocessing**
   - Loaded and split dataset into training and test sets.
   
2. **Decision Tree Classifier**
   - Trained on training data.
   - Visualized using `graphviz`.
   - Accuracy evaluated and overfitting controlled by adjusting `max_depth`.

3. **Random Forest Classifier**
   - Trained with 100 estimators.
   - Accuracy compared to Decision Tree.
   - Feature importances plotted.

4. **Cross-Validation**
   - 5-fold cross-validation applied to both models.

---

## 📊 Results

| Model           | Test Accuracy | CV Mean ± Std      |
|------------------|----------------|---------------------|
| Decision Tree    | 97.08%         | 99.71% ± 0.59%       |
| Random Forest    | 98.05%         | 99.41% ± 0.72%       |

---

## 📈 Visual Outputs
- `decision_tree_heart.png` – Tree structure
- `tree_depth_vs_accuracy.png` – Accuracy vs Depth
- `feature_importances.png` – Top predictors of heart disease

---

## ⚠️ Graphviz Setup
To visualize trees:
- Install from: https://graphviz.org/download/
- Ensure `dot` executable is added to system PATH.

---

## 🚀 Run the Code
```bash
python decision_tree_randomforests.py
[Aiml_task5.pdf](https://github.com/user-attachments/files/20977562/Aiml_task5.pdf)
