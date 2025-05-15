# 👻 Ghouls, Goblins, and Ghosts (Boo!) Classification using Random Forest + GridSearchCV

This repository contains a Google Colab notebook that classifies **monsters** (ghouls, goblins, and ghosts) using **RandomForestClassifier**. The model is optimized using **GridSearchCV** to achieve the best performance on the dataset.

---

## 🧠 Problem Description

The goal is to classify each creature into one of the following:
- 👻 **Ghost**
- 🧌 **Goblin**
- 🧟‍♂️ **Ghoul**

We use features such as:
- `bone_length`
- `rotting_flesh`
- `hair_length`
- `has_soul`
- `color`

---

## 📊 Dataset Description

- **Source**: [DrivenData Competition](https://www.drivendata.org/competitions/73/)
- **Type**: Tabular dataset
- **Task**: Multiclass classification
- **Features**:
  - Numeric: `bone_length`, `rotting_flesh`, `hair_length`, `has_soul`
  - Categorical: `color`
  - Target: `type` (Ghost, Goblin, Ghoul)

---

## 🧪 Model: Random Forest Classifier

We use `RandomForestClassifier` and apply **GridSearchCV** to tune:
- `n_estimators`
- `max_depth`
- `min_samples_split`
- `min_samples_leaf`

### 🔍 GridSearchCV Details:
- **Cross-validation**: 5-fold
- **Scoring**: Accuracy

## 📈 Evaluation Metrics

- Accuracy
- Classification report (Precision, Recall, F1-score)
- Confusion Matrix

---
