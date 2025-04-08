# British Athletics: Medal Prediction and Performance Analysis

This project focuses on predicting potential medal-winning performances by British track and field athletes at the 2025 World Athletics Championships in Tokyo. Using historical performance data and a structured statistical approach, the analysis identifies strong medal contenders and highlights areas of strength and improvement for strategic planning.

## Project Overview

- **Objective**: Predict how many medals Great Britain is likely to win and in which events.
- **Scope**: 19 Olympic track and field events (2019–2024).
- **Outcome**: Data-driven predictions with event-specific performance insights and athlete-level evaluations.

## Methodology

### 1. Data Preparation
- Merged athlete lists with competition results.
- Created unified datasets with flags distinguishing national and global competitions.
- Filtered for final-round performances only.
- Standardised formats, cleaned duplicates, and handled missing values.

### 2. Performance Analysis
- Segmented performances by gender and event type (time-based vs. distance-based).
- Computed statistics (mean, median, min, max, standard deviation).
- Compared GBR athlete stats to global benchmarks to identify strengths.

### 3. Medal Prediction Model
- Introduced a **threshold-based statistical approach** using the third-best global performance per event as the medal benchmark.
- Identified GBR athletes whose final-round performances met or exceeded the benchmark.
- Prioritised global-level performances and removed duplicates for clarity.

### 4. Visualisation & Insight Generation
- Bar charts, heatmaps, and trend lines to highlight:
  - Medal predictions by event
  - Team composition trends
  - Emerging domestic talents
  - Performance gaps between GBR and global athletes

## Key Deliverables

- Jupyter notebooks with complete data pipeline
- Visuals folder with event-specific insights
- Project report in PDF and presentation format
- Cleaned datasets stored in `data/processed/`

## Project Structure
british-athletics-medal-prediction/
├── data/
│   ├── raw/                 # Original CSV datasets
│   └── processed/           # Cleaned and merged datasets
├── notebooks/               # Jupyter Notebooks
├── reports/                 # PDF report and presentation
├── visuals/                 # Generated charts and graphs
├── docs/                    # Limitations, questions for leadership
├── requirements.txt         # Python packages
└── README.md                # Project overview

## Limitations

- Based on historical data only; does not factor in real-time form, injuries, or retirements.
- Medal thresholds are fixed per event and do not account for competition dynamics.
- No emerging global talent or environmental conditions are included.

## Future Improvements

- Integrate athlete biometrics and training data for deeper modelling.
- Use real-time injury/form data feeds.
- Transition to machine learning once richer, more complete datasets are available.

## Author

**Usman Tariq**  
MSc Data Science | University of Surrey  
GitHub: [github.com/your-profile](https://github.com/GloriousGeek)  
LinkedIn: [linkedin.com/in/your-profile](https://www.linkedin.com/in/engrusmantariq/)
