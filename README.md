# Natural Disasters and Economic Resilience

## 🧭 Goal // Guiding Question
Do state/local economies bounce back effectively enough from natural disasters to warrant businesses investing in areas with a high risk of natural disasters?

## 💡 Rationale // Motivations
Climate change is rapidly increasing the rate at which natural disasters occur, with many cities being in high-risk zones.

Evaluation of local/state economies’ resilience to natural disasters is key to deciding whether businesses, both small and large, should invest in expansion/locations in high-risk zones, observing whether it is financially wise to invest in office space and real estate in these areas.

## 📊 Data Collection // Additional Sources
- Compiled a list of 18 natural disasters that affected the United States, creating a CSV file recording:
  - Quarter of the year
  - Affected states
  - Total estimated damages
  - Disaster type

- External data sources used:
  - [Natural Disasters Increasing – Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/natural-disasters-increasing)
  - [Natural Disasters by State – Kaggle](https://www.kaggle.com/datasets/samaneheslamifar/natural-disasters)
  - [Real GDP by State – US BEA](https://apps.bea.gov/itable/?ReqID=70&step=1&_gl=1*1coaqq6*_ga*MTA3NTE3MDUxOS4xNzQzODkxNDQw*_ga_J4698JNNFT*MTc0Mzk0NjIxNy4zLjEuMTc0Mzk0NjIyOC40OS4wLjA)

## 🧪 Data Analysis Methodology
- Utilized **Jupyter notebooks** to analyze data, create visualizations, and identify trends.
- **Unemployment analysis**:
  - Cleaned and transformed datasets to make them comparable.
  - Calculated average unemployment two quarters before, the quarter of, and two quarters after each disaster.
  - Ran a **T-test**, finding a statistically significant difference at a 90% confidence interval (p-value = 0.067).
- **Rent price & availability analysis**:
  - T-tests were used to determine changes in rent prices and availability pre- and post-disaster.
- **Cost savings analysis**:
  - Grouped lease data by disaster.
  - Calculated rent savings using the formula:  
    `[(Avg rent price/ft² before) - (Avg rent price/ft² after)] * (Avg sq ft of leased property in disaster area)`
  - This determined tenant savings ($USD) post-disaster due to decreased rent prices.

## 📈 Conclusions // Direction
- Local and state economies **rebound effectively** from natural disasters:
  - **Unemployment decreases**
  - **GDP increases**
- **Investing in high-risk areas is not financially unwise**.
  - Rent prices often decrease after disasters, presenting savings opportunities for businesses.
  - Leasing shortly after a disaster can lead to economic advantages due to reduced rent and increased availability.

> ⚠️ While short-term impacts are minimal, long-term risks due to climate change remain unclear. More data is needed to understand the long-term effects of repeated natural disasters on state/local economies.
# DukeDataFest2025
