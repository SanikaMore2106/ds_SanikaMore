# ds_Sanika_More

This repository contains the Data Science assignment exploring the relationship between trader behavior and the Bitcoin Fear/Greed index.

## 📂 Repository Structure
```
ds_Sanika_More/
├── notebook_1.ipynb       # Main Colab-ready notebook with analysis and plots
├── csv_files/             # Cleaned and processed data files
│   ├── historical_data_clean.csv
│   ├── fear_greed_index_clean.csv
│   └── merged_daily_metrics.csv
├── outputs/               # Visual outputs (charts, graphs)
│   ├── classification_count.png
│   ├── pnl_by_classification.png
│   ├── volume_by_classification.png
│   └── timeseries_totalpnl.png
├── ds_report.pdf          # Final summarized insights and explanations
└── README.md              # Repository documentation
```

## 🚀 How to Use
1. Open `notebook_1.ipynb` in **Google Colab**.
2. Ensure the `csv_files/` folder is available in the working directory.
3. Run all cells to reproduce the analysis and generate plots in `outputs/`.

## 📊 Key Insights
- **Greed periods** → Higher average PnL but increased risk-taking behavior.  
- **Fear periods** → Lower activity and volumes but more stable outcomes.  

## 📝 Notes
- All visualizations are generated using `matplotlib` (no seaborn/styles).
- Sentiment data comes from the Bitcoin Fear & Greed Index (`classification`, `value`).
- Trader data includes PnL, trade sizes in USD, and account-level activity.
