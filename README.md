# MCDM



Multi-Criteria Decision Making and Analysis for Intelligent Systems







# NBA Player Ranking Decision Support System (DSS)







This project aims to develop a Decision Support System (DSS) for ranking 150 NBA players from the 2022-23 season based on multiple criteria. The system utilizes two weighting methods (AHP and Entropy) and four Multi-Criteria Decision Making (MCDM) methods (TOPSIS, WASPASS, WSM, WPM) to provide a comprehensive evaluation of player performance.







## Key Features







*   **Data Source:** NBA player statistics from the 2022-23 season.



*   **Criteria:** Up to 7 key performance indicators are used, including points (pts), rebounds (reb), assists (ast), free throws made (ftm), 3-pointers made (fg3m), net rating, and usage percentage (usg_pct).



*   **Weighting Methods:**



    *   Analytic Hierarchy Process (AHP): Subjective weighting based on pairwise comparisons of criteria.



    *   Entropy: Objective weighting based on the information content of each criterion.



*   **Ranking Methods:**



    *   TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)



    *   WASPASS (Weighted Aggregated Sum Product Assessment)



    *   WSM (Weighted Sum Model)



    *   WPM (Weighted Product Model)







## Methodology







1.  **Data Preprocessing:** Data cleaning, filtering for the most recent season, and player selection.



2.  **Normalization:** Min-max scaling to ensure comparability of criteria.



3.  **Weight Calculation:** AHP and Entropy weights are calculated and then averaged to obtain final weights.



4.  **MCDM Ranking:** Each of the four MCDM methods is applied to the weighted data to generate player rankings.



5.  **Comparison and Analysis:** Rankings are compared to identify the top players and analyze differences between methods.







## Results







The project identifies the top 10 NBA players based on each MCDM method and provides a comparative analysis of their rankings. 







A visualization of the TOPSIS ranking is also included.







![Top 10 NBA Players Ranking (TOPSIS)](/nba_player_rankings_topsis.png)







## Usage







1.  Ensure the necessary libraries are installed: `pandas`, `numpy`, and `altair`.



2.  Run the Python scripts in the following order:



    *   `data_preprocessing.py`



    *   `calculate_weights.py`



    *   `topsis_ranking.py`



    *   `waspass_ranking.py`



    *   `wsm_ranking.py`



    *   `wpm_ranking.py`



    *   `compare_rankings.py`







## Future Work







*   Incorporate additional criteria and ranking methods for a more comprehensive evaluation.



*   Explore the use of other weighting methods.



*   Conduct sensitivity analysis to assess the impact of different weights on the rankings.







## Contributing







Contributions are welcome! Feel free to open an issue or submit a pull request.







## License







[None]
