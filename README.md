# 🛫 IATA Airport Distance Calculator

This project calculates the geographical distances between airports using IATA codes and coordinates, based on a full global airport list. It can be used to analyze travel routes, identify the nearest airports, or estimate route lengths for aviation-related logistics.

## 📂 Dataset
- Source: [Open IATA Airport Dataset on GitHub](https://github.com/lxndrblz/Airports)
- Fields: IATA Code, Airport Name, Country, Latitude, Longitude, Altitude, etc.

## 🔧 Tools Used
- Language: R 
- Libraries: `geosphere`, `dplyr`, `tidyverse`

## 🧠 Methodology
1. Cleaned and filtered airport data to include only valid IATA-coded airports.
2. Applied the Haversine formula to calculate distances between selected airport pairs.
3. Created summary tables of distances and visualized key insights.

## 📊 Key Outputs
- Longest and shortest distances between global airports.
- Distance matrix between airport hubs.
- [Optional] Interactive map or chart showing flight path distances.

## 📎 Files in This Repo
- `data/iata_airports.csv`: Raw dataset
- `scripts/distance_calculation.R`: Distance calculation logic
- `output/results.csv`: Distance results

## 📌 Future Work
- Estimate flight durations and CO₂ emissions
- Add mapping with `leaflet` or `ggmap`
- Create a Shiny dashboard

