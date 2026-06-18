# Data Notes

This project used NHL goalie performance data from the 2010-2014 seasons.

The dashboard focused on traditional goalie performance and workload metrics, including:
- Save percentage
- Goals-against average
- Wins
- Regulation/OT win percentage
- Workload
- Shot volume

Data preparation steps included:
- Combining five seasons of NHL goalie data vertically in SQL
- Cleaning and transforming the data in Power Query
- Removing low-usage goalies
- Removing rows with missing statistics
- Creating DAX measures in Power BI for KPI and visual reporting

The source data file is included in the `data/` folder.
