# Jupyter Notebooks Collection

This repository contains a collection of data science and analytics projects covering sports betting, weather prediction, financial analysis, and machine learning.

## Table of Contents
- [Sports Analytics & Betting](#sports-analytics--betting)
- [Weather & Prediction Markets](#weather--prediction-markets)
- [Financial & Economics](#financial--economics)
- [Business & Data Analysis](#business--data-analysis)
- [Recommendation Systems](#recommendation-systems--machine-learning)
- [Learning & Educational](#learning--educational)
- [Other Projects](#other-projects)

---

## Sports Analytics & Betting

### College Sports
- **CollegeBasketballSpreadResults.ipynb** - College basketball spread analysis comparing FanDuel vs Pinnacle
- **NCAABMachineLearning.ipynb** - NCAA basketball machine learning betting model with:
  - Gradient boosting classifier
  - Cross-validation and threshold optimization
  - ROI analysis
  - Feature engineering from multiple line sources
- **OddsTrackerNCAAF.ipynb** - NCAA football odds tracking

### Professional Sports
- **NBAMachineLearning.ipynb** - NBA betting model featuring:
  - Gradient boosting with sklearn pipelines
  - ROI and accuracy analysis
  - Monthly performance breakdowns
  - Line range analysis
- **NBAPlayoffs.ipynb** - NBA playoffs analysis
- **MLBAnalysis.ipynb** & **MLBAnalysis2.ipynb** - MLB game analysis
- **NFL.ipynb** - NFL analysis
- **OddsTrackerNFL.ipynb** - NFL odds tracking with database integration

### Betting Analysis
- **FanDuelVsPinnacle.ipynb** - Comparative analysis of FanDuel and Pinnacle betting lines:
  - Week-before game line analysis
  - Error comparison
  - Average accuracy metrics
- **OpeningSpreads.ipynb** - Opening spreads analysis
- **SportsBetting.ipynb** - General sports betting analysis
- **Huge January.ipynb** - Analysis of betting performance during January

---

## Weather & Prediction Markets

- **Weather.ipynb** - Weather prediction analysis
- **WeatherJul8.ipynb**, **WeatherJul21.ipynb**, **WeatherBlend.ipynb** - Various weather analyses from July
- **WatherJul10.ipynb**, **Wather.ipynb** - Additional weather studies
- **Kalshi.ipynb** - Kalshi API integration for weather prediction markets:
  - Los Angeles & Denver temperature betting
  - API endpoint testing
  - Market data retrieval

---

## Financial & Economics

- **Bitcoin.ipynb** - Bitcoin and cryptocurrency analysis
- **TCV2.ipynb** - Total Contract Value analysis
- **TCVAnalysis.ipynb** - TCV correlation studies
- **TCVAnalysis3AllNonTakeoversAfter2018.ipynb** - Non-takeover contracts analysis (post-2018)

---

## Business & Data Analysis

- **CityLifestyleCorrelations.ipynb** - Territory and lifestyle analysis featuring:
  - Revenue correlation with population, HHI, home values, and business counts
  - Magazine revenue comparison
  - Statistical correlation analysis
  - Data visualization

---

## Recommendation Systems & Machine Learning

- **Music_Recommendation_System_Full_Code.ipynb** - Music recommendation system
- **music_recommendation_system_final_submission.ipynb** - Final submission version
- **Recommendation_Systems_Learner_Notebook_Full_Code.ipynb** - Educational recommendation systems project
- **FDS_Project_LearnerNotebook_FullCode.ipynb** - Comprehensive data science project

---

## Learning & Educational

- **Python_For_DataScience_intro.ipynb** - Introduction to Python for data science
- **Notebook - Introduction to Python.ipynb** - Python basics
- **Notebook - Introduction to Python (2).ipynb** - Additional Python fundamentals
- **Notebooks intro.ipynb** - Getting started with Jupyter notebooks
- **FirstNotebook.ipynb** - First Jupyter notebook

---

## Other Projects

- **density_relevance.ipynb** - Density and relevance analysis
- **unsubscriber_analysis.ipynb** - Unsubscriber behavior analysis
- **MediumAricle.ipynb** - Medium article content
- **demo.ipynb** - Demo notebook
- **nbagg_uat.ipynb** - NBA game testing
- **reconstruction_usage.ipynb** - Reconstruction usage examples
- **taming-transformers.ipynb** - Transformer model experiments
- **Untitled.ipynb**, **Untitled1.ipynb** - Scratch/experimental notebooks

---

## Key Features

### Machine Learning Models
- Gradient boosting classifiers for sports betting
- Feature engineering from multiple data sources
- Cross-validation with time series splits
- Threshold optimization for maximum ROI
- Recommendation systems for music

### Data Sources
- Multiple sportsbook APIs (FanDuel, Pinnacle)
- ESPN FPI ratings
- Kalshi prediction markets
- National Weather Service data
- MySQL databases via SSH tunnels

### Analysis Techniques
- Statistical correlation analysis
- ROI and profitability calculations
- Performance tracking by time periods
- Line movement and market efficiency studies
- Predictive modeling and backtesting

---

## Technologies Used

- **Python Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Machine Learning**: Gradient Boosting, pipelines, cross-validation
- **Data Access**: MySQL, SSH tunnels, REST APIs
- **Visualization**: matplotlib, seaborn

---

## Getting Started

Most notebooks can be run independently. Key dependencies include:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn requests pymysql sshtunnel
```

For sports betting models, you'll need access to historical game data in CSV format.

For weather prediction markets, you'll need Kalshi API credentials.

For database-connected notebooks, ensure you have proper SSH access credentials.

---

## Notes

- Many sports betting notebooks include production-ready ML pipelines
- Cross-validation results show real-world performance expectations
- Weather analysis integrates with prediction markets for arbitrage opportunities
- Financial analysis notebooks focus on contract valuations and correlations

---

## License

Personal project collection for educational and research purposes.
