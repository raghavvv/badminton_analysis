# Indian Badminton Player Rankings Analysis (2001–2025)

This project analyzes the world rankings and performance of Indian badminton players from 2001 to 2025 using data scraped from [badmintonstatistics.net](https://www.badmintonstatistics.net/). The notebook fetches, processes, and visualizes player rankings, win-loss records, and trends for both Men's Singles (MS) and Women's Singles (WS) categories.

## Features

- **Web Scraping:** Collects weekly world ranking data and player details using `requests` and `BeautifulSoup`.
- **Data Processing:** Cleans and structures ranking tables with `pandas`.
- **Top Players:** Identifies the top 10 Indian players by their best-ever world rank.
- **Win-Loss Records:** Fetches and summarizes career win-loss statistics for these top players.
- **Trend Analysis:** 
  - Tracks the number of unique Indian players in the top 100 each year.
  - Visualizes win rates, best ranks, and player timelines.
  - Heatmaps of peak world ranks by year and by month.
- **Visualization:** Uses `matplotlib` and `seaborn` for clear, publication-ready plots.

## Requirements

- Python 3.x
- pandas
- requests
- beautifulsoup4
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install pandas requests beautifulsoup4 matplotlib seaborn
```

## Usage

1. Open and run `badminton.ipynb` in Jupyter Notebook or VS Code.
2. The notebook will:
    - Scrape and process ranking data for Indian players.
    - Identify top performers and fetch their win-loss records.
    - Generate and display various plots and heatmaps.
3. Output CSV: The win-loss data for the top 10 Indian players is saved as `top10_indian_players_win_loss_2001_2025.csv`.

## Notes

- The scraping process may take several minutes due to the number of requests and built-in delays to avoid overloading the server.
- The analysis focuses on singles categories (MS and WS) but can be extended to others.
- All data is sourced from [badmintonstatistics.net](https://www.badmintonstatistics.net/).

## Visualizations

- **Bar plots:** Top 10 Indian players by win rate.
- **Line plots:** Number of Indian players in the top 100 over time.
- **Scatter plots:** Timeline of best world ranks achieved.
- **Heatmaps:** Peak world ranks by year and by month.

---
