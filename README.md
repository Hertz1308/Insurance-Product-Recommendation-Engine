# 🛡️ Insurance Policy Recommendation Engine

This project is a **machine learning-based policy recommender** built with Python. It analyzes user profile details like income, marital status, education, and more, and suggests the most suitable insurance policy using a ranking model.

---

## 📌 Features

- Uses **XGBoost ranking (pairwise ranking)** to match users with policies.
- Categorical inputs are encoded using **Label Encoding**.
- Numerical data is scaled using **StandardScaler**.
- **Cosine similarity** is used to calculate match scores between customer and policy features.
- Provides a **reasoning explanation** for the recommended policy.
- Interactive **CLI interface** for collecting user data.

---

## 📁 Dataset

The project uses the **[WA_Fn-UseC_-Marketing-Customer-Value-Analysis.csv](https://www.kaggle.com/code/tariqmuneer/wa-fn-usec-marketing-customer-lm/input)** dataset for customer profile training data.

Make sure to download and place the CSV file in the same directory as the code:
