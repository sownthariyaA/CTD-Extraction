# CTD-Extraction
This project involves the extraction, processing, and seasonal analysis of Conductivity-Temperature-Depth (CTD) profiles collected onboard RV Sindhu Sadhana. The study focuses on identifying oceanographic patterns and anomalies over seasonal cycles in the Arabian Sea region.

Project Objectives:
'''Extract CTD profile data collected from the RV Sindhu Sadhana cruise expedition
Clean, preprocess, and organize multi-depth temperature, salinity, and pressure datasets
Perform seasonal trend analysis of oceanographic parameters (Winter, Summer, Monsoon, Post-Monsoon)
Visualize depth-wise variability and identify anomalies across time and space
Build reproducible analysis pipelines for further ocean climate research'''



ctd-analysis/
│
├── data/
│   └── raw/                # Raw CTD files (Excel, .txt, or .csv formats)
│   └── processed/          # Cleaned and preprocessed data
│
├── notebooks/
│   └── 01_data_cleaning.ipynb       # Cleaning and formatting CTD data
│   └── 02_seasonal_trend_analysis.ipynb  # Time-series decomposition and plots
│   └── 03_anomaly_detection.ipynb   # Highlighting unusual patterns
│
├── plots/
│   └── seasonal_trends/            # Line plots, heatmaps, etc.
│
├── README.md
└── requirements.txt                # Python package dependencies

