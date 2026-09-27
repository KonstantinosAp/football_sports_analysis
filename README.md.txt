EUROPEAN FOOTBALL DATA ANALYSIS(2000/01-2024/25):

An end-to-end data analysis project exploring over two decades of European Football match data
using Python, SQL, Tableau and EDA.

\Executive Summary & Key Findings:

-Overall Match Performance & Home Advantage:
.Dataset Scope: Analyzed 95384 matches across 18 European competitions spanning 24 seasons (2000/01 to 2024/25).
.The "12th" Man Quantified: Home teams secured 43140 wins(~45.2%) compared to 28969 away wins(~30.4%) and 23275 draws(~24.4%).
 Across all competitions, home advantage consistenly yields a +14.8% win probability premium.
.Overall Goal Output: European Football averaged 2.71 goals per match, showcasing a stable high-tempo offensive baseline across two decades.

--Team Performance & Dominance :
.Offensive Powerhouses: Bayern Munich leads all teams with 2279 goals scored, followed by Manchester City (1953 goals) and Arsenal (1867 goals).
.All-Time Win Leaders: Bayern Munich registered the most total wins with 654 victories, closely trailed by Juventus (636) and Manchester United (598).
.Defensive Rigor: PSG (0.84), Juventus(0.86) and Bayern Munich(0.90) maintained the lowest average goals conceded per match,
 demonstrating that elite efficiency on defence strongly correlates with long-term league dominance.

#Competition Dynamics:
.High-Scoring Cup Competitions: Knockout tournaments display higher goal variability.
 DFB-Pokal averaged 3.61 goals/match, followed by the FA Cup (3.21) and Coupe de France (3.13).
.Domestic League Comparison: The German Bundesliga averaged 2.94 goals per match, solidifying its reputation as the highest-scoring domestic top-flight
 league in Europe, followed by Super-Lig (2.90).

##Country & Regional Analysis:
.Data Volume Leader: England holds the largest representation in the dataset with 26107 matches and 72797 goals, driven by deep league structures (Premier League,
 EFL Championship, FA Cup).
.Goal Productivity by Nation: Germany recorded the highest country-wide goal average (2.93 goals/match), outperforming England (2.79) and Turkey (2.81).
.Tactical Defensiveness: France (2.56), Italy (2.59) and Spain (2.59) produced lower average goal rates, reflecting a stronger emphasis on tactical organization
 and defensive setups.

=Strategic Insights & Practical Takeaways:
1. Home-Field Advantage as a Critical Variable:
  -Across all leagues, playing at home provides a predictable ~15% boost in win probability. Tactical setups for away fixtures should focus heavily on defensive
   resilience aerly in matches to neutralize home momentum.
2. The "Bundesliga Factor": High-Risk, High-Reward Style:
  -German football (both Bundesliga and DFB-Pokal) consistenly leads in goal productivity. The higher goals-per-match metric suggests a tactical preference for 
   aggressive pressing and open transitions compared to Serie A or Ligue 1.
3. Balanced Champions:
  -Teams that dominate across decades (e.g. Bayern Munich, Juventus) excel in both metrics simultaneously ranking top 3 in goals scored and maintaining a sub- 1.00
   goals-conceded-per-match ratio.

## Tech Stack & Methodology:

-Data Processing & ETL:
 Python (Pandas, NumPy)
-Database & Querying:
 SQL (Aggregations, Window Functions, Partitioning, CTEs)
-Visualization:
 Tableau Desktop (Interactive Dashboards, Trend Lines, Distribution Analyses)