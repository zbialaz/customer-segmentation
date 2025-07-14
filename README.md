# 🛍️ Customer Segmentation Analysis

## 📊 Project Overview

This project implements a comprehensive customer segmentation analysis using K-Means clustering algorithm on mall customer data. The analysis identifies distinct customer segments based on demographic and behavioral characteristics to support targeted marketing strategies.

## 🎯 Objectives

- Segment customers based on age, annual income, and spending behavior
- Identify optimal number of clusters using statistical methods
- Provide actionable business insights for each customer segment
- Generate targeted marketing recommendations

## 📈 Dataset

The analysis uses the Mall Customers dataset containing:
- **200 customers** with demographic and behavioral data
- **5 features**: CustomerID, Gender, Age, Annual Income, Spending Score
- **Source**: Kaggle Mall Customers Dataset

### Features Description:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Customer gender (Male/Female)
- `Age`: Customer age in years
- `Annual Income (k$)`: Annual income in thousands of dollars
- `Spending Score (1-100)`: Spending behavior score from 1-100

## 🔧 Technologies Used

- **Python 3.8+**
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` & `seaborn` - Data visualization
  - `scikit-learn` - Machine learning algorithms
  - `kaggle` - Dataset download

## 📁 Project Structure

```
customer_segmentation/
├── notebook/
│   └── mall_customer_seg.ipynb    # Main analysis notebook
├── dataset/
│   └── Mall_Customers.csv         # Raw dataset
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/customer_segmentation.git
cd customer_segmentation
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn kaggle
```

3. Set up Kaggle API (optional):
   - Download `kaggle.json` from your Kaggle account
   - Place it in `~/.kaggle/kaggle.json`

4. Run the Jupyter notebook:
```bash
jupyter notebook notebook/mall_customer_seg.ipynb
```

## 📊 Analysis Workflow

### 1. Data Exploration
- Statistical summary of customer demographics
- Distribution analysis of key features
- Correlation analysis between variables

### 2. Data Preprocessing
- Feature selection for clustering
- Data standardization using StandardScaler
- Handling of categorical variables

### 3. Optimal Cluster Determination
- **Elbow Method**: Identifies optimal k based on WCSS
- **Silhouette Analysis**: Evaluates cluster quality
- **Stability Analysis**: Tests clustering consistency

### 4. K-Means Clustering
- Implementation of K-Means algorithm
- Cluster assignment and visualization
- Performance evaluation using multiple metrics

### 5. Algorithm Comparison
- K-Means vs Agglomerative Clustering
- K-Means vs Gaussian Mixture Models
- Performance comparison using Silhouette Score

## 📈 Key Findings

### Customer Segments Identified:

1. **💎 Premium Customers (High Income + High Spending)**
   - Target demographic for luxury products
   - Focus on premium experiences and exclusive offers

2. **💰 Conservative Customers (High Income + Low Spending)**
   - Potential for upselling with value propositions
   - Strategic discount campaigns

3. **🎯 Impulsive Customers (Low Income + High Spending)**
   - Responsive to emotional marketing
   - Affordable product recommendations

4. **📊 Budget Customers (Low Income + Low Spending)**
   - Price-sensitive segment
   - Focus on value and necessity items

5. **⚖️ Moderate Customers (Balanced Profile)**
   - Diverse marketing approach
   - Engagement and loyalty programs

## 🎯 Business Recommendations

### Marketing Strategy by Segment:

- **Premium Segment**: Exclusive events, premium product launches
- **Conservative Segment**: Value-based messaging, strategic discounts
- **Impulsive Segment**: Emotional appeals, limited-time offers
- **Budget Segment**: Price promotions, essential product focus
- **Moderate Segment**: Balanced campaigns, loyalty programs

## 📊 Model Performance

- **Optimal Clusters**: 5 segments
- **Silhouette Score**: 0.XXX (to be updated with actual value)
- **Algorithm Stability**: Consistent across multiple runs
- **Best Performing Algorithm**: K-Means clustering

## 📈 Visualizations

The project includes comprehensive visualizations:
- Customer distribution by demographics
- Cluster visualization in 2D and 3D space
- Comparative analysis across different algorithms
- Business insights dashboard

## 🙏 Acknowledgments

- [Kaggle](https://www.kaggle.com) for providing the dataset
- [Scikit-learn](https://scikit-learn.org/) for machine learning tools
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for visualization capabilities

---

