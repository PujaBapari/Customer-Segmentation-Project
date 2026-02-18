# 📊 Retail Customer Segmentation (RFM & K-Means)

### 🌟 Project Overview
This project focuses on segmenting customers of an online retail store to understand their purchasing behavior. By using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means Clustering**, I have categorized customers into distinct groups, which helps in creating targeted marketing strategies.

### 📂 Dataset
The dataset used in this project is the "Online Retail Dataset" which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

🔗 **Dataset Link:** [[Download from Kaggle](https://www.kaggle.com/datasets/thedevastator/online-retail-transaction-data)]

---

### 🛠️ Key Technical Steps
1. **Data Cleaning:** Handled missing values (specifically CustomerIDs) and removed outliers or invalid transactions (negative quantities/prices).
2. **RFM Analysis:** -
   **Recency:** Days since the last purchase.
   - **Frequency:** Total number of transactions.
   - **Monetary:** Total amount spent by the customer.
3. **Data Preprocessing:** Applied **Log Transformation** and **StandardScaler** to normalize the skewed RFM data for better clustering results.
4. **Machine Learning:** Implemented **K-Means Clustering** to automatically group customers into 4 optimal segments.

---

### 📈 Visualizing the Segments
The following plot shows how customers are grouped based on their Recency and Monetary value after applying the K-Means algorithm:

<img width="657" height="494" alt="image" src="https://github.com/user-attachments/assets/68c911c9-48fa-4fd4-b85c-0acf67710c7f" />


---

### 💻 Tech Stack Used
- **Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Download the dataset from the link above and place it in the project folder.
4. Run the script: `python main.py`
