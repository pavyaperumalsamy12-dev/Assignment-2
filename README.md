# Assignment-2
Statistical Analysis Using Wilcoxon Signed-Rank Test

📌 Project Overview

This project demonstrates statistical analysis using the Wilcoxon Signed-Rank Test in Python. It compares two related datasets generated using Poisson distributions and analyzes the statistical significance of their differences.

🎯 Objectives

- Generate two sets of random Poisson-distributed data.
- Visualize and compare the datasets.
- Perform the Wilcoxon Signed-Rank Test.
- Analyze p-values for different sample sizes and lambda values.
- Visualize statistical results using a heatmap.

🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

📂 Project Structure

Statistical-Analysis/
│
├── 25_stats_ttest_signedRank (1).ipynb
└── README.md

⚙️ Installation

Install the required libraries:

pip install numpy matplotlib scipy jupyter

▶️ How to Run

1. Download or clone this repository.
2. Open Jupyter Notebook.
3. Open the ".ipynb" file.
4. Run all the cells.
5. Observe the statistical results and heatmap visualization.

📊 Methodology

1. Data Generation

- Generates two Poisson-distributed datasets.
- Uses a sample size of 30.
- Compares datasets with different lambda values.

2. Data Visualization

- Uses Matplotlib to display both datasets.
- Shows the differences between paired observations.

3. Wilcoxon Signed-Rank Test

- Uses SciPy's "stats.wilcoxon()" function.
- Calculates the test statistic and p-value.
- Helps evaluate differences between paired samples.

4. Heatmap Visualization

- Tests different sample sizes (5 to 50).
- Evaluates different lambda values (1 to 3).
- Displays statistical results using a heatmap.

📈 Expected Output

- Comparison plot of two datasets.
- Wilcoxon Signed-Rank Test statistic and p-value.
- Heatmap showing statistical results for different sample sizes and lambda values.

📝 Conclusion

This project demonstrates how Python can be used for statistical analysis and hypothesis testing. The Wilcoxon Signed-Rank Test helps compare paired datasets, while heatmap visualization makes it easier to understand statistical patterns.

