# 🛍️ Customer Segmentation Using Unsupervised Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** techniques to segment customers based on their purchasing behavior and demographic characteristics. By understanding the distinct groups within a customer base, businesses can tailor their marketing strategies, optimize product recommendations, and improve overall customer retention. The project primarily leverages **K-Means Clustering** to identify these customer personas.

## 🎯 Objectives

- **Analyze** customer purchasing behavior and demographics.
- **Perform** Exploratory Data Analysis (EDA) to uncover trends.
- **Apply** feature engineering, data cleaning, and standardization.
- **Implement** K-Means clustering for robust customer segmentation.
- **Visualize** high-dimensional customer clusters using t-SNE.

## 📊 Dataset Information

The dataset (`new.csv`) contains comprehensive customer information, including:
- **Demographics:** Year of Birth, Education Level, Marital Status, Income.
- **Family Structure:** Number of children/teens at home.
- **Spending Habits:** Amounts spent on various product categories (Wines, Fruits, Meat, Fish, Sweets, Gold).
- **Engagement:** Web visits, campaign acceptance, and recent purchases.

*(Note: The dataset is excluded from version control for privacy/space, but should be placed in the `data/` directory to run the notebook).*

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## 📂 Project Structure

```text
Customer-Segmentation-Using-Unsupervised-Learning/
│
├── data/                  # Directory for the dataset (e.g., new.csv)
├── images/                # Saved visualizations and plots
├── notebooks/             # Jupyter notebooks for EDA and modeling
│   └── Customer_Segmentation_using_Unsupervised_Machine_Learning_in_Python.ipynb
├── results/               # Exported results and reports
├── .gitignore             # Ignored files and folders
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sashankabhiram/Customer-Segmentation-Using-Unsupervised-Learning.git
   cd Customer-Segmentation-Using-Unsupervised-Learning
   ```

2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Add the dataset:**
   Ensure your dataset (`new.csv`) is placed inside the `data/` folder.

4. **Launch the Notebook:**
   ```bash
   cd notebooks
   jupyter notebook
   ```
   Open `Customer_Segmentation_using_Unsupervised_Machine_Learning_in_Python.ipynb` and run all cells.

## 💡 Key Insights & Results

*(Add your findings here!)*
- **Cluster 1 (e.g., High Spenders):** ...
- **Cluster 2 (e.g., Bargain Hunters):** ...
- **Cluster 3 (e.g., New Parents):** ...

> *Visualizations such as the t-SNE scatter plot of customer segments can be saved in the `images/` folder.*

## 👨‍💻 Author

**Muthyala Sashank Abhiram**
