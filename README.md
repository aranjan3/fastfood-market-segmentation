# McDonald's Customer Segmentation using Machine Learning

This project analyzes consumer perception data of McDonald's to identify meaningful customer segments using machine learning techniques in Python.

## 🚀 Project Highlights

- Conducted **exploratory data analysis (EDA)** and **binary encoding** of perception variables.
- Applied **Principal Component Analysis (PCA)** for dimensionality reduction and **perceptual mapping**.
- Performed **K-Means clustering (2–8 segments)** and **cluster stability analysis** via bootstrapped Adjusted Rand Index (ARI).
- Used **Factor Analysis for Mixed Data (FAMD)** for visualizing mixed-type variables with cluster membership.
- Compared results with **Bayesian Gaussian Mixture Models (BGMM)** and profiled clusters using **Random Forest** feature importance.

## 📚 Dataset

Sourced dataset includes:

- 11 brand perception variables (e.g., YUMMY, FAST, FUN)
- Demographics (Age, Gender)
- Behavioral data (Visit Frequency, Liking Score)


## 🛠 Libraries Used

- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- prince (for FAMD)
- Jupyter Notebook

## 📈 Results

- Identified **4 customer segments** based on brand perception.
- Visualized insights using **scree plots**, **perceptual maps**, **FAMD projections**, and **cluster profile heatmaps**.
- Key attributes influencing cluster separation: *YUMMY*, *FUN*, *FAST*.

## ✅ Conclusion

This segmentation can guide McDonald's to tailor its **marketing strategy**, personalize campaigns, and design better offerings for distinct consumer groups.

---

📌 *Feel free to explore, fork, or adapt this notebook for your own segmentation or consumer analytics work!*
