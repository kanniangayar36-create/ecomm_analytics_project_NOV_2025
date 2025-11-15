# E-Commerce Analytics Project (NOV 2025)

An end-to-end **E‑commerce Analytics Platform** built with:

* SQL database design
* Python data analysis
* Predictive modeling
* Interactive dashboards

This project simulates a complete analytics workflow used in real-world e‑commerce companies.

---

## 📌 **Project Overview**

This project demonstrates the full lifecycle of an analytics solution:

1. Designing a relational SQL database
2. Loading and transforming data
3. Running Python-based analysis
4. Building predictive models
5. Creating dashboards and insights

---

## 📁 **Repository Structure**

```
├── analytics.py          # Data analysis & insights
├── dashboard.txt         # Dashboard layout / logic
├── db_schema.sql         # SQL schema for creating tables
├── models.py             # Predictive ML models
├── requirements.txt      # Dependencies
├── slides.txt            # Presentation notes
├── README.md             # Documentation
```

---

## 🗄️ **Database Design**

The SQL schema includes:

* **Customers** table
* **Orders** table
* **Order Items**
* **Products**
* **Payments**

All tables follow proper normalization rules.

Example:

```sql
CREATE TABLE customers (
    customer_id INT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    city VARCHAR(50),
    signup_date DATE
);
```

---

## 📊 **Analytics & Insights (Python)**

The `analytics.py` script performs:

* Summary statistics
* Monthly sales trends
* Product performance
* City-wise revenue
* Customer purchase behavior

Key libraries:

* pandas
* numpy
* matplotlib / seaborn

---

## 🤖 **Predictive Modeling**

The `models.py` file includes:

* Customer churn prediction
* Sales forecasting
* Product demand classification

Modeling steps:

1. Data preprocessing
2. Train-test split
3. Model training
4. Evaluation (Accuracy, RMSE, AUC)

---

## 📈 **Dashboards**

The dashboard (Power BI / Tableau / Python) includes:

* Total revenue overview
* Monthly growth
* Top products
* Customer insights
* Forecasts visualized

---

## 🚀 **How to Run the Project**

### **1. Clone the repository**

```
git clone https://github.com/kanniangayar36-create/ecomm_analytics_project_NOV_2025
```

### **2. Install dependencies**

```
pip install -r requirements.txt
```

### **3. Create the SQL schema**

Run the script:

```
mysql < db_schema.sql
```

(or PostgreSQL / SQL Server depending on your setup)

### **4. Run analytics**

```
python analytics.py
```

### **5. Run predictive models**

```
python models.py
```

---

## 🧾 **Presentation Slides**

`slides.txt` includes talking points you can convert into a PPT.

---

## ⭐ **Future Enhancements**

* API integration
* Real-time analytics
* Frontend dashboard in React
* Deployment on cloud

---

## 📬 Contact

If you have questions or want improvements, feel free to reach out!
