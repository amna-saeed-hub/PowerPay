<div align="center">
  <img width="300px" src="https://res.cloudinary.com/dxctpvd8v/image/upload/v1739421238/PowerPay_Logo" />
</div>

<h1 align="center">PowerPay Insights Dashboard</h1>

<table align="center">
  <tr>
    <td width="1440">
      <h2 align="center">Client Background</h2>

      <p>
        <strong>PowerPay</strong> is a regional electricity distribution company serving over 4 million customers through 20 regional business centers (Areas).  
        Established in 2018, PowerPay provides both residential and commercial connections while promoting its digital transformation initiatives.  
        Over the years, the company has faced evolving consumer payment preferences — transitioning from manual over-the-counter (Conventional) collections to modern digital platforms (mobile wallets, banking apps, and online portals).
      </p>

      <p>
        To enhance revenue collection efficiency and monitor customer behaviour, PowerPay conducted an in-depth analysis of its payment data from <strong>2022–2025</strong>.  
        The analysis provides actionable insights on channel performance, customer segments, and digital adoption patterns that can guide future collection strategies.
      </p>

      <h3>Northstar Metrics</h3>
      <ul>
        <li><strong>Total Payments:</strong> Tracking total collection amounts across digital and conventional channels.</li>
        <li><strong>Digital Adoption:</strong> Monitoring migration from cash/cheque payments to online, wallet, and mobile app transactions.</li>
        <li><strong>Customer Behaviour:</strong> Analysing transaction trends by customer type (Regular vs Loyalty) and category (Residential vs Commercial).</li>
        <li><strong>Regional Performance:</strong> Evaluating Area-wise payment trends and identifying low-performing areas.</li>
        <li><strong>Seasonal Analysis:</strong> Understanding collection peaks and dips across months and quarters.</li>
      </ul>
    </td>
  </tr>
</table>


---

<h1 align="center">Executive Summary</h1>

<h3 align="center">Collection Analysis (2022–2025)</h3>
<img width="1433" height="122" alt="PowerPay_Dashboard_Top" src="https://github.com/user-attachments/assets/23525010-2deb-4e04-a7b1-561b78bdc0d3" />

<div align="center">
  
</div>

<table>
<tr>
<td width="460" valign="top">

1. <strong>Digital Growth & Peak Performance</strong>  
   - Digital (Digital) payments increased from <strong>9.8bn in 2022</strong> to <strong>12.3bn in 2025</strong>, marking a consistent upward trend.  
   - Online and wallet-based transactions now make up nearly <strong>80%</strong> of all collections.  
   - The highest monthly collection was recorded in <strong>March 2025</strong> with over <strong>1.12bn</strong> in total payments.

2. <strong>Steady Decline in Conventional Payments</strong>  
   - Over-the-counter (Conventional) collections have declined by <strong>15–20%</strong> over the last two years.  
   - Rural Areas still contribute heavily to Conventional volumes, while urban centers show stronger digital uptake.

</td>

<td width="460" valign="top">

3. <strong>Customer Category Insights</strong>  
   - <strong>Residential customers</strong> account for ~70% of all transactions but contribute smaller payment amounts.  
   - <strong>Commercial customers</strong>, although only 20% by count, contribute over 40% of the total payment value.  
   - Loyalty users show higher engagement and on-time payment behaviour.

4. <strong>Seasonal & Behavioural Trends</strong>  
   - Peaks observed in <strong>March–April</strong> and <strong>October–December</strong>.  
   - A mid-year dip occurs in <strong>June–July</strong> due to lower billing and payment activity.  
   - Mondays and Tuesdays record the highest weekly transaction volumes.

</td>
</tr>
</table>

---

<h2 align="center">Dataset Structure and ERD (Entity Relationship Diagram)</h2>

<body>
The analytical model is powered by a synthetic dataset designed to replicate realistic utility company payment flows.  
It includes details of transaction modes, customer categories, payment channels, and regional performance across 20 Areas.
</body>

<div align="center">
  <img width="700" src="https://res.cloudinary.com/dxctpvd8v/image/upload/v1739423466/PowerPay_ERD.png" />
</div>

---

<h1 align="center">Insights Deep-Dive</h1>

## Payment Channel Analysis

<div align="center">
  <img width="1633" height="267" alt="PowerPay_Trends" src="https://github.com/user-attachments/assets/ffdc19a4-1366-4a4c-83cc-16639e93dfc2" />

</div>

**Digital (Digital) Payments**
- Online banking, wallets, and app payments dominate, driving **over 80% of total revenue**.
- Wallet and mobile app channels show 25% YoY growth.
- E-banking transactions peak in March and October.

**Conventional (Conventional) Payments**
- Conventional modes (cash, cheque, booth) show a gradual decline, particularly after 2023.
- Booth-based collections maintain relevance only in rural Areas.

---

## Customer Segmentation Insights

<div align="center">
  <img width="1511" height="246" alt="image" src="https://github.com/user-attachments/assets/9bc6dca9-c834-4aa8-8ee5-31f8907944dc" />

</div>

- **Regular customers**: 91% of all users, contributing stable but moderate payment sizes.  
- **Loyalty customers**: 9% share but 1.4× higher average payment and 20% higher on-time rate.  
- Residential customers dominate by volume; commercial customers dominate by value.

---

## Regional (Area) Performance

<div align="center">
  <img width="1651" height="389" alt="PowerPay_Regional" src="https://github.com/user-attachments/assets/75aad1c0-9207-49f6-9264-d350b9209980" />

</div>

- **Top Areas:** Area 3, Area 9, Area 1 — leading in both payments and digital transactions.  
- **Underperformers:** Area 17–20 show lower digital adoption and lower transaction frequency.  
- Consistent quarterly improvements seen in Central and North regions.

---

<h1 align="center">Recommendations</h1>

<ul>
  <h3>Digital Strategy</h3>
  <li>Continue expanding digital payment infrastructure (wallet integrations, app features).</li>
  <li>Introduce <strong>cashback or loyalty points</strong> for customers using online channels.</li>
  <li>Conduct awareness drives in regions lagging in Digital adoption.</li>

  <h3>Customer Experience</h3>
  <li>Promote loyalty programs — loyalty users show higher on-time payment rates and AOV.</li>
  <li>Introduce incentives for commercial users to shift fully to digital billing.</li>

  <h3>Operational Efficiency</h3>
  <li>Automate alerts for low-collection months (June–July).</li>
  <li>Prioritize digital collection expansion in underperforming Areas (Area 17–20).</li>

  <h3>Performance Optimization</h3>
  <li>Use predictive models to forecast seasonal payment dips and prevent revenue shortfall.</li>
  <li>Link customer complaint data with payment records to correlate service quality with collection rates.</li>
</ul>

---

<h2 align="center">Tools & Technologies</h2>

<div align="center">
  <p>Power BI | Excel | Python (Data Simulation) | Pandas | GitHub</p>
</div>

---

<h2 align="center">Disclaimer</h2>

<p align="center">
All data presented in this dashboard are <strong>synthetically generated</strong> for learning and demonstration purposes only.  
PowerPay and the data referenced are entirely fictional.
</p>
