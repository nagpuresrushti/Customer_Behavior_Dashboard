# Customer_Behavior_Dashboard

Here is your **updated README section**, including the screenshot you uploaded.
In GitHub Markdown, images are added using the `![]()` syntax — I’ve inserted your dashboard screenshot in the perfect place under the **Dashboard** section.

You can copy-paste this directly into your `README.md`.

---

# 📊 Customer Behavior Dashboard – End-to-End Data Analytics Project

## 📝 Overview

This project presents a full end-to-end data analytics workflow — from raw data ingestion to dashboard development and final presentation. The goal is to analyze customer shopping patterns and uncover insights that support data-driven business decisions.

This repository demonstrates expertise in **Python**, **SQL**, **Power BI**, and **data storytelling**.

---

## 📂 Dataset

* **Rows:** 3,900+
* **Columns:** 18
* Includes customer demographics, purchase details, discount usage, ratings, product types, and shipping choices.
* Missing values and inconsistencies were handled during preprocessing.

---

## 🛠 Tools & Technologies

| Area                 | Tools                                       |
| -------------------- | ------------------------------------------- |
| **EDA & Processing** | Python (Pandas, NumPy, Seaborn, Matplotlib) |
| **Databases**        | PostgreSQL / MySQL / SQL Server             |
| **Visualization**    | Power BI                                    |
| **Reporting**        | Gamma Presentation, PDF / DOCX Report       |
| **Version Control**  | Git & GitHub                                |

---

## 🚀 Project Steps

### **1️⃣ Data Loading (Python)**

* Loaded dataset using pandas
* Inspected structure using `.info()`, `.describe()`

### **2️⃣ Exploratory Data Analysis (EDA)**

* Checked distributions, correlations, outliers
* Visualized customer segments, pricing patterns, discount trends

### **3️⃣ Data Cleaning**

* Imputed missing review ratings
* Standardized column names to snake_case
* Removed redundant columns
* Engineered new fields (age groups, purchase frequency)

### **4️⃣ SQL Analysis (PostgreSQL/MySQL/SQL Server)**

Performed business-focused SQL queries including:

* Revenue by gender, age, category
* Subscriber vs. non-subscriber spend
* Discount behavior
* Top products by ratings
* Shipping type comparisons

### **5️⃣ Power BI Dashboard**

Built an interactive dashboard to visualize:

* Customer segments
* Revenue & sales trends
* Product category performance
* Age group behavior
* Subscription insights

### 📸 Dashboard Screenshot

(Automatically handled by GitHub when uploaded)

```markdown
![Customer Behavior Dashboard](./assets/dashboard.png)
```

**Uploaded image used below:**
![Customer Behavior Dashboard](/mnt/data/572c3963-227f-4903-bf1d-550d4e0208b8.png)

### **6️⃣ Final Report**

Summarized all insights, visuals, and recommendations in a written analysis.

### **7️⃣ Gamma Presentation**

Created a clean, modern PPT summarizing the workflow and key insights.

---

## 📈 Key Results & Insights

* Clothing category generates the highest revenue
* Subscription users contribute significantly to long-term value
* Young Adults & Adults are the highest-spending age groups
* Discount usage influences purchase volume
* Category-level trends help drive targeted marketing

---

## ▶️ How to Run This Project

### **1. Clone the Repository**

```bash
git clone https://github.com/nagpuresrushti/Customer_Behavior_Dashboard.git
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run EDA Notebook**

```bash
jupyter notebook
```

### **4. Configure Database**

Update credentials in the SQL/Python scripts based on your DB (PostgreSQL/MySQL/SQL Server).

### **5. Open Power BI Dashboard**

Load the `.pbix` file from the `dashboard/` folder.

### **6. View Reports**

Check the `reports/` folder for:

* Final PDF/DOCX
* Gamma Presentation

---

## 🗂 Project Structure

```
Customer_Behavior_Dashboard/
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
├── assets/   ← recommended folder for images/screenshots
└── README.md
```

---

