# plp-da-a2-rainfall-advisory

# County Rainfall and Planting Advisory

## Project Summary
This project cleans raw weather station rainfall records, analyzes precipitation patterns across five Kenyan counties using NumPy, identifies optimal two-month planting windows, and exports a summary CSV (`rainfall_summary.csv`) to guide farmer-support SMS advisories.

## How to Run
You can open and execute the analysis interactively via Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rakelcey/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

Alternatively, run the Jupyter notebook locally after installing dependencies:
```bash
pip install -r requirements.txt
jupyter notebook rainfall_analysis.ipynb


Planting Advisory
Farmers in Nairobi, Nakuru, Kisumu, and Mombasa should target the April–May planting window, which delivers peak two-month cumulative rainfall ranging from 265 mm in Nakuru to 420 mm in Kisumu.

Farmers in Machakos should prioritize the November–December planting window (278 mm combined rainfall) and adopt drought-tolerant crops to manage its 5 dry months per year.

SMS advisories should note that missing Machakos readings for April and September were imputed using the station's valid monthly average (68 mm), which may slightly underestimate true short-rains totals.


