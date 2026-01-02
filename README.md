# Negative Event Density Index (NEDI)
**Developed by Jamie A. Gostt**

The **Negative Event Density Index (NEDI)** is an open-source data visualization tool designed to quantify the concentration of historical crises over time. By leveraging the MediaWiki API, NEDI identifies and clusters reporting spikes related to conflict, economic instability, and humanitarian disasters.

## Methodology
Unlike qualitative sentiment analysis, NEDI focuses on **event density**. 
- **Data Sourcing:** Real-time scraping of Wikipedia's year-by-year archives.
- **Signal Tracking:** Algorithmic filtering for crisis-related keywords (e.g., *war, death, crash, recession*).
- **Visualization:** A moving average trendline is applied to identify volatility "waves" rather than isolated incidents.

## Features
- **Interactive Timeline:** Click any year to view the specific events contributing to its density score.
- **Export Capabilities:** - **CSV:** Summary data (Year, Count, Trend) for Excel/Tableau.
  - **JSON:** Full master archive of every event and its category context.
- **Performance Optimized:** Includes a "breather" delay for long-range historical requests (150+ years) to maintain browser stability.

## Citation & License
If you use NEDI for academic research or publications, please cite as:
> Jamie A. Gostt, (2026). *Negative Event Density Index (NEDI)*. [Link to your GitHub Repo]

- **Software:** Licensed under the [MIT License](https://opensource.org/licenses/MIT).
- **Research & Logic:** Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## 🛠 Usage
1. Open `index.html` in any modern browser.
2. Select your desired year range.
3. Toggle "Trend" or "Phases" (historical context markers) as needed.
4. Click **Run Analysis**.
