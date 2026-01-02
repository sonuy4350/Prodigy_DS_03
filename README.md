# Prodigy Infotech – Data Science Internship  
## Task 03: Customer Purchase Prediction using Decision Tree

## 📌 Objective
The objective of this task is to build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on **demographic and behavioral data**.  
This helps businesses identify potential customers and improve marketing strategies.

---

## 📊 Dataset
- **Dataset Name:** Bank Marketing Dataset (Sample)  
- **File Used:** `bank_data.csv`  
- **Description:** Contains information about customers, including:
  - Demographic features: age, job, marital status, education, etc.  
  - Behavioral features: contact communication, previous campaign interactions, etc.  
  - Target variable: Whether the customer subscribed to the product/service (`yes`/`no`)  

**Dataset Source:** [Sample Dataset for Task-03](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)

---

## 🛠️ Data Preprocessing Steps
- Handled missing values if any  
- Encoded categorical variables using **One-Hot Encoding**  
- Split dataset into **features (X)** and **target (y)**  
- Divided data into training and testing sets

---

## 📈 Model Building & Evaluation
- Built a **Decision Tree Classifier** using scikit-learn  
- Trained the model on the training dataset  
- Evaluated the model using:
  - Accuracy  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-score)  
- Visualized the decision tree to understand decision paths  

---

## 🔍 Key Insights
- The decision tree model identifies important features that influence customer purchase behavior  
- Certain demographics and previous interactions significantly affect purchase probability  
- Visualization helps in interpreting how the model makes predictions  

---

## 🧰 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 Repository Contents
- `Task3.ipynb` – Jupyter Notebook containing data preprocessing, model building, and evaluation  
- `bank_data.csv` – Dataset used for modeling  
- `README.md` – Project documentation  
- `visuals/` – Folder for decision tree plots and other visualizations  

---

## ✅ Conclusion
This task provided practical experience in:
- Building a **supervised machine learning model**  
- Preprocessing real-world datasets  
- Evaluating model performance using multiple metrics  
- Visualizing and interpreting a decision tree  

---

## 👤 Author
**Sonu Kumar Yadav**  
Data Science Intern – Prodigy Infotech  
