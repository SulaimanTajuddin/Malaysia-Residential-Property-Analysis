# 🏠 Malaysia Residential Property Analysis

A comprehensive exploratory data analysis (EDA) of Malaysian residential property market, uncovering trends, patterns, and insights across different states and districts.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Analysis Highlights](#analysis-highlights)
- [License](#license)
- [Contributing](#contributing)

## Overview

This project provides an in-depth analysis of Malaysia's residential property market using real-world data. It explores property characteristics, pricing trends, regional variations, and key market insights through interactive Jupyter notebooks, forecasting models, and comprehensive visualizations.

## ✨ Features

- **Comprehensive Data Exploration**: Detailed exploratory data analysis with statistical summaries
- **State & District Analysis**: Compare properties across different Malaysian states and districts
- **Visualization Suite**: Multiple charts and graphs including:
  - Correlation matrices
  - Distribution plots
  - District comparisons
  - Market trends
- **Regional Focus**: Dedicated analysis of specific regions (e.g., Pahang and Johor states)
- **Forecasting & Trend Projection**: Regression-based price forecasting for state-level market outlooks
- **Data-Driven Insights**: Actionable conclusions about market dynamics

## Dataset

**File**: `Malaysia Residential Property Data.csv`

This dataset contains comprehensive information about residential properties in Malaysia including:
- Property prices and valuations
- Location details (state, district)
- Property characteristics (size, type, tenure)
- Market data across multiple regions and transaction periods

**Data Source**: [Source information]
**Records**: 410,959
**Features**: 14

## Project Structure

```
Malaysia-Residential-Property-Analysis/
├── README.md                              # Project documentation
├── LICENSE                                # Apache License 2.0
├── Malaysia Residential Property Data.csv # Main dataset
├── EDA.ipynb                              # Comprehensive EDA & analysis
├── EDA (Pahang).ipynb                     # Focused analysis on Pahang state
├── EDA (Johor).ipynb                      # Focused analysis on Johor state
├── Forecast (Pahang).ipynb                # Pahang forecasting and projection
└── Forecast (Johor).ipynb                 # Johor forecasting and projection
```

## Installation

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required libraries: pandas, numpy, matplotlib, seaborn, scipy

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Malaysia-Residential-Property-Analysis.git
   cd Malaysia-Residential-Property-Analysis
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

## Usage

### View the Analysis

1. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open the analysis notebooks**
   - `EDA.ipynb` - Comprehensive analysis of the entire dataset
   - `EDA (Pahang).ipynb` - Focused analysis of Pahang state properties
   - `EDA (Johor).ipynb` - Focused analysis of Johor state properties
   - `Forecast (Pahang).ipynb` - Forecasting and market projection for Pahang
   - `Forecast (Johor).ipynb` - Forecasting and market projection for Johor

3. **Run cells sequentially** to explore the analysis step by step

### Customize the Analysis

- Modify data filters to focus on specific regions or price ranges
- Adjust visualization parameters in the notebooks
- Generate new insights by creating additional analysis cells

## Key Insights

The analysis reveals:
- Regional variation in property prices and characteristics
- Market trends across different districts
- Correlation patterns between property features and pricing
- State-specific market dynamics
- Statistical summaries of key metrics

## Analysis Highlights

### Notebook Features

**EDA.ipynb**
- Data loading and cleaning
- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Multi-state comparisons
- District-level insights
- Advanced visualizations

**EDA (Pahang).ipynb**
- Pahang state-specific analysis
- District-by-district breakdown
- Regional market trends
- State-focused insights

**EDA (Johor).ipynb**
- Johor state-specific analysis
- District-level comparison across Johor
- Local property pricing patterns
- Regional distribution and correlation analysis

**Forecast (Pahang).ipynb**
- Forecasting model development for Pahang
- Time-series and regression-based price projection
- Future transaction trend visualization

**Forecast (Johor).ipynb**
- Forecasting model development for Johor
- State-specific predictive insights
- Trend analysis and projection charts

## 🔍 Technologies Used

- **Python** - Data analysis programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive analysis environment

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

### Contribution Ideas

- Additional regional analyses
- Enhanced visualizations
- Predictive models
- Data quality improvements
- Documentation enhancements

## 📊 Related Projects

- Malaysian Real Estate Analytics
- Property Market Prediction Models
- Regional Housing Trends

## 📧 Contact & Support

For questions, suggestions, or feedback:
- Open an issue on GitHub
- Contact the repository maintainer

---

**Last Updated**: 2026 | **Status**: Active Development
