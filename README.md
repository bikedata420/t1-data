[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)


# Training Data Export

![Sync Status](https://github.com/bikedata420/t1-data/actions/workflows/auto-sync.yml/badge.svg)

**Last successful sync:** 2026-01-20 23:41:13 UTC

Automated export of cycling training data from Intervals.icu for AI analysis.

## 📊 Data URL
- **Latest**: https://raw.githubusercontent.com/bikedata420/t1-data/main/latest.json
- **Archive**: Historical snapshots in `/archive/` folder

## 🔄 Auto-Sync
Data syncs automatically every 15 minutes from Intervals.icu.

## 📋 Data Included
- **Performance**: Power, HR, cadence, speed, pace
- **Energy**: Work (kJ), calories, carbs used/ingested
- **Efficiency**: Variability Index, decoupling, intensity factor
- **Zones**: HR zones (Z1-Z7), Power zones (Z1-Z7)
- **Environment**: Temperature, weather, humidity, wind (when available)
- **Wellness**: HRV, resting HR, sleep, fatigue
- **Training load**: TSS, CTL, ATL, TSB

## 💬 AI Analysis
Share the latest.json URL with any AI assistant:
```
Analyze my training data from https://raw.githubusercontent.com/bikedata420/t1-data/main/latest.json
```

Example questions:
- "Am I overtraining based on my TSB and HRV trends?"
- "Analyze my zone distribution and intensity balance"
- "Review my fueling strategy based on carbs used"
- "What does my decoupling suggest about aerobic fitness?"


## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

You're free to use, share, and adapt this protocol for personal and non-commercial use.
Attribution required. For commercial licensing, contact me.
