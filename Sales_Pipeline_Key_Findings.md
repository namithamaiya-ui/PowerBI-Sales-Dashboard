[Sales_Pipeline_Key_Findings.md](https://github.com/user-attachments/files/32900662/Sales_Pipeline_Key_Findings.md)

# 📊 Sales Pipeline Dashboard — Key Findings

## 🔎 Project Overview

This Power BI project analyzes a B2B manufacturing sales pipeline across regions, industries, products, sales stages, and lead sources.

**Sales lifecycle:** Fresh Lead → NDA → Customer Audit → RFQ → Won / Lost

It also includes **Existing Customers** to understand repeat-business opportunities.

---

## 📌 Key Business Findings

### 🌍 1. Regional Sales Performance

| Region | Opportunities | Open Pipeline | Won Value | Lost Value |
|---|---:|---:|---:|---:|
| **East** | 272 | ₹11.30 Cr | ₹4.39 Cr | ₹6.53 Cr |
| **West** | 246 | ₹11.19 Cr | **₹4.72 Cr** | ₹5.03 Cr |
| **North** | 251 | ₹11.15 Cr | ₹4.52 Cr | ₹4.55 Cr |
| **South** | 231 | ₹7.83 Cr | ₹3.02 Cr | ₹6.41 Cr |

**Key observations**
- **East** has the highest number of opportunities and the largest open pipeline.
- **West** generated the highest won sales value.
- **South** has the smallest open pipeline and a comparatively high lost value.

---

### 🏭 2. Industry Performance

| Industry | Opportunities | Total Opportunity Value | Won Value | Closed Win Rate |
|---|---:|---:|---:|---:|
| Industrial Equipment | 137 | ₹13.58 Cr | **₹3.52 Cr** | 55.6% |
| Electronics Manufacturing | 125 | ₹11.51 Cr | ₹3.26 Cr | **58.2%** |
| Automotive | 111 | ₹11.47 Cr | ₹2.26 Cr | 51.1% |
| Aerospace & Defense | 125 | ₹10.21 Cr | ₹2.03 Cr | 42.3% |
| Heavy Engineering | 157 | **₹14.70 Cr** | ₹1.66 Cr | 37.1% |
| Railways | 144 | ₹10.65 Cr | ₹1.56 Cr | 42.9% |
| Oil & Gas | 122 | ₹11.83 Cr | ₹1.23 Cr | 31.7% |
| Marine Engineering | 79 | ₹7.36 Cr | ₹1.11 Cr | 31.4% |

**Key observations**
- **Electronics Manufacturing** has the highest closed-opportunity win rate at **58.2%**.
- **Industrial Equipment** generated the highest won value at **₹3.52 Cr**.
- **Heavy Engineering** has the largest total opportunity value, but its closed win rate is **37.1%**.
- **Oil & Gas** and **Marine Engineering** have comparatively lower closed win rates.

---

### 🔄 3. Sales Pipeline & Stage Analysis

| Stage | Opportunities | Total Deal Value |
|---|---:|---:|
| Lost | 219 | **₹22.52 Cr** |
| Won | 176 | ₹16.64 Cr |
| Fresh Lead | 149 | ₹12.98 Cr |
| Existing Customer | 144 | ₹10.70 Cr |
| RFQ | 93 | ₹10.07 Cr |
| Customer Audit | 107 | ₹9.26 Cr |
| NDA | 112 | ₹9.16 Cr |

**Key observations**
- The **Lost** stage contains the highest total deal value at **₹22.52 Cr**.
- **RFQ** has the highest average deal value at approximately **₹10.82 lakh** per opportunity.
- A significant amount of value remains in opportunities that have not yet reached a final outcome.

---

### 🎯 4. Lead Source Performance

| Lead Source | Opportunities | Won Value | Closed Win Rate |
|---|---:|---:|---:|
| **Existing Customer Upsell** | 246 | **₹3.06 Cr** | **62.5%** |
| Industry Association | 126 | ₹2.45 Cr | 51.9% |
| Referral | 93 | ₹2.16 Cr | 55.3% |
| Cold Outreach | 80 | ₹2.21 Cr | 31.0% |
| LinkedIn | 102 | ₹2.16 Cr | 47.1% |
| Trade Show | 99 | ₹1.69 Cr | 44.9% |
| RFP Portal | 86 | ₹1.43 Cr | 44.2% |
| Website Inquiry | 94 | ₹0.90 Cr | 33.3% |
| Partner Network | 74 | ₹0.58 Cr | 27.3% |

**Key observations**
- **Existing Customer Upsell** generated the highest won value and the highest closed win rate.
- **Referral** also shows a relatively strong closed win rate.
- **Partner Network** and **Cold Outreach** have comparatively lower closed win rates.

---

### 📦 5. Product & Category Performance

Top products by won value include:

| Product | Won Value |
|---|---:|
| Electronic Control Enclosure | **₹1.95 Cr** |
| Anodized Aluminum Extrusion Kit | ₹1.35 Cr |
| Defense Grade Armor Plate Component | ₹1.30 Cr |
| Heat Exchanger Assembly | ₹1.19 Cr |
| Robotic Welding Fixture | ₹1.05 Cr |

Top categories by won value include:

| Category | Won Value |
|---|---:|
| Precision Machining | **₹2.38 Cr** |
| Electronics Enclosures | ₹1.95 Cr |
| Tooling & Fixtures | ₹1.49 Cr |

---

## 💡 Overall Business Insights

1. **East has the largest open pipeline**, with approximately ₹11.30 Cr in open opportunities.
2. **West generated the highest won sales value**, at approximately ₹4.72 Cr.
3. **Electronics Manufacturing has the highest closed win rate**, at 58.2%.
4. **Industrial Equipment generated the highest won value by industry**, at approximately ₹3.52 Cr.
5. **Heavy Engineering has the largest total opportunity value**, but its closed win rate is 37.1%.
6. **RFQ opportunities have the highest average deal size**, at approximately ₹10.82 lakh.
7. **Existing Customer Upsell** has a 62.5% closed win rate and ₹3.06 Cr in won value.
8. The **Lost stage contains ₹22.52 Cr of opportunity value**, making loss analysis an important area for further investigation.
9. **Electronic Control Enclosures and Precision Machining** contribute substantially to won sales value.

---

## 📈 Business Questions Answered

This dashboard helps answer:

- Which region has the largest sales pipeline?
- Which region generated the highest won sales?
- Which industries are progressing successfully through the pipeline?
- Which industries have higher win/loss outcomes?
- Which sales stages contain the most opportunity value?
- Which lead sources generate better conversion outcomes?
- Which products and categories contribute the most to won sales?
- Where is opportunity value being lost?
- Which areas may require further sales investigation?

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **SQL**
- **CSV / Excel**
- **AI-assisted analysis and development**

---

## 📝 Note

The findings are based on the opportunity dataset used in this Power BI project. Win rate is calculated using **closed opportunities (Won + Lost)** where specified.
