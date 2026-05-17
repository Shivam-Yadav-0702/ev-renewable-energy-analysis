# ev-renewable-energy-analysis
Data Analytics Capstone analyzing 543,610 US EV registrations and renewable energy correlation across 50 states using Python and Excel
# ⚡ US Electric Vehicle Registrations & Renewable Energy Analysis

## 📌 Objective
Investigate the relationship between EV adoption across US states
and availability of renewable energy using 2018 registration data
and energy generation records from 1990–2019.

## 📊 Key Statistics
| Metric | Value |
|--------|-------|
| Total EV Registrations (2018) | 543,610 |
| States Analyzed | 51 (50 + DC) |
| National Avg EV Adoption Rate | ~0.3% |
| California's Share | ~47% |
| Highest Adoption Rate | 1.73% (California) |
| EV-Renewable Correlation | ~0.62 (moderate-strong) |
| Renewable Share of Grid (2018) | 16.9% |

## 🔍 Key Insights
- California alone accounts for 47% of all US EV registrations
- Top 5 states hold 68% of registrations — market is not truly national
- EV registrations grew 6x from 2012 to 2018 driven by Tesla Model 3
- States with high renewables (WA, CA, OR) also lead in EV adoption
- Texas anomaly: massive renewables but low EV rate due to oil culture
- 62.7% of US electricity still from fossil fuels in 2018
- Wind is fastest growing renewable; solar has massive growth potential

## 💡 Business Recommendations
- Standardize federal EV tax credits — remove automaker caps
- Fund rural EV charging corridors to break the infrastructure gap
- Pair EV adoption policy with grid decarbonization mandates
- Expand ZEV mandates from 13 → 30 states to triple EV market
- EVs on a clean grid reduce emissions by 70% vs gasoline vehicles

  ## 🤖 Predictive Modeling
Built a Linear Regression model to estimate EV registrations
based on state energy generation values.
- Tool: Scikit-learn
- Metrics: MAE, R² Score
- Finding: Positive relationship confirmed between
  energy generation and EV adoption (correlation ~0.62)

## 🚀 How to Run
1. Clone the repo: `git clone <repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `US_EV_Capstone_Project.ipynb` in Jupyter Notebook

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Excel
- Jupyter Notebook

## 📁 Data Sources
- DOT EV Registrations 2018
- EIA Annual Energy Generation 1990–2019
- All Vehicle Registrations 2018 (for adoption rate calculation)

## 📎 Files
- 📄 [Capstone Presentation](./EV_Capstone_Project.pdf)
