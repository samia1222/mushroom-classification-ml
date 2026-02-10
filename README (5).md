# Mushroom Classification using Machine Learning

A machine learning project that classifies mushrooms as edible or poisonous using the UCI Mushroom Dataset. This project implements and compares Decision Tree and Random Forest classifiers to achieve accurate classification.

## 📊 Project Overview

This project uses the Mushroom Dataset from the UCI Machine Learning Repository to classify mushrooms based on their physical characteristics. The dataset contains 8,124 instances of mushrooms with 23 categorical features.

**Key Results:**
- **Accuracy:** 100% on both classifiers
- **Models Used:** Decision Tree and Random Forest
- **Evaluation Method:** 10-fold Stratified Cross-Validation

## 📁 Project Structure

```
├── agaricus-lepiota_data.ipynb    # Main Jupyter notebook with analysis
├── agaricus-lepiota.data          # Dataset file
├── agaricus-lepiota.names         # Dataset description
├── THE_ML_REPORT.pdf              # Detailed project report
├── README.md                      # This file
└── Index                          # Original dataset index
```

## 🔍 Dataset

The Mushroom Dataset was originally sourced from The Audubon Society Field Guide to North American Mushrooms (1981) and donated by Jeff Schlimmer in 1987.

**Features:**
- 23 categorical features (cap-shape, cap-color, odor, gill-color, etc.)
- Binary classification: edible (e) or poisonous (p)
- 8,124 total instances

## 🛠️ Preprocessing

1. **Missing Values:** Replaced `?` in `stalk-root` with `unknown` category
2. **One-Hot Encoding:** Applied to categorical features without inherent order
3. **Label Encoding:** Applied to binary features (bruises, class)

## 🤖 Models

### Decision Tree Classifier
- Easy to interpret and visualize
- Handles categorical data well
- Captures non-linear relationships

### Random Forest Classifier
- Ensemble method combining multiple decision trees
- More robust and less prone to overfitting
- Provides feature importance insights

## 📈 Evaluation

**Metrics Used:**
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Validation:** 10-fold Stratified Cross-Validation to ensure balanced class distribution in each fold.

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn jupyter matplotlib seaborn
```

### Running the Project
1. Clone this repository
2. Open `agaricus-lepiota_data.ipynb` in Jupyter Notebook or JupyterLab
3. Run all cells to reproduce the analysis

## 📚 References

- UCI Machine Learning Repository: [Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom)
- Schlimmer, J. S. (1987). Concept Acquisition Through Representational Adjustment
- For detailed references, see THE_ML_REPORT.pdf

## 👨‍💻 Author

**Samia Hassan Haron Hamid**
- Student ID: AIU22102352
- Course: CCS2213 Machine Learning
- Institution: School of Computing and Informatics

## 📄 License

This project uses the UCI Mushroom Dataset which is publicly available for research and educational purposes.

## 🙏 Acknowledgments

- Prof. Dr. Zurinahni Zainol (Course Lecturer)
- UCI Machine Learning Repository
- Jeff Schlimmer (Original dataset donor)
