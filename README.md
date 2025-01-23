# 🎯 Customer Segmentation Using K-Means Clustering

Welcome to the **Customer Segmentation Project**, where we analyze mall customer data to uncover actionable business insights using the **K-Means Clustering** algorithm. This project demonstrates how machine learning can drive personalized marketing strategies and improve resource allocation.

---

## 📝 Table of Contents
- [Overview](#overview)  
- [Dataset](#dataset)  
- [Tools and Libraries](#tools-and-libraries)  
- [Methodology](#methodology)  
- [Results](#results)  
- [How to Run](#how-to-run)  
- [Contributions](#contributions)  

---

## 📚 Overview
Customer segmentation is a critical task for businesses looking to better understand their customers and offer targeted services. In this project, we:
- Use **K-Means Clustering** to segment customers into 5 distinct groups.
- Perform **Exploratory Data Analysis (EDA)** to identify trends in customer behavior.
- Visualize results to gain insights into spending patterns and annual income levels.

---

## 📊 Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python). It contains 200 entries with the following columns:
- **CustomerID**: Unique identifier for customers.  
- **Gender**: Gender of the customer.  
- **Age**: Age of the customer.  
- **Annual Income (k$)**: Annual income in thousands of dollars.  
- **Spending Score (1-100)**: A score assigned based on customer spending habits.

---

## 🛠 Tools and Libraries
The following tools and libraries were used in this project:
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning algorithm implementation.

---

## 🔍 Methodology
1. **Data Preparation**:
   - Dataset downloaded and preprocessed for analysis.
   - Checked for missing values and ensured data quality.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions of age, annual income, and spending score.
   - Examined relationships between features using scatter plots and box plots.

3. **Optimal Cluster Determination**:
   - Applied the **Elbow Method** to find the ideal number of clusters (5 clusters).

4. **K-Means Clustering**:
   - Segmented customers into 5 clusters based on **Annual Income** and **Spending Score**.

5. **Visualization**:
   - Visualized cluster distributions and centroids for better interpretability.

---

## 🎉 Results
The clustering results produced **5 distinct customer segments**:
- **Cluster 1**: Low income, low spending score.  
- **Cluster 2**: Low income, high spending score.  
- **Cluster 3**: High income, low spending score.  
- **Cluster 4**: High income, high spending score.  
- **Cluster 5**: Moderate income and spending score.  

These insights can be used to:
- Target high-value customers with premium offers.
- Engage low-spending customers through discounts and loyalty programs.
- Optimize marketing strategies and allocate resources efficiently.

---

## 🚀 How to Run
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/customer-segmentation.git
2. Navigate to the project directory:
   ```
   cd customer-segmentation
3. Install the required libraries:
   ```
   pip install -r requirements.txt
4. Run the main script:
   ```
   python customer_segmentation.py

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📬 Contact
For questions or feedback, feel free to reach out:
- Email: muhammadasrialfajri@gmail.com
- LinkedIn: https://www.linkedin.com/in/muhammadasrialfajri
