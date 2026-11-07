# Clean Sheet Home Advantage Analysis

## Overview
This project investigates whether home teams keep clean sheets (0 goals conceded) at a significantly higher rate than away teams across European soccer matches using statistical hypothesis testing.

## Technologies Used
* **Language:** Python 3
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy

## Hypothesis Testing
* **Null Hypothesis ($H_0$):** $p_{\text{home}} = p_{\text{away}}$ (Clean sheet rates are equal)
* **Alternative Hypothesis ($H_1$):** $p_{\text{home}} > p_{\text{away}}$ (Home teams have a higher clean sheet rate)
* **Significance Level ($\alpha$):** 0.05
* **Statistical Test:** Chi-Square Test of Independence (`scipy.stats.chi2_contingency`)

## How to Run
1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Upload the `european_top5_matches_sample.csv` dataset.
3. Run all cells sequentially.
