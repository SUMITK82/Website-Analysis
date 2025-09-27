<div align="center">

# 🌐 Website Traffic Analysis Dashboard

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![Website Analytics Dashboard](https://img.shields.io/badge/Website-Analytics-2ea44f?style=for-the-badge&logo=google-analytics)

</div>

## 📊 Project Overview

A comprehensive analysis of website traffic data to derive actionable insights into user behavior, channel performance, and engagement metrics. This project utilizes Python's data science stack to process, analyze, and visualize website analytics data.

<div align="center">
  <h3>📈 Key Performance Metrics</h3>
  <div style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
    <div style="flex: 1; min-width: 45%;">
      <img src="images/Engagement_Rates_Vs_Sessions_Over_time.png" alt="Engagement vs Sessions Over Time" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
      <p style="text-align: center; font-style: italic; color: #666; margin-top: 8px;">Figure 1: Engagement rates and session trends over time</p>
    </div>
    <div style="flex: 1; min-width: 45%;">
      <img src="images/Channel_Performance_Area_Chart.png" alt="Channel Performance Over Time" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
      <p style="text-align: center; font-style: italic; color: #666; margin-top: 8px;">Figure 2: Channel performance distribution and trends</p>
    </div>
  </div>
  
  <h3>🔍 Detailed Analysis</h3>
  <div style="display: flex; flex-direction: column; gap: 30px; margin: 20px 0;">
    <div style="background: #f8f9fa; padding: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
      <h4>Engaged vs Non-Engaged Sessions</h4>
      <div style="display: flex; justify-content: center; margin: 15px 0;">
        <img src="images/Engaged_vs_Non-Engaged_Sessions.png" alt="Engaged vs Non-Engaged Sessions" style="max-width: 100%; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      </div>
      <p style="text-align: center; font-style: italic; color: #666; margin-top: 10px;">
        Figure 3: Distribution of engaged vs non-engaged sessions, showing the proportion of users who actively interacted with the website content
      </p>
    </div>
    
    <div style="background: #f8f9fa; padding: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
      <h4>Channel Performance Over Time</h4>
      <div style="display: flex; justify-content: center; margin: 15px 0;">
        <img src="images/Channel_Performance_Area_Chart.png" alt="Channel Performance Over Time" style="max-width: 100%; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      </div>
      <p style="text-align: center; font-style: italic; color: #666; margin-top: 10px;">
        Figure 4: Comprehensive view of channel performance trends over time, highlighting the dominance of Organic Social traffic
      </p>
    </div>
  </div>
</div>

## 🗂 Project Structure

```
website-analysis/
├── Data.ipynb               # Jupyter notebook containing the complete analysis
├── Website.csv              # Raw dataset (not included in repo)
├── images/                  # Generated visualizations
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
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SUMITK82/Website-Analysis.git
   cd Website-Analysis
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Then open `Data.ipynb` to view and run the analysis.


## 🔍 Key Insights

### 📈 Traffic Analysis
- **User Engagement Trends**: Analyze how user engagement changes over time
- **Session Patterns**: Understand peak traffic hours and days
- **Channel Performance**: Compare effectiveness of different traffic sources

### 📊 Visualizations
<div align="center">
  <img src="images/Traffic_by_Hour_and_Channel.png" alt="Traffic Heatmap" width="80%">
  <p><em>Figure: Hourly traffic distribution across different channels</em></p>
</div>

### 📈 Engagement Metrics
- **Engagement Rate**: Measure of user interaction quality
- **Session Duration**: Average time spent per session
- **Bounce Rate**: Percentage of single-page visits

<div align="center">
  <img src="images/Engaged_vs_Non-Engaged_Sessions.png" alt="Engaged vs Non-Engaged Sessions" width="70%">
</div>

## 🛠️ Dependencies

- [pandas](https://pandas.pydata.org/) - Data manipulation and analysis
- [numpy](https://numpy.org/) - Numerical computing
- [matplotlib](https://matplotlib.org/) - Basic plotting
- [seaborn](https://seaborn.pydata.org/) - Statistical data visualization
- [jupyter](https://jupyter.org/) - Interactive computing

## 📦 Project Structure

- `Data.ipynb`: Main notebook containing the analysis
- `images/`: Directory containing all generated visualizations
- `requirements.txt`: List of Python dependencies

## 📊 Example Visualizations

<div align="center">
  <img src="images/Correlation_Heatmap.png" alt="Correlation Heatmap" width="45%">
  <img src="images/Users_By_Channel.png" alt="Users by Channel" width="45%">
</div>

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- [Google Analytics](https://analytics.google.com/) for the data
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for visualization
- [Jupyter](https://jupyter.org/) for interactive computing

---
<div align="center">
  Made with ❤️ by Sumit Kumar | [GitHub](https://github.com/SUMITK82)
</div>
