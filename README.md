🏀 NBA Team Performance Analysis

## 🧠 Executive Summary

This project delivers a comprehensive, data-driven evaluation of historical NBA franchise performance using SQL, Python, and professional data visualization techniques. The goal of this analysis is to identify long-term patterns in team success, highlight exceptional seasons, and pinpoint the most dominant multi-year windows across NBA history.

The workflow begins with rigorous data cleaning and transformation in SQL, followed by exploratory and comparative analysis in Python using pandas and Matplotlib. The results include a series of polished visualizations that examine best and worst regular seasons, year-over-year improvements, five-year dominance spans, and franchise-wide win/loss distribution.

A focused case study on the Los Angeles Lakers is also included, isolating their strongest five-year stretch and breaking down each season’s wins, losses, and performance trends.  

This end-to-end project demonstrates practical analytics skills, including data cleaning, SQL querying, feature engineering, statistical comparison, and visualization design—culminating in a portfolio-ready analysis suitable for technical interviews, case studies, or data analyst roles.


🔹 1. Project Overview

The NBA has evolved dramatically through different eras defined by superstar players, rule changes, and team strategy.

This project analyzes historical franchise performance using:

-SQL for data preparation and multi-season aggregations

-Python (pandas + matplotlib) for high-quality visualizations

Goal: Understand long-term team performance through regular-season results, multi-year dominance windows, and league-wide win/loss patterns.

🔹 2. Business Questions

Which teams recorded the best and worst regular seasons in NBA history?

Which teams showed the largest year-to-year improvement in wins?

Which franchises had the strongest five-year spans?

How do teams compare based on all-time wins, losses, and win%?

What was the single best five-year run in Lakers history, and how did each season perform?

🔹 3. Methodology

Dataset Sources: Historical NBA franchise records (cleaned and standardized)
Tools Used:

SQL – filtering, windowing, 5-year span construction, performance aggregation

Python (pandas, matplotlib) – data visualization and formatting

Steps Taken:

Cleaned and structured team-level and season-level datasets.

Built SQL queries to compute wins, losses, win percentages, year-over-year deltas, and rolling 5-year metrics.

Developed multiple polished visualizations to summarize both short-term and long-term team performance.

🔹 4. Results & Visualizations

🏆 Best Regular Season Records (Top 5)

Insight:
Teams with historically high win percentages often represent dynasty-level rosters or highly efficient coaching systems.

<img src="images/best_regular_season_records.png" width="650">

📉 Worst Regular Season Records (Top 5)

Insight:
These seasons often align with rebuilding phases, roster injuries, or transitions between star eras.

<img src="images/worst_records_in_nba_history.png" width="650">

🔺 Largest Win Increase (Two Seasons Compared)

Insight:
Massive win jumps commonly coincide with acquiring superstar players, hiring elite coaching staffs, or recovering from injury-heavy years.

<img src="images/largest_win_increase_from_previous_season.png" width="650">

📊 Top 5 Records Over a Five-Year Span

Insight:
Five-year dominance often reflects sustained coaching stability and strong roster cores.
Comparing wins vs. losses over these windows highlights overall organizational efficiency.

<img src="images/top_records_over_5_year_span.png" width="650">

📊 Leaguewide Wins & Losses (Sorted by All-Time Win %)

Insight:
Sorting by win% highlights long-term consistency rather than total games played.
Historic powerhouses like the Lakers, Celtics, and Spurs rank near the top, while younger franchises or long-rebuilding teams fall lower.

<img src="images/total_wins_and_losses.png" width="650">

🟣🟨 Lakers’ Best 5-Year Run — Season-by-Season Breakdown

Insight:
This isolates the single most dominant stretch in Lakers history and provides a deeper look into how each season contributed to the peak.

<img src="images/best_5_year_record_lakers.png" width="650">
🔹 5. Key Takeaways

-Consistent Dynasties: Certain franchises demonstrate sustained excellence over multiple eras.

-Volatile Turnarounds: Major roster or coaching changes can generate enormous single-year win improvements.

-Era Defining Teams: Five-year windows highlight the most dominant stretches across NBA history.

-Long-Term Performance: Win percentage provides a more accurate long-term ranking than raw win totals.

-Lakers Insight: Their strongest five-year run demonstrates elite team construction and consistent seasonal performance.

🔹 6. Next Steps

-Incorporate playoff performance for deeper historical comparisons.

-Integrate advanced analytics, such as SRS, net rating, or BPM, for richer insights.

-Build an interactive dashboard (Tableau, Power BI, or Streamlit).

-Expand analysis to include player-level metrics and roster influence.

-Compare franchise eras (e.g., Showtime Lakers vs. Shaq-Kobe vs. Modern Lakers).