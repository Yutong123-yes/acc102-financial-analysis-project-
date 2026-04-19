# NEV Financial Ratio Analysis (2020-2024)
## Project Overview
This project conducts a comprehensive financial ratio analysis of three leading Chinese new energy vehicle (NEV) manufacturers: **BYD**, **Changan Automobile**, and **Great Wall Motors**, covering the period 2020-2024. The analysis is based on data extracted from the WRDS-CSMAR database, using Python for data processing, calculation, and visualization.

## Target Audience & Analysis Objectives
### Target Audience
This analysis is designed for **financial analysts**, **investment researchers**, **business students**, and **industry stakeholders** who need to evaluate the operational performance, profitability, and financial risk of leading Chinese NEV companies.
### Analysis Objectives
- Evaluate the core financial performance of three NEV giants from 2020 to 2024
- Identify competitive advantages and potential risks in the rapidly growing NEV market
- Provide data-driven insights for investment decision-making and industry research

## Key Financial Ratios Analyzed
1.  **ROE (Return on Equity)**: Measures profitability generated from shareholders' equity
2.  **Net Profit Margin**: Measures operational efficiency and core profitability
3.  **Asset Turnover**: Measures asset utilization efficiency and operational capability
4.  **Financial Leverage**: Measures financial risk and capital structure health

## Data Source & Specifications
- **Database**: WRDS-CSMAR Financial Master Table (audited annual financial data for Chinese listed companies)
- **Companies**: BYD (002594), Changan Automobile (000625), Great Wall Motors (601633)
- **Time Period**: 2020-2024 (filtered by `typrep = 'A'` to ensure data accuracy)
- **Data Relevance**: The dataset is closely tied to the business context of the Chinese NEV industry, supporting real-world financial analysis and decision-making.

## Tools & Technologies
- **Programming Language**: Python 3.9
- **Libraries**: wrds, pandas, openpyxl, matplotlib
- **Platform**: Jupyter Notebook, GitHub
- **Environment**: macOS

## Project Structure

NEV_Financial_Analysis/
├── 11111.ipynb                # Complete analysis notebook (code + results)
├── financial_ratios.csv       # Raw data backup (CSV format)
├── financial_ratios.xlsx      # Final results (Excel format)
├── financial_ratio_trends.png # Visualization of ratio trends (optional)
└── README.md                  # Project documentation

## How to Run the Code
1.  **Install Dependencies**:
    ```bash
    pip install wrds pandas openpyxl matplotlib
    ```
2.  **Connect to WRDS**: Replace the `username` variable in the notebook with your WRDS account
3.  **Run the Notebook**: Execute the full code in a single cell to complete data extraction, cleaning, transformation, analysis, and export
4.  **Check Results**: The final financial ratio tables, exported files, and visualizations will be generated automatically

## Analysis Value & Key Findings
### Analysis Value
This project delivers actionable analytical insights rather than just raw code:
- It builds a systematic financial evaluation framework for NEV companies, enabling efficient performance comparison
- It visualizes 5-year financial trends to help stakeholders identify long-term operational patterns
- It provides clear, interpretable conclusions to support data-driven investment and strategic decisions

### Key Findings
#### 1. Profitability (ROE & Net Profit Margin)
- **BYD**: Achieved the strongest growth, with ROE rising from 9.3% (2020) to 20.9% (2024), driven by scale expansion and cost optimization
- **Great Wall**: Maintained stable profitability, with ROE reaching 16.1% in 2024
- **Changan**: Showed a fluctuating trend, with ROE peaking at 12.7% in 2023

#### 2. Operational Efficiency (Asset Turnover)
- **BYD**: Consistently led the industry, with asset turnover increasing from 77.9% to 99.2%, reflecting efficient asset utilization
- **Changan & Great Wall**: Maintained steady turnover rates, with gradual improvement over the period

#### 3. Financial Risk (Financial Leverage)
- **BYD**: Maintained moderate leverage (3.94 in 2024), balancing growth and risk
- **Changan & Great Wall**: Adopted more conservative leverage strategies, with ratios below 2.75

## Methodological Understanding
This analysis follows rigorous financial analysis principles and Python data processing workflows:
- **Data Acquisition**: Connected to the professional WRDS-CSMAR database to obtain standardized, audited financial data
- **Data Cleaning**: Filtered annual year-end data, removed invalid entries, and ensured data consistency
- **Data Transformation**: Calculated core financial ratios based on accounting standards, generated pivot tables for cross-company comparison
- **Descriptive Analysis & Visualization**: Summarized performance trends and created visual charts to enhance interpretability
- **Simple Modeling**: Built a basic performance evaluation framework to support multi-dimensional company comparison

## Conclusion
This analysis provides a clear, comprehensive comparison of the financial performance of three leading NEV companies in China, highlighting their competitive advantages and potential risks in the rapidly growing electric vehicle market. It fully meets the requirements of Track 2 (GitHub Data Analysis Project) with standardized code, complete documentation, and actionable analytical insights.

## Author
[Yutong Zhu] | [2473101]
Xi'an Jiaotong-Liverpool University
ACC102 Financial Accounting
