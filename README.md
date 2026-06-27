# 🚚 Supply Chain Bottleneck & Late Delivery Risk Analysis Dashboard

## 📌 Project Overview

This project analyzes supply chain performance and identifies delivery bottlenecks using historical order and shipment data. The dashboard provides insights into late delivery risks, cost impact, shipping mode performance, regional trends, and category-level delivery delays.

The goal is to help logistics teams, supply chain managers, and business stakeholders monitor shipment performance and make data-driven decisions to reduce delays and associated costs.

---

## 🎯 Business Problem

Late deliveries can lead to:

* Increased operational costs
* Customer dissatisfaction
* Revenue loss
* Supply chain inefficiencies

This dashboard helps identify:

* High-risk shipping methods
* Product categories prone to delays
* Geographic regions with elevated late delivery risks
* Seasonal delay patterns
* Overall financial impact of delayed shipments

---

## 📊 Dashboard Features

### KPI Summary

* **Total Orders:** 180.5K+
* **Late Delivery Cases:** 99K+
* **Total Cost Impact:** $19M+
* **Late Delivery Rate:** 54.83%

---

### Key Visualizations

#### 1. Late Delivery Risk by Shipping Mode

Compares average delay risk across:

* First Class
* Second Class
* Same Day
* Standard Class

**Insight:** Identifies which shipping methods experience the highest delivery risk.

---

#### 2. Late Delivery Risk by Product Category

Highlights categories with the highest probability of delayed deliveries.

Examples:

* Trade-In
* Golf Shoes
* Sporting Goods
* Girls' Apparel
* Basketball

---

#### 3. Monthly Delay Trend Analysis

Tracks average late delivery risk throughout the year.

**Purpose:**

* Detect seasonal patterns
* Identify peak-risk months
* Support capacity planning

---

#### 4. Geographic Delay Risk Map

Visual representation of late delivery risk across global order regions.

**Purpose:**

* Identify regional bottlenecks
* Monitor geographic performance differences
* Support logistics optimization

---

#### 5. Delivery Status Distribution

Breakdown of shipments into:

* Slightly Delayed
* On Time
* Severely Delayed

Provides a quick overview of delivery performance.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI

---

## 📂 Project Structure

```text
Supply-Chain-Bottleneck-Analysis/
│
├── data/
│   └── supply_chain_data.csv
│
├── notebooks/
│   └── supply_chain_bottleneck.ipynb
│
├── dashboard/
│   └── Supply_Chain_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
├── README.md
│
└── requirements.txt
```

---

## 📈 Key Metrics Calculated

### Late Delivery Risk

Measures the probability of an order being delivered after its expected date.

### Cost Impact

Estimates the financial impact caused by delayed shipments.

### Delay Rate

```text
Delay Rate = (Delayed Orders / Total Orders) × 100
```

### Category Risk Score

Average delay risk calculated across product categories.

---

## 🔍 Insights Generated

* First Class shipments show the highest average late delivery risk.
* More than half of all orders experienced delivery delays.
* Certain product categories consistently face higher shipment risks.
* Delay risk fluctuates throughout the year, indicating seasonal bottlenecks.
* Geographic regions differ significantly in delivery performance.

---

## 🚀 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/supply-chain-bottleneck-analysis.git
cd supply-chain-bottleneck-analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
supply_chain_bottleneck.ipynb
```

```

---

## 💡 Future Enhancements

* Predictive delivery delay modeling using Machine Learning
* Real-time shipment tracking integration
* Automated bottleneck alerts
* Supplier performance scoring
* Route optimization recommendations

---

### ⭐ If you found this project useful, consider giving it a star on GitHub!
