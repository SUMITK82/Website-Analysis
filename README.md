# Website Data Analysis

This project analyzes website traffic data to understand user engagement, channel performance, and session patterns.

## Project Structure
```
.
├── Data.ipynb               # Main Jupyter notebook with analysis
├── Website.csv              # Source data file
├── images/                  # Directory for generated visualizations
│   ├── Avg_Engagement_time.png
│   ├── Channel_Performance_Area_Chart.png
│   ├── Correlation_Heatmap.png
│   ├── Engagement_Rate_by_Channel.png
│   ├── Engagement_Rates_Vs_Sessions_Over_time.png
│   ├── Engaged_vs_Non-Engaged_Sessions.png
│   ├── Hourly_Engagement_by_Channel.png
│   ├── Sessions_by_DayOfWeek.png
│   ├── Top_Performing_Time_Slots.png
│   ├── Traffic_by_Hour_and_Channel.png
│   ├── Users_By_Channel.png
│   └── user_Over_time.png
├── README.md                # This file
└── requirements.txt         # Python dependencies
```

## Setup

1. **Prerequisites**
   - Python 3.7+
   - Jupyter Notebook
   - Required Python packages (install via `pip install -r requirements.txt`)

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Running the Analysis**
   - Open `Data.ipynb` in Jupyter Notebook
   - Run all cells to execute the analysis

## Analysis Includes

- User engagement trends over time
- Channel performance comparison
- Session analysis (engaged vs non-engaged)
- Hourly and daily traffic patterns
- Correlation between different metrics
- Top performing time slots

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## Output

All visualizations are automatically saved in the `images/` directory as PNG files.

## License

[Specify your license here, if any]
