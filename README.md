# PowerPay Insights Dashboard | 2022 – 2025  

## 🏢 Company Background  
**PowerPay** is a mid-sized electricity distribution company serving over **4 million customers** across 20 regional business centers (IBCs).  
As part of its digital transformation initiative, PowerPay aimed to evaluate how customers are shifting from **conventional payment modes** (cash, cheque, booth counters) to **digital platforms** (mobile apps, e-banking, wallets).  

This dashboard consolidates **payment, transaction, and regional data** between **2022 and 2025**, enabling PowerPay’s management to monitor collection efficiency, digital adoption, and customer behaviour in real time.

---

## 🎯 Project Objectives  
- Track total payments and transactions across all IBCs.  
- Compare **Digital (ADC)** vs **Conventional (OTC)** payment performance.  
- Identify leading and lagging IBCs based on payment volume and customer type.  
- Measure the effectiveness of **digital adoption initiatives** and **loyalty programs**.  
- Highlight seasonal and behavioural trends to support financial forecasting.  

---

## 🧩 Dataset Overview  
Synthetic dataset built to simulate real-world utility data.

| Column | Description |
|---------|-------------|
| Date | Payment posting date |
| IBC | Integrated Business Center (regional office) |
| Mode / Mode Type | ADC (digital) or OTC (manual) |
| Further Breakdown | Channel-level detail (Online Banking, Wallet, Cash, Cheque, etc.) |
| Consumer Category | Residential, Commercial, Industrial, Temporary |
| Customer Type | Regular or Loyalty |
| Paytype / Sub Type | Card, Wallet, Counter, Booth, etc. |
| Online vs Offline | Indicates digital adoption level |
| RTPS, KE-Live, HBLBooth | Flags for payment completion and integration |
| Transactions | Number of successful payment events |
| Amount | Total payment amount collected (PKR) |

🧮 **Records:** 60,000  
🗓 **Period:** 2022 – 2025  
📊 **Tool Used:** Power BI  
💾 **Data Type:** Fully synthetic (non-confidential, generated using Python)

---

## 📊 Dashboard Insights  

### **1️⃣ Payment Channel Performance**  
- **Digital payments dominate** with ~80% share of total collections.  
- Wallets, online banking, and app-based transactions show strong quarterly growth.  
- Conventional payments continue to decline (~15–20%) across 2024–2025.  

### **2️⃣ Regional (IBC) Insights**  
- **Top-performing IBCs:** Area 3, Area 9, and Area 1 lead in both payments and transaction volume.  
- **Low-performing IBCs:** Area 17–20 show reduced digital adoption and lower payment completion rates.  

### **3️⃣ Customer Behaviour**  
- Residential customers form **70% of total transactions** but contribute smaller amounts.  
- Commercial customers drive **~40% of revenue** with larger payment values.  
- Loyalty customers show higher engagement and on-time payment frequency.  

### **4️⃣ Seasonal Patterns**  
- Collections **peak in Mar–Apr and Oct–Dec** (due cycles & festive billing).  
- **Mid-year (Jun–Jul)** shows low activity.  
- Weekly analysis reveals Monday–Tuesday spikes post weekend.  

### **5️⃣ 2025 Snapshot**  
| Metric | Value | Change (YoY) |
|--------|--------|---------------|
| **Total Payments** | 15.26 bn | +12.5% |
| **Digital Payments** | 12.33 bn | +18.7% |
| **Conventional Payments** | 2.93 bn | –9.4% |
| **Total Transactions** | 1.32 M | +15.2% |

---

## 💡 Key Recommendations  
1. Launch **digital cashback & loyalty rewards** to increase wallet usage.  
2. Provide **targeted outreach** to underperforming regions with low ADC adoption.  
3. Automate **collection alerts** for seasonal low-collection periods.  
4. Integrate **complaint analytics** to correlate outages/service issues with payment delays.  
5. Maintain focus on **digital customer retention**, as digital users show higher consistency.  

---

## 🛠 Tools & Technologies  
Power BI • Excel • Python (Synthetic Data Generation) • GitHub • Pandas  

---

## ⚠️ Disclaimer  
All data presented are **synthetically generated** and do not represent any real organization.  
This project was created purely for analytical and portfolio demonstration purposes.  

---

### 📁 Repository Structure
