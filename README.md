# La Liga Data Analysis & Champion Prediction (2014–2025)

This repository contains my practice project for La Liga data analysis and champion prediction.
I **followed a YouTube tutorial** to reproduce the basic workflow and then experimented with my own ideas.

## Files
- Data_scraping.ipynb: Web scraping workflow (following the tutorial)
- LaLiga_data_analysis.ipynb: Feature engineering, modeling, evaluation
- la_liga_data_2014_2025.csv: Season-level team data (2014–2025)

## Notes
- Started by following a YouTube video (learning purpose), then modified parts (leak-free lag features, LOSO CV, calibration).
- Data sources: public football stats sites (e.g., FBref). Check their terms of use.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
```

## License
For learning and personal research purposes.
