# Machine Learning Course Projects

This repository contains a collection of machine learning projects developed during the **CENG 463 - Introduction to Machine Learning** course. Each project focuses on different aspects of ML, ranging from supervised classification and feature engineering to unsupervised clustering and natural language processing (NLP).

## 🛠 Tech Stack
* **Languages:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn, PyTorch/Keras (for data loading), BERTopic.
* **Concepts:** Supervised Learning (Random Forest, SVM), Unsupervised Learning (K-Means, DBSCAN), NLP (Topic Modeling), Dimensionality Reduction (PCA, t-SNE).

---

## 📂 Projects Overview

### 1. [Water Resource Risk Classification](./01-Water-Resource-Risk)
**Goal:** Predicting the water resource risk category of countries based on hydrological and environmental indicators.
* **Key Techniques:**
    * **Feature Engineering:** Created *Composite Water Stress Index (CWSI)* and *Seasonal-Flood Interaction (SFI)* features which significantly improved model performance.
    * **Model Comparison:** Benchmarked Random Forest, SVM, KNN, Logistic Regression, and Naive Bayes.
* **Results:** Achieved **~92% accuracy** with the Random Forest model, identifying it as the superior algorithm for handling non-linear hydrological data.

### 2. [News Topic Modeling & Text Analysis](./02-News-Topic-Modeling)
**Goal:** Analyzing text data to classify documents and discover hidden topics within news articles.
* **Key Techniques:**
    * **Bag of Words (BoW):** Implemented from scratch to analyze frequency distributions across Sports, Economy, and Politics domains.
    * **Topic Modeling:** Utilized **BERTopic** and **UMAP** to discover latent topics.
    * **Debugging:** Solved a critical reproducibility issue with UMAP's random state initialization that was merging distinct topics.
* **Results:** Successfully identified 21 distinct topics and validated coherence using synthetic document tests.

### 3. [CIFAR-10 Image Clustering](./03-CIFAR10-Image-Clustering)
**Goal:** Grouping images from the CIFAR-10 dataset using unsupervised learning techniques without using labels.
* **Key Techniques:**
    * **Dimensionality Reduction:** Reduced 3072 features to 50 components using **PCA** to tackle the curse of dimensionality.
    * **Clustering Algorithms:** Compared K-Means, Agglomerative Clustering, and DBSCAN.
    * **Analysis:** Visualized clusters using t-SNE to observe class separation (e.g., Vehicles vs. Animals).
* **Results:** **K-Means** proved to be the most effective algorithm for this high-dimensional dataset, successfully grouping broad categories like vehicles.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/osmanaltunbag/ml-course-projects.git](https://github.com/osmanaltunbag/ml-course-projects.git)

