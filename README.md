# YouTube Data Science Channels Analysis  

This project dives into **8 popular YouTube channels** in the Data Science & Analytics space, combining **Python + Tableau** to collect, clean, enrich, and visualize their performance data.

- **Data Collection (Python/Jupyter)**:  
  - Uses the YouTube API to pull channel and video metadata  
  - Main analysis in: `youtube_analysis.ipynb`  

- **Data Cleaning & Enrichment**:  
  - Three key datasets:  
    - `channels_clean.csv` – high-level channels info  
    - `videos_clean.csv` – detailed video data for each upload  
    - `features_clean.csv` – calculated KPIs like views/day, engagement rates, and content topics  

- **Visualization (Tableau)**:  
  - Interactive dashboard covering:
    - Channel growth and performance trends  
    - YouTube Shorts vs. Longform content breakdown  
    - Topic popularity heatmap  
    - Key metrics: views per day, engagement rates, upload frequency, and audience reach  

## 🚀 How to Use

1. Clone this repo  
2. Check out all the datasets used in the project
3. Run through the Jupyter notebook to see the full data pipeline  
4. Open the Tableau workbook or view it live on Tableau Public  

## 📌 Data Notes

- I handpicked channels with roughly 1M+ subscribers (or close to it)  
- Analysis covers **videos uploaded in the last 12 months**  
- All data is publicly available through the YouTube API  

## 🛠️ Tech Stack

- **Python** (pandas, requests, YouTube API)  
- **Tableau** (for visualizations)  
- CSV data files  

## ✨ What's Next?

Some ideas I'm considering for future versions:
- Expand to more channels or explore other niches (AI research, software development, etc.)  
- Track performance "velocity" with time-series snapshots (T+1, T+7 views)  
- Analyze how video length, posting schedule, or thumbnail design affects engagement
