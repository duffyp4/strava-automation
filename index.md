# Training Data - Enhanced Daily Files

This repository contains comprehensive training data with detailed per-split metrics, 
weather interpolation, and Garmin wellness data in organized daily files.

## Recent Activities

- **[Monday, July 07, 2025](data/2025/07/07.md)** - 1 workout, 8.0 miles


## Monthly Summary

- **July 2025**: 1 workouts, 8.0 miles


## Enhanced Features

- **📊 Detailed Splits**: Per-mile HR, pace, cadence, stride, power, weather
- **🌤️ Real Weather**: Historical temperature data via Visual Crossing API
- **😴 Wellness Data**: Sleep stages, HRV, body battery, resting HR
- **🏃 Running Dynamics**: GCT, vertical oscillation, power, balance
- **📁 Organized Structure**: Daily files with YAML frontmatter
- **🔄 Automated Collection**: Nightly sync with latest Garmin data

## Directory Structure

```
data/
├── YYYY/
│   ├── MM/
│   │   ├── DD.md (enhanced daily summary)
│   │   └── ...
│   └── ...
└── ...
```

## Schema Version 2

Each daily file contains:
- **daily_metrics**: Sleep, HRV, steps, totals
- **workout_metrics**: Enhanced workouts with detailed splits
- **Front matter**: YAML for easy parsing
- **Weather data**: Real historical temperatures per split
- **Multiple workouts**: Support for multi-workout days

## Data Sources

- **Garmin Connect**: Primary activity and wellness data
- **Visual Crossing**: Historical weather and temperature data
- **FIT Files**: Detailed per-second metrics and running dynamics
