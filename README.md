#  Crypto Historical Prices Dashboard

**Data Analytics • Cryptocurrency Market Insights • Looker Studio Dashboard**

This project analyzes eight years of historical data across five major cryptocurrencies to uncover price dynamics, volatility patterns, market behavior, and seasonal trends. It is built as an end-to-end analytics workflow—from data preparation and exploration to visualization and strategic recommendations—to support more informed and data-driven investment decisions.

---

##  **1. Background**

The cryptocurrency market is characterized by extreme volatility, making it difficult for investors to identify safe momentum and optimal allocation strategies. Differences in asset stability, unpredictable trading windows, and sharp fluctuations in volume introduce additional risk—especially for retail investors sensitive to liquidity swings.
This project addresses that challenge by leveraging long-term historical data to extract reliable insights that can guide more measured and informed investment decision-making.

---

##  **2. Analytical Workflow**

This analysis follows a structured end-to-end data workflow:

### **1. Business Understanding**

Defined the primary needs of investors:

* Achieving more accurate trading timing
* Identifying assets with higher long-term stability
* Increasing confidence in portfolio allocation

### **2. Data Collection**

Gathered **8 years of historical data** for the five cryptocurrencies that represent the majority of market activity.

### **3. Data Preparation**

Ensured clean, reliable, ready-to-analyze data by:

* Normalizing data types
* Handling missing values
* Removing duplicates
* Reviewing and addressing outliers
* Exporting cleaned data in `.csv` format

### **4. Exploratory Data Analysis (EDA)**

Explored long-term price trends, seasonal patterns, volatility cycles, and volume dynamics to uncover market drivers and behavioral signals.

### **5. Dashboard Development**

Built an interactive **Looker Studio dashboard** to consolidate insights, enable quick interpretation, and support precise and data informed decision making.

---

## **3. Key Findings**

From the eight-year dataset, four major patterns consistently shape crypto market movements:

* **Bitcoin is the market’s most stable asset**, acting as a leading indicator for almost all altcoin movements.
* **Bitcoin and Ethereum dominate trading volume**, reflecting the highest levels of market confidence.
* **Bitcoin’s market cap overwhelmingly surpasses other assets**, reinforcing its position as the primary market driver.
* Strong **seasonal patterns** emerge:

  * Prices generally increase at the **beginning of the year**
  * Weekend periods show **consistent upward tendencies**

These findings form a clear basis for strategic recommendations.

---

## **4. Strategic Recommendations**

Based on the observed patterns:

* **Use Bitcoin as the anchor asset**, as it consistently signals early market movements.
* Position **Ethereum and BNB** as stable growth drivers due to their liquidity and strong historical performance.
* Leverage **seasonal patterns**—early-year accumulation and weekend momentum—for more precise trading timing.
* Treat **ADA and DOT** as selective high-risk, small-allocation assets with strict risk management.

This balanced approach enhances stability while still capturing upside potential through controlled exposure to growth and speculative assets.

---

## **5. Tools & Technologies**

* **Python / Jupyter Notebook** for EDA and data cleaning
* **Pandas, NumPy, Matplotlib**
* **Google Sheets** for structured dataset storage
* **Looker Studio** for dashboard visualization
* **Git & GitHub** for version control

---

## 📊 **6. Dashboard**

🔗 **Live Dashboard (Looker Studio):**
* https://lookerstudio.google.com/s/kq2dkAthJmE *

---

## 📁 **7. Project Structure**

```
📦 crypto-historical-prices-dashboard
├── data/                # Raw and cleaned csv data
├─────raw                # Raw
├── notebooks/           # Jupyter Notebooks
├── deliverables/
│   ├── dashboard/       # Dashboard preview images
│   ├── report/          # Reports and documentation
└── README.md
```

---

👤 Team

Nicki D. Utomo
Anindya Meyla KS
Yusi Nifmad M
Rafli Firdaus M
Muhammad Arifian

A collaborative analytics team focused on delivering high-quality data processing, financial insights, and performance driven dashboard solutions. Our work emphasizes data integrity, analytical rigor, and clarity in communicating insights for strategic decision-making.
