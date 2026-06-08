# Data Analysis 

- scripts for analyzing cleaned Eugene CAD data and SPR Calls for Service data


# Contents

analysis.ipynb: Loads the files "EUG_cleaned.csv" and "SPR_cleaned.csv" (located in "../data/") and outputs four graphs with p-values for four difference in difference analyses using Eugene, Oregon as the treatment group and Springfield, Oregon as the control group. The 4 analyses are:
1) Total CAD calls per 1000 people
2)  Welfare check calls per 1000 people
3) Police dispatches to welfare check calls per 1000 people
4) Welfare check calls per 1000 people with no dispatch

Output files:
1) total_calls_per_1000.png
2) welfare_check_calls_per_1000.png
3) police_welfare_checks_per_1000.png
4) nodisp_welfare_checks_per_1000.png

# Libraries Used

- numpy, pandas, datetime, matplotlib, seaborn, diff-diff