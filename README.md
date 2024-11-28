# 🛍️ Customer Segmentation with Clustering

## 📚 Table of Contents

1. [📖 Project Overview](#project-overview)
2. [🧰 Tech Stack and Libraries](#tech-stack-and-libraries)
3. [🎯 Project Structure](#project-structure)
   - [Data Loading & Preprocessing](#data-loading--preprocessing)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Feature Engineering](#feature-engineering)
   - [Clustering](#clustering)
   - [Insights & Analysis](#insights--analysis)
4. [🚀 Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
5. [📊 Key Results](#key-results)
6. [📂 Folder Structure](#folder-structure)
7. [📜 License](#license)
8. [📫 Contact](#contact)

Welcome to the **Customer Segmentation** project! This project focuses on analyzing customer data and segmenting customers into distinct groups using clustering techniques, making it easier for businesses to understand and target their audience effectively. 🚀

---

## 📂 Project Overview

In this project, we utilize **machine learning clustering algorithms** to classify customers into different segments based on their purchasing behavior. This segmentation helps identify unique characteristics of customer groups, allowing businesses to tailor marketing strategies, optimize product placements, and enhance personalized recommendations for different customer segments.


### **Business Requirements for Clustering**

1. **Customer Segmentation:**
   - **Objective:** Group customers into segments based on their demographic, socio-economic, and geographic characteristics.
   - **Use Case:** Tailor marketing campaigns for different customer groups. For instance:
     - High-income young professionals (premium product targeting).
     - Elderly customers in small settlements (budget-friendly offerings).

2. **Personalized Product Recommendations:**
   - **Objective:** Understand customer preferences by clustering based on occupation, income, and age.
   - **Use Case:** Recommend products or services suited to the identified cluster, e.g., luxury goods for high-income professionals or educational loans for younger, educated customers.

3. **Market Expansion:**
   - **Objective:** Identify underserved customer groups or regions (based on `Settlement size`).
   - **Use Case:** Launch new branches, stores, or digital campaigns targeting clusters in small settlements or areas with specific customer profiles.

4. **Credit Risk Assessment:**
   - **Objective:** Categorize customers into risk profiles based on `Income`, `Age`, and `Marital status`.
   - **Use Case:** Financial institutions can offer customized loan schemes or credit limits based on the customer's cluster (e.g., low-risk clusters get higher credit limits).

5. **Improving Customer Retention:**
   - **Objective:** Cluster customers to identify groups more likely to churn (e.g., low-income, older age, or smaller settlements).
   - **Use Case:** Design targeted loyalty programs or retention strategies.

6. **Workforce Planning:**
   - **Objective:** Analyze customer clusters based on `Occupation` and `Settlement size` to understand demand patterns.
   - **Use Case:** Allocate resources or sales representatives to areas with higher customer density for specific occupations or settlement sizes.

7. **Enhancing Education Services:**
   - **Objective:** Use `Education`, `Age`, and `Settlement size` to cluster customers who might need educational services or upskilling programs.
   - **Use Case:** Promote online courses or skill-building workshops to clusters with high educational needs.
     

### 📂 Dataset Source

The dataset used in this project is available on Kaggle:  
[**Customer Clustering Dataset**](https://www.kaggle.com/datasets/dev0914sharma/customer-clustering)

---

### 🧰 Tech Stack and Libraries

- **Python** 🐍: The backbone of our project
- **Jupyter Notebook** 📓: For organizing code, visualizations, and insights in a single, interactive document
- **Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`

---

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

---

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

---

## 📊 Key Results

- **Gaussian Mixture Model (GMM)** outperformed other methods such as K-means, DBSCAN, and Hierarchical Clustering.
- The best clustering was achieved with **7 components** and a **tied variance** matrix.
- Model selection metrics **AIC** and **BIC** confirmed GMM as the most suitable model, supported by the highest **Rand Index** and **Silhouette Score**.

Each cluster represents a unique customer group based on purchasing patterns and behavior, providing valuable insights for targeted marketing. 📈

---

## 📂 Folder Structure

```bash
├── customer-segmentation-clustering.ipynb  # Jupyter Notebook with code and analysis
├── requirements.txt                       # Libraries required to run the project
└── README.md                              # Project description and instructions
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 📫 Contact

Feel free to reach out for questions or support:

- **Name**: Om Subhash Shrivastav
- **Email**: [omshrivastav1005@gmail.com](mailto:omshrivastav1005@gmail.com)
- **GitHub**: [Omshrivastav12](https://github.com/Omshrivastav12)

Happy recommending! 🌟
