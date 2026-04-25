# ACC102 Track2 Assignment: SBA Loan Data Analysis (2023–2025)

## 1. Problem & User
This project analyzes SBA loan data from 2023 to 2025 to explore loan trends, revenue patterns, and small business financing characteristics. The insights are intended for business analysts, small business advisors, and students interested in public-sector lending patterns.

## 2. Data
- **Source**: SBA loan filtered dataset (`sba_loan_filtered_2023-2025.csv`)
- **Access Date**: 2025-04-20
- **Key Fields**:
  - Loan amount
  - Industry / sector
  - Approval date
  - Revenue indicators
  - Geographic region

## 3. Methods (Main Python Steps)
1.  **Data cleaning and filtering** with pandas: removed duplicates, handled missing values, and filtered the 2023–2025 period.
2.  **Exploratory analysis**: aggregated loan volumes and revenue patterns by year and sector.
3.  **Visualization**: built revenue trend charts using matplotlib to identify patterns over time.
4.  **Trend and fluctuation analysis**: identified periodic changes in SBA loan support distribution.

## 4. Key Findings
- Clear revenue trends are visible across the 2023–2025 period.
- The distribution of SBA loan support remains stable across sectors and regions.
- Identifiable periodic fluctuations exist in loan approval volumes over the years.
- Certain industries show consistent patterns in both loan amounts and revenue indicators.

## 5. How to run (optional but valuable)
1.  Clone this repository to your local machine.
2.  Install the required libraries:
    ```bash
    pip install pandas matplotlib
    ```
3.  Open and run the notebook:
    ```bash
    jupyter notebook ACC102_Analysis.ipynb
    ```
4.  The output chart `revenue_trend.png` will be generated automatically.

## 6. Product link / Demo
- **GitHub Repository**: https://github.com/GeyundiZhang24/ACC102-Track2-Assignment
- **Demo Video**: https://video.xjtlu.edu.cn/Mediasite/Play/d016e2e8dd6b4fd2b5167a366faad7541d

## 7. Limitations & next steps
- The dataset is filtered; future analysis could include the full SBA dataset for broader context.
- The analysis focuses on aggregated trends; deeper correlation testing between loan size and business outcomes is recommended.
- The visualizations are basic; adding interactive plots or additional metrics would improve the presentation.

---
**Author**: GeyundiZhang24 ACC102 Track2
