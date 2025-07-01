# ⚽ 23-24-Champions-League-Playing-XI
![.](media/uefa-champions-league.gif)

## 📌 Project Overview
* Built the Best Playing XI of the 2023/24 UEFA Champions League using data-driven analysis of player performance metrics.
* Scraped player stats from ![fbref.com](https://fbref.com/en/comps/8/2023-2024/stats/2023-2024-Champions-League-Stats) using ![google chrome extension](https://chromewebstore.google.com/detail/nocoding-data-scraper-eas/ojaffphbffmdaicdkahnmihipclmepok?hl=en-US&utm_source=ext_sidebar).
* Cleaned and organized the dataset for analysis using python.
* Visualized performance metrics and made an interactive dashboard on Tableau.
* Compared players across positions using stats like goals, assists, xG, key passes, tackles, interceptions, saves etc
* Selected a data-driven Best XI for the season.

## 🛠️ Tools & Technologies
* Python (Pandas)
* Visualization tool : Tableau

## 📊 Dataset Description
* datatable : Contains all the shooting stats (Goals, Xg, Non-penalty Xg etc).
* fbref_creation : Contains all the creativity and creation metrics (Shot creating Actions, Goal Creating Actions).
* fbref_def : Contains all the defensive stats (Tackles, Interceptions etc).
* fbref_passing : Contains all the passing metrics (Assists, Pass completion etc).
* fbref_possession : Contains all the possession stats (touches, takeons, carries).
* fbref_misc : Contains some miscellaneous stats (red card, yellow card, aerial duels etc).
* fbref_goalk : Contains standard goalkeeper stats (saves, goals conceeded).
* fbref_goalka : Contains advanced goalkeeping stats (crosses saved, passes, expected saves).

## 🧹 Data Cleaning and Preprocessing
* Removed all the unneccesary columns.
* Changed the datatypes from object to integer and float.
* Enquired any null values.
* Processed all the null values appropriately.
* Extracted files as a csv file.

## Tableau Dashboard
Made an interactive Dashboard highlighting all the best players for each position.
![.](media/wingtab.png)

## Conclusion
My Best Playing XI 
![.](media/lineup-builder.png)

Official UEFA Playing XI
![.](media/uefa.jpg)
