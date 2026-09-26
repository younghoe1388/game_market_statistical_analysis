## Game Market Statistical Inference & Regional Analytics
An exploratory and inferential data analysis on global video game historical sales (16,000+ records) using R. This project focuses on regional sales distributions, cross-region market correlations, and a Bayesian approach to predicting genre success rates.   

## 📌 Key Insights & Findings
-Regional Market Alignment: Pearson correlation tests reveal a strong linear relationship between North American (NA) and European (EU) sales ($r = 0.77, p < 2.2 \times 10^{-16}$), whereas Japanese (JP) market preferences align significantly less with NA ($r = 0.45, p < 2.2 \times 10^{-16}$).   

-Genre Hit Rates (Bayesian Model): Formulated a Bayesian probability model to calculate posterior probabilities for games reaching "blockbuster" status (>1M units sold).   $P(\text{Hit} \mid \text{Action}) \approx 19.3\%$   
$P(\text{Hit} \mid \text{Strategy}) \approx 6.5\%$   

-Conclusion: Action games have roughly 2.98x higher likelihood of hitting 1M+ sales compared to Strategy games.   

## 🛠️ Tech Stack & Methods
-Language: R   

-Libraries: tidyverse, dplyr, ggplot2, ggrepel   

-Statistical Methods:
  -Exploratory Data Analysis (EDA) & Data Reshaping (pivot_longer)   
  -Pearson Correlation & Hypothesis Testing (cor.test)   
  -Posterior Probability Analysis via Bayes' Theorem   

## 📂 Project Structure
.
├── data/
│   └── vgsales.csv          # Global video game sales data
├── analysis.R      # Data cleaning, visualization & statistical models
├── output_result.docx
├── presentation.pptx
└── README.md

## 🚀 Getting Started
1. Clone the repository:
  git clone https://github.com/your-username/game_market_statistical_analysis.git
  cd game-market-analysis
2.Run the analysis: Open analysis.R in RStudio and execute the script, or run via terminal
  Rscript analysis.R
