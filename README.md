# La Liga Data Analysis & Champion Prediction (2014–2025)

## Acknowledgement
This project was made by watching a YouTube tutorial and typing the code along step-by-step.  
Original video: [La Liga Data Analysis & Champion Prediction](https://youtu.be/Lngf-g369A4?si=k_OB8S77tu1U4PAk) by **Anas Riad**.

## Overview
This repository contains my practice project for La Liga data analysis and champion prediction.  
I initially followed the YouTube tutorial to reproduce the basic workflow, then experimented with my own ideas and improvements.

## Files
- **Data_scraping.ipynb** – Web scraping workflow (from the tutorial)
- **LaLiga_data_analysis.ipynb** – Feature engineering, modeling, evaluation
- **la_liga_data_2014_2025.csv** – Season-level team data (2014–2025)

## Notes
- Started by following a YouTube video for learning purposes, then added modifications (e.g., leak-free lag features, LOSO CV, calibration).
- Data sources: Public football stats sites (e.g., FBref). Please review their terms of use before using the data.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
