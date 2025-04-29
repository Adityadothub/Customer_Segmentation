# Customer_Segmentation

# 📊 Customer Segmentation using SQL & Python

This project focuses on segmenting customers into meaningful groups using the **K-Means clustering algorithm**. The goal is to understand customer behavior based on features like age, income, and spending score, which can help businesses make data-driven marketing decisions.

---

## 📌 Project Highlights

- 📂 Dataset loaded from Google Drive into **Google Colab**
- 🧾 Data queried using **SQL** (SQLite in Python)
- 📈 Clustering performed using **K-Means (Scikit-learn)**
- 📊 Visualized with **Matplotlib** and **Seaborn**
- 🔍 Focused on **Age**, **Annual Income**, and **Spending Score**

---

## 🚀 Tech Stack

- **Python 3**
- **Pandas** — data manipulation  
- **SQLite3** — SQL-based querying  
- **Scikit-learn** — clustering (KMeans)  
- **Matplotlib / Seaborn** — data visualization  
- **Google Colab** — development environment  
- **gdown** — Google Drive file download (optional)

---

## 🧠 Workflow

1. Mount or fetch data from Google Drive  
2. Load CSV into a Pandas DataFrame  
3. Create an SQLite database and query required fields  
4. Apply K-Means clustering (e.g., 4 clusters)  
5. Visualize clusters with scatter plots  
6. (Optional) Use Elbow Method to determine optimal clusters

---

## 📊 Example Features Used

| Feature             | Description                         |
|---------------------|-------------------------------------|
| Age                 | Customer's age                      |
| Annual Income (k$)  | Yearly income in thousands          |
| Spending Score      | Score assigned by the store (1–100) |

---

## 🎯 Objectives

- Segment customers into similar behavior groups  
- Identify high-value or high-risk customers  
- Enable targeted marketing strategies  
- Visualize and interpret customer clusters

---

## 🖼 Sample Output

![Clustering Visualization](https://via.placeholder.com/500x300.png?text=Clustering+Visualization)

---

## 📁 How to Run

1. Open the notebook in Google Colab
2. Mount Google Drive or use `gdown` to fetch the dataset
3. Follow the step-by-step cells (SQL + clustering)
4. View and interpret the visual output

---

## 📌 Note

Make sure your dataset includes the relevant columns:
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

Rename or adjust column names if necessary.

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out or open an issue!

---

⭐ If you find this project useful, consider giving it a star on GitHub!
