# Kimia Farma Performance Analytics

Final Project - Rakamin Academy x Kimia Farma

## 📌 Project Overview

This project analyzes Kimia Farma's business performance from 2020–2023 using transaction, product, and branch datasets.

The project consists of:

- Data preparation using Google BigQuery
- SQL analysis
- Interactive dashboard using Looker Studio
- Business insights and recommendations

---

## 🛠 Tools

- Google BigQuery
- Google Looker Studio
- Google Cloud Platform
- GitHub

---

## 📂 Dataset

The project uses four datasets:

- kf_final_transaction
- kf_product
- kf_kantor_cabang
- kf_inventory

---

## 📊 Data Model

Transaction data is joined with:

- Product Master
- Branch Master

Inventory data is provided but not required for the analytical table.

---

## 📈 Analysis Table

The final table contains:

- transaction_id
- date
- branch_name
- kota
- provinsi
- customer_name
- product_name
- actual_price
- discount_percentage
- persentase_gross_laba
- nett_sales
- nett_profit
- rating_cabang
- rating_transaksi

---

## 📁 SQL

SQL scripts are available in:

```
sql/62926_kimia_farma_analysis.sql
```

---

## 📊 Dashboard

Dashboard was created using Google Looker Studio.

Dashboard includes:

- KPI Summary
- Revenue Trend
- Profit Trend
- Top Branch
- Top Province
- Branch Rating
- Transaction Rating
- Business Insights

---

## 👨‍💻 Author

Shah Delphi Muhammad