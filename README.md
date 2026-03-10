 # 🏦 Bank Loan Report — Power BI Dashboard

> **Project Type:** Data Analytics & Business Intelligence  
> **Tool:** Microsoft Power BI  
> **Pages:** 3 (Summary · Overview · Details)

<img width="1011" height="602" alt="image" src="https://github.com/user-attachments/assets/232751e6-2a08-4f4f-96f4-f4a687f581fc" />
<img width="1013" height="597" alt="image" src="https://github.com/user-attachments/assets/ef71e06d-d9c9-4b8d-a58a-ce4966a8be11" />
<img width="1010" height="607" alt="image" src="https://github.com/user-attachments/assets/150b3885-f970-45e0-bf4c-fa55eae7be0d" />

---

## 📌 Overview

The **Bank Loan Report** is a multi-page interactive Power BI dashboard designed to monitor and analyze a bank's loan portfolio performance. It provides key insights into loan applications, funded amounts, repayment behavior, and loan quality — enabling data-driven decisions for risk management and lending strategy.

---

## 📷 Dashboard Pages

### 1️⃣ Summary Page
<img width="1011" height="602" alt="image" src="https://github.com/user-attachments/assets/fdd2ee4b-fe0b-4509-a3c0-fec2957ba5c3" />
 

- High-level KPIs with Month-over-Month (MoM%) and Month-to-Date (MTD) tracking
- **Loan Quality** donut chart — Good Loans (85.88%) vs Bad Loans (14.12%)
- Good Loan vs Bad Loan breakdown: total applications, funded amount, amount received
- **Loan Status Table** — Fully Paid, Charged Off, Current with full financial breakdown

### 2️⃣ Overview Page
<img width="1013" height="597" alt="image" src="https://github.com/user-attachments/assets/ef71e06d-d9c9-4b8d-a58a-ce4966a8be11" />

- Monthly trend of total loan applications (area chart)
- Geographic distribution by U.S. state (map visual)
- Loan applications by **employment length**, **purpose**, **term**, and **home ownership**

### 3️⃣ Details Page
<img width="1010" height="607" alt="image" src="https://github.com/user-attachments/assets/e3c92152-fc35-488d-9f3d-ecb580869f90" />

- Granular loan-level data table
- Fields: ID, Purpose, Home Ownership, Grade, Interest Rate, Year, Month, Day, Funded Amount, Installment, Amount Received

---

## 📊 Key KPIs Tracked

| KPI | Value | MoM % | MTD |
|-----|-------|--------|-----|
| Total Loan Applications | 38.6K | 12.59% | 4K |
| Total Funded Amount | $435.8M | 14.14% | $54M |
| Total Amount Received | $473.1M | 13.99% | $58M |
| Average Interest Rate | 12.05% | 2.9% | 0.12 |
| Average DTI | 13.33% | 2.87% | 0.14 |

---

## 🟢 Loan Quality Analysis

| Category | Applications | Funded Amount | Amount Received |
|----------|-------------|---------------|-----------------|
| **Good Loans** | 33,243 | $370,224,850 | $435,786,170 |
| **Bad Loans** | 5,333 | $65,532,225 | $37,284,763 |

---

## 🔍 Loan Status Breakdown

| Status | Applications | Funded Amount | Amount Received | Avg DTI | Avg Interest Rate |
|--------|-------------|---------------|-----------------|---------|-------------------|
| Fully Paid | 32,145 | $351,358,350 | $411,586,256 | 13.17% | 11.64% |
| Charged Off | 5,333 | $65,532,225 | $37,284,763 | 14.00% | 13.88% |
| Current | 1,098 | $18,866,500 | $24,199,914 | 14.72% | 15.10% |
| **Total** | **38,576** | **$435,757,075** | **$473,070,933** | **13.33%** | **12.05%** |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualizations |
| **DAX** | KPI measures — MoM%, MTD, Good/Bad Loan metrics |
| **Power Query (M)** | Data cleaning and transformation |
| **Excel / CSV** | Source loan data |
| **Bing Maps** | Geographic distribution visual |

---

## 📁 File Structure

```
Bank-Loan-Report/
│
├── Bank_Loan_Report.pbix        # Main Power BI file
├── data/
│   └── loan_data.csv            # Source dataset
├── screenshots/
│   ├── summary_preview.png
│   ├── overview_preview.png
│   └── details_preview.png
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

### Steps
1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/Bank-Loan-Report.git
   ```
2. **Open the report**  
   Launch `loan.pbix` in Power BI Desktop

3. **Load data**  
   If prompted, point the data source to `financial_loan.csv`

4. **Explore**  
   Use the left panel slicers to filter by **State**, **Grade**, **Loan Quality**, and **Loan Status**

---

## 🎛️ Filters / Slicers Available

- **State** — Filter by U.S. state
- **Grade** — Loan grade (A–G)
- **Loan Quality** — Good Loan / Bad Loan
- **Loan Status** — Fully Paid / Charged Off / Current

---

## 💡 Key Insights

- **85.88%** of loans are Good Loans — healthy portfolio quality
- **Debt consolidation** is the #1 loan purpose (18K applications)
- **10+ years employment** applicants have the highest loan volume (8.9K)
- **73.2%** of loans are on a 60-month term vs 26.8% on 36-month
- Loan applications grew steadily throughout the year, peaking in **December (4.3K)**
- **Rent and Mortgage** holders dominate home ownership categories

---

## 👤 Author

**Laiba**  
Final Year Student | Computer Science  
 [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/laiba-a2834227b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/laiba26-aslam)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](laibaslam383@gmail.com)


---

 > *Built to demonstrate end-to-end Power BI development — data modeling, DAX measures, and interactive storytelling* 🚀
