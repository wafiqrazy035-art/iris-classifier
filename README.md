# Iris Flower Classification

A machine learning project that classifies iris flowers into 3 species (setosa, versicolor, virginica) based on sepal and petal measurements.

## 📊 Project Overview

This project demonstrates a complete machine learning workflow:
- Data exploration and visualization
- Comparing multiple ML algorithms
- Model evaluation with confusion matrix
- Feature importance analysis
- Predicting new samples

## 🎯 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | **96.67%** |
| Decision Tree | 93.33% |
| Random Forest | 90.00% |

**Best Model:** Logistic Regression with 96.67% accuracy on test set (30 samples).

## 🔍 Key Insights

1. **Petal features dominate**: petal width and petal length together contribute ~87% of feature importance
2. **Setosa is easily separable**: 100% precision and recall, no misclassification
3. **Versicolor vs Virginica**: most confusion happens between these two species (1 misclassification)
4. **Simple beats complex**: Logistic Regression outperformed Random Forest, demonstrating that complex models aren't always better

## 🛠️ Tech Stack

- **Python 3.12**
- **scikit-learn** — ML algorithms and dataset
- **pandas** — data manipulation
- **matplotlib & seaborn** — visualization
- **Jupyter Notebook** — interactive development

## 📁 Project Structure

iris-classifier/
├── iris_classifier.ipynb    # Main notebook
├── README.md                # This file
├── requirements.txt         # Dependencies
└── venv/                    # Virtual environment (not committed)

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/wafiqrazy035-art/iris-classifier.git
cd iris-classifier
```

2. Create virtual environment:
```bash
python -m venv venv
.\venv\Scripts\Activate.ps1  # Windows
source venv/bin/activate     # Mac/Linux
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Open the notebook:
```bash
jupyter notebook iris_classifier.ipynb
```

## 📈 Visualizations

The notebook includes:
- Class distribution bar chart
- Pairplot showing relationships between all features
- Confusion matrix heatmap
- Feature importance bar chart

## 🎓 What I Learned

- End-to-end ML workflow from data exploration to model deployment
- Importance of train/test split with stratification
- How to interpret confusion matrix and classification report
- Why simpler models can outperform complex ones on small datasets
- Feature importance analysis for understanding model decisions

## 📝 Future Improvements

- [ ] Hyperparameter tuning with GridSearchCV
- [ ] Cross-validation for more robust evaluation
- [ ] Deploy as Streamlit web app
- [ ] Add more advanced algorithms (SVM, XGBoost)

## 👤 Author

Made by [wafiqrazy035-art] as a learning project to build foundational ML skills.

---

⭐ If you find this helpful, please star the repo!