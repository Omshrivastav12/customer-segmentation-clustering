# 🛍️ Customer Segmentation with Clustering

Welcome to the **Customer Segmentation** project! This project focuses on analyzing customer data and segmenting customers into distinct groups using clustering techniques, making it easier for businesses to understand and target their audience effectively. 🚀

## 📂 Project Overview

In this project, we utilize **machine learning clustering algorithms** to classify customers into different segments based on their purchasing behavior. This segmentation helps in identifying unique characteristics of customer groups and can improve marketing strategies, product placements, and personalized recommendations.

### 🧰 Tech Stack and Libraries

- **Python** 🐍: The backbone of our project
- **Jupyter Notebook** 📓: For organizing code, visualizations, and insights in a single, interactive document
- **Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`

## 🎯 Project Structure

1. **Data Loading & Preprocessing** 🧹
    - Load customer data and clean it for analysis.
    - Handle missing values, outliers, and data types to prepare a robust dataset.

2. **Exploratory Data Analysis (EDA)** 🔍
    - Visualize distributions, correlations, and potential patterns in the data.
    - Understand the general trends and significant variables in the customer dataset.

3. **Feature Engineering** 🛠️
    - Transform and create features to enhance model performance.
    - Standardize and scale features for clustering.

4. **Clustering** 🧊
    - Experiment with multiple clustering methods:
        - **K-Means Clustering**
        - **DBSCAN**
        - **Gaussian Mixture Model (GMM)**
        - **Hierarchical Clustering**
    - Achieved the best clustering results with the **Gaussian Mixture Model (GMM)** using 7 components and a tied variance matrix. The GMM outperformed other methods based on **AIC** and **BIC** scores, along with superior **Rand Index** and **Silhouette Score**, indicating better cluster separation and accuracy.

5. **Insights & Analysis** 📊
    - Summarize key insights for each cluster.
    - Present actionable business insights for targeting and marketing strategies.

## 🚀 Getting Started

### Prerequisites

Make sure you have **Python 3.x** installed.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/customer-segmentation.git
    cd customer-segmentation
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook customer-segmentation-clustering.ipynb
    ```

## 📊 Key Results

- **Gaussian Mixture Model (GMM)** outperformed other methods such as K-means, DBSCAN, and Hierarchical Clustering.
- The best clustering was achieved with **7 components** and a **tied variance** matrix.
- Model selection metrics **AIC** and **BIC** confirmed GMM as the most suitable model, supported by the highest **Rand Index** and **Silhouette Score**.

Each cluster represents a unique customer group based on purchasing patterns and behavior, providing valuable insights for targeted marketing. 📈

## 📂 Folder Structure

```bash
├── customer-segmentation-clustering.ipynb  # Jupyter Notebook with code and analysis
├── requirements.txt                       # Libraries required to run the project
└── README.md                              # Project description and instructions
```

## 📜 License

This project is licensed under the MIT License.
