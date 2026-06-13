#ACOS Analyzer

##Problem Statement
Developed an Amazon PPC Analyzer using Python, Pandas, and Tkinter that automates Search Term Report analysis. The tool calculates key advertising KPIs including ACoS, CTR, CPC, CVR, and ROAS, classifies keywords into Winner, Watch, and Waste categories based on performance thresholds, identifies negative keyword opportunities, and generates an interactive dashboard with Excel exports. This project demonstrates Amazon PPC optimization, data analysis, automation, and reporting skills.

Amazon advertisers often spend hours manually analyzing Search Term Reports to identify profitable keywords, wasted ad spend, and optimization opportunities. Manual analysis is time-consuming, prone to errors, and can delay critical decisions that impact campaign performance and profitability.

This project aims to automate Amazon PPC analysis by calculating key performance metrics, classifying keyword performance, identifying negative keyword opportunities, and generating actionable insights through an easy-to-use dashboard.


##Data
##Methodology
##Insights
##Recommendations

1. Input Amazon Search Term Report

User uploads:

Search Term Report (.xlsx)
Campaign Report (.xlsx) (optional)

Tools:

Python
Pandas
Tkinter GUI
2. Data Cleaning
Remove blank rows
Convert Spend, Sales, Clicks to numeric
Handle missing values
Standardize column names
3. KPI Calculation

Calculate:

KPI	Formula
CTR	Clicks ÷ Impressions
CPC	Spend ÷ Clicks
CVR	Orders ÷ Clicks
ACoS	Spend ÷ Sales
ROAS	Sales ÷ Spend
TACoS	Spend ÷ Total Sales
4. Performance Classification

Apply business rules:

Winner Keywords
Orders ≥ 2
ACoS ≤ 30%

Action:

Increase bid
Move to Exact Match
Watch Keywords
Clicks > 10
No conversion yet

Action:

Monitor performance
Waste Keywords
Clicks > 20
Orders = 0

Action:

Add as Negative Keyword
5. Negative Keyword Mining

Identify:

High spend, no sales
Irrelevant search terms

Output:

Negative Exact
Negative Phrase
6. Dashboard Generation

Generate:

Top 10 Profitable Keywords
Highest ROAS
Lowest ACoS
Waste Spend Analysis
Total wasted spend
Number of waste keywords
Campaign Summary
Total Spend
Total Sales
Average ACoS
Average ROAS
7. Export Results

Create Excel workbook:

Amazon_PPC_Analysis.xlsx

├── Dashboard
├── Winners
├── Watchlist
├── Waste
├── Negative Keywords
└── Raw Data
8. Visualization

Create charts:

Spend vs Sales
Top 10 Keywords
ACoS Distribution
Campaign Performance
9. GitHub Repository Structure
amazon-ppc-analyzer/
│
├── data/
│   ├── sample_report.xlsx
│
├── screenshots/
│   ├── dashboard.png
│   ├── gui.png
│
├── output/
│   ├── sample_output.xlsx
│
├── src/
│   ├── analyzer.py
│   ├── dashboard.py
│   ├── utils.py
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore


10. GitHub README Flow
Upload Search Term Report
        ↓
Data Cleaning
        ↓
KPI Calculation
        ↓
Performance Classification
        ↓
Negative Keyword Detection
        ↓
Dashboard Creation
        ↓
Excel Export
Portfolio Description

Developed an Amazon PPC Analyzer using Python, Pandas, and Tkinter that automates Search Term Report analysis. The tool calculates key advertising KPIs including ACoS, CTR, CPC, CVR, and ROAS, classifies keywords into Winner, Watch, and Waste categories based on performance thresholds, identifies negative keyword opportunities, and generates an interactive dashboard with Excel exports. This project demonstrates Amazon PPC optimization, data analysis, automation, and reporting skills.










