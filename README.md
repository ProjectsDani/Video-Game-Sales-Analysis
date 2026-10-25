Video Game Sales Analysis
An exploratory analysis of video game sales using Python, pandas, Matplotlib, and Seaborn. This project compares sales across platforms, genres, publishers, and regions, and explores how review scores relate to sales.
Project overview
The goal is to turn a historical video game dataset into clear comparisons and visual findings. The notebook includes data preparation, missing-value checks, grouped analysis, and 10 visualizations with written interpretations.

This is an independent learning project, not commercial client work.
Dataset
The input file is Video_Games_Sales_as_at_22_Dec_2016.csv, containing 16,719 records and 16 columns before cleaning.

Fields include:
- Game name, platform, release year, genre, and publisher.
- Sales in North America, Europe, Japan, and other regions.
- Global sales, critic scores, user scores, developer, and age rating.
Sales figures represent units sold in millions, rather than revenue or profit. Records can represent a game on a particular platform, so record counts should not be treated as counts of unique game titles.

The analysis uses a historical dataset dated December 2016; it does not describe the current video game market.
Tools
- Python and Jupyter Notebook
- pandas for data preparation and aggregation
- Matplotlib and Seaborn for visualization
Data preparation
- Remove duplicate rows.
- Convert user scores to numeric values, treating nonnumeric entries as missing.
- Exclude records without a release year and convert release years to integers.
- Review missing-value percentages.
- Fill missing developer, publisher, and rating values with Unknown.
- Retain records without review scores for sales comparisons.
- Filter missing review scores separately for charts that require those scores.
Analysis
The notebook explores:
1. Highest-selling game records.
2. Recorded global sales grouped by game release year.
3. Platforms with the highest recorded game sales.
4. Global sales volumes by genre.
5. Regional sales differences across genres.
6. Relationships between critic and user scores.
7. Relationships between critic scores and global sales.
8. Sales distributions across age-rating categories.
9. Publishers with the highest recorded global sales.
10. Numbers of game records by release year.
Charts include ranked bar charts, a line chart, grouped regional comparisons, scatterplots with fitted trend lines, and a boxplot.
Selected findings
In the analyzed dataset:
- Wii Sports leads the individual game-record sales ranking.
- PS2 leads recorded game sales by platform.
- Action has the highest total sales volume by genre.
- Nintendo leads recorded global sales by publisher, followed by Electronic Arts and Activision.
