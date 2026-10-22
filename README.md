# U.S. Obesity and Food Environment Analysis

**BA780 – Introduction to Data Analytics · Boston University Questrom School of Business · Team B09**

What's behind the large gap in adult obesity between U.S. states, and where should a state public-health department focus a limited prevention budget? This project combines CDC BRFSS survey data with the USDA Food Environment Atlas to study how income, demographics and the food environment relate to adult obesity across all 50 states and DC.

## Key findings

- Adult obesity rose from 27.4% in 2011 to 33.1% in 2024. In 2022, state rates ranged from 24.3% (Washington, DC) to 41.0% (West Virginia).
- Wealthier states have lower obesity (r = −0.71), yet adults in the same income bracket still have very different obesity rates depending on their state.
- States with more dollar stores per person have higher obesity (r = +0.62), while states with more full-service restaurants (r = −0.69) and recreation facilities (r = −0.49) have lower obesity.
- In high-obesity states, even groups that usually have lower obesity (college graduates and higher earners) are above the all-state average.

All relationships are state-level correlations, not proof of cause and effect.

## Contributors

- Bhavya Kandhari
- Zoya Salman
- Danyang (Lucy) Qin
- Sanjay Kumar
- Dylan Rubenstein

## Data sources

- CDC BRFSS – Nutrition, Physical Activity, and Obesity (2011–2024): https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system
- USDA ERS Food Environment Atlas (2025): https://ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads

## Files

- `B09_Obesity_and_Food_Enivornment_Analysis.ipynb`: final project notebook (data cleaning, analysis, charts, conclusions, challenges and generative AI disclosure)

## How to run

1. Open the notebook in Google Colab.
2. Download the datasets above and put `BRFSS_Obesity.csv`, `StateAndCountyData.csv` and `VariableList.csv` in your Google Drive at `MyDrive/780-project/data/`.
3. Run all cells.
