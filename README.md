# 🐧 Penguin Species Classification using Naive Bayes (GaussianNB)

This is a beginner-friendly machine learning project that uses the **Naive Bayes classifier** (specifically, the Gaussian variant) to classify penguin species based on physical measurements and island location. It uses the popular **Palmer Penguins Dataset** as a simpler and more interpretable alternative to the Iris dataset.

---

## 📂 Dataset

The dataset used in this project is referenced from the following source:

🔗 [[Palmer Penguins Dataset – GitHub (by Allison Horst)](https://github.com/allisonhorst/palmerpenguins)](https://www.kaggle.com/datasets/martaarroyo/palmer-penguins-for-binary-classification)


> **Note:** The dataset is not uploaded to this repository due to licensing and distribution considerations. Please download it from the above link 

---

## 🚀 Project Highlights

- Predict penguin species: **Adelie** and **Gentoo**
- Used the **Gaussian Naive Bayes** model
- Performed data preprocessing:
  - Handled missing values
  - Encoded categorical variables
  - Scaled numerical features using **MinMaxScaler**
- Trained and tested the model on an 80:20 split
- Evaluated performance using:
  - **Accuracy**
  - **Precision / Recall / F1-Score**
  - **Confusion Matrix**

---

## 🧪 How to Run

1. Open the notebook in **Google Colab** or any Jupyter environment  
2. Use `seaborn` or `pandas` to load the Palmer Penguins dataset  
3. Run all cells step-by-step to:
   - Clean and preprocess the data
   - Train and evaluate the Naive Bayes model

> ✅ **Tip:** You can visualize the data distribution using pairplots or correlation heatmaps to better understand feature separability.

---

## ✅ Conclusion

The **Gaussian Naive Bayes model** worked effectively for this multiclass classification problem. Despite its simplicity and assumptions of feature independence, the model achieved solid accuracy and balanced precision/recall across classes. This shows that Naive Bayes can be a strong baseline for clean, structured datasets like Palmer Penguins.

---

## 🛠️ Credits

- Dataset: Kaggle - Palmer Penguins for binary classification  
- Developed using **Python**, **Scikit-learn**, **Pandas**, **matplotlip** and **Seaborn**
