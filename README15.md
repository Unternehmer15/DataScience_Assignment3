## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the United Nations Global Terrorism Analysis (UNGTA) dataset. The dataset covers terrorist incidents worldwide from 1970 to 2017, containing over 180,000 records. The analysis uncovers temporal, geographical, and operational patterns in global terrorism, focusing on trends, attack types, targets, and impacts.

## Dataset
- **Source**: United Nations Global Terrorism Analysis (UNGTA) dataset.
- **Size**: 112,550 rows and 135 columns (reduced to 19 key columns after preprocessing).
- **Key Features**: Year, Month, Day, Country, Region, AttackType, Killed, Wounded, Target_type, Weapon_type, etc.
- **Preprocessing**: Handled missing values, renamed columns, created new features like 'total_casualties'.

## Objectives
- Analyze trends in terrorist activities over time.
- Identify geographical hotspots and affected regions/countries.
- Examine attack types, weapons, and target categories.
- Assess casualty impacts (killed and wounded).
- Provide insights for policymakers, security agencies, and researchers.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, wordcloud, missingno
- Install via: `pip install pandas numpy matplotlib seaborn wordcloud missingno`

## Usage
1. Clone or download the Jupyter Notebook.
2. Ensure the dataset file 'Global Terrorism Data.csv' is in the same directory (encoding='latin1').
3. Run the notebook cells sequentially to execute the analysis and generate visualizations.
4. The notebook is designed for deployment-ready execution without errors.

## Analysis Highlights
- **Temporal Trends**: Attacks increased sharply post-2004, peaking in 2014.
- **Attack Types**: Bombing/Explosion is the most common, followed by Armed Assault.
- **Geographical Insights**: Iraq, Pakistan, Afghanistan, and India are top hotspots.
- **Target Types**: Private Citizens & Property are most targeted, followed by Military and Government.
- **Visualizations**: Includes 20+ charts (bar plots, heatmaps, word clouds) following UBM structure (Univariate, Bivariate, Multivariate).

## Key Findings
- Terrorism has escalated globally, with concentrated impacts in specific regions.
- Insights support strategic planning for security and risk mitigation.
- Negative growth implications: Economic disruptions, human capital loss, and reduced investments in affected areas.

## Visualizations
- Number of Attacks per Year
- Distribution of Attack Types
- Top 15 Countries by Attacks
- Word Cloud for Countries
- Distribution of Target Types
- And more (20+ charts with detailed insights on trends, impacts, and business implications).

## Contributors
- Yash Raj Mehta (Individual Contributor)
