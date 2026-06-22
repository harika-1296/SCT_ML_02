# SCT_ML_02
Customer Segmentation using K-Means Clustering to group retail store customers based on annual income and spending behavior, enabling data-driven marketing and business insights.

# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

Customer segmentation is an essential strategy for businesses to better understand their customers and deliver personalized marketing campaigns. This project uses the **K-Means Clustering Algorithm** to group customers of a retail store based on their purchasing behavior.

The goal is to identify distinct customer segments using **Annual Income** and **Spending Score**, helping businesses target customers more effectively and improve decision-making.

---

## 🎯 Objective

Build a K-Means Clustering model to:

* Analyze customer purchasing patterns
* Segment customers into meaningful groups
* Identify high-value and low-value customers
* Generate business insights from customer data

---

## 📊 Dataset

The dataset used is **Mall Customers Dataset** containing customer information such as:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

### Features Used for Clustering

* Annual Income (k$)
* Spending Score (1–100)

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Workflow

### 1. Data Collection

* Imported the Mall Customers dataset
* Loaded dataset using Pandas

### 2. Exploratory Data Analysis (EDA)

* Examined dataset structure
* Checked missing values
* Generated statistical summaries
* Visualized feature distributions

### 3. Data Preprocessing

* Selected relevant features
* Applied StandardScaler for feature scaling

### 4. Finding Optimal Number of Clusters

* Used the Elbow Method
* Analyzed WCSS values
* Determined the optimal number of clusters as **5**

### 5. Model Building

* Implemented K-Means Clustering
* Trained the model with 5 clusters
* Assigned cluster labels to customers

### 6. Model Evaluation

* Calculated Silhouette Score
* Evaluated clustering quality

### 7. Visualization

* Visualized customer clusters
* Highlighted cluster centroids
* Interpreted customer segments

---

## 📈 Results

The K-Means algorithm successfully segmented customers into **5 distinct groups**:

| Cluster   | Customer Type                                  |
| --------- | ---------------------------------------------- |
| Cluster 0 | Average Income, Average Spending               |
| Cluster 1 | High Income, High Spending (Premium Customers) |
| Cluster 2 | Low Income, High Spending                      |
| Cluster 3 | High Income, Low Spending                      |
| Cluster 4 | Low Income, Low Spending                       |

---

## 💡 Business Insights

### Premium Customers

* High annual income
* High spending score
* Most valuable customer segment
* Ideal target for premium products and loyalty programs

### Potential Customers

* Low income but high spending
* Responsive to promotions and offers

### Conservative Customers

* High income but low spending
* Opportunity for targeted marketing campaigns

### Budget Customers

* Low income and low spending
* Suitable for discounts and budget-friendly products

---

## 📊 Sample Visualization

The project includes:

* Elbow Method Graph
* Customer Segmentation Scatter Plot
* Cluster Centroid Visualization

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/harika-1296/SCT_ML_02.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

Open:

```bash
Customer_Segmentation.ipynb
```

and execute all cells.

---

## 📁 Project Structure

```text
SCT_ML_02/
│
├── Mall_Customers.csv
├── Customer_Segmentation.ipynb
├── Customer_Segmentation_Output.csv
├── README.md
└── requirements.txt
```

---

## 📌 Key Learnings

* Unsupervised Machine Learning
* Customer Segmentation Techniques
* K-Means Clustering Algorithm
* Feature Scaling
* Elbow Method
* Silhouette Score Evaluation
* Data Visualization

---


## 🏆 Internship Task

**SkillCraft Technology – Machine Learning Internship**

**Task 02:** Create a K-Means Clustering Algorithm to Group Customers of a Retail Store Based on Their Purchase History.

---

### ⭐ If you found this project useful, don't forget to star the repository! ⭐

#SkillCraftTechnology #MachineLearning #KMeansClustering #CustomerSegmentation #DataScience #Python #ScikitLearn #ArtificialIntelligence #InternshipProject
