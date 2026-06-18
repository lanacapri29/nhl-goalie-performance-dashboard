# Dashboard Design Notes

## Theme
- Theme Name: Innovate
- Canvas Background Color: #143C5F
- Global Font: Calibri
- Primary Title Background: #2878BD

## Purpose
The dashboard analyzes NHL goalie performance from 2010-2015, with a focus on evaluating Jonathan Quick’s performance relative to league averages and Vezina Trophy-winning goalies.

## Key Metrics
- Save percentage
- Goals-against average
- Regulation/OT win percentage
- Games played
- Shots against per 60
- Workload indicators

## Dashboard Pages
- Information Page
- Quick vs. League: Season Overview
- League Rankings & Vezina Case
- Workload vs. Performance: Consistency
- Standards Page

## Data Preparation
- Combined five seasons of NHL goalie data vertically in SQL
- Cleaned the data in Power Query
- Removed low-usage goalies and rows with missing statistics
- Created DAX measures in Power BI to summarize performance

## Design Standards
- Consistent blue color palette across pages
- KPI cards with large callout values
- Slicers for player, season, and metric selection
- Consistent navigation buttons across dashboard pages
- Visual backgrounds set to black with transparency
- Uniform title styling using theme color #2878BD
- Header icons disabled except Focus Mode

## Key Player Accent Colors
- Jonathan Quick: #E063F6
- Carey Price: #C5E538
- Tuukka Rask: #FF9100
- Sergei Bobrovsky: #00F5F5
- Henrik Lundqvist: #FF0000
- Tim Thomas: #D8BB05
