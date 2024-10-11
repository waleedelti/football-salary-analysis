# Key Metrics Influencing Player Wages: An Empirical Analysis of European Football’s Top Five Leagues
Project Overview

This project explores the key performance metrics that influence the wages of professional football players in Europe’s top five leagues (Premier League, La Liga, Serie A, Bundesliga, Ligue 1) during the 2023/24 season. The study aims to provide clubs, agents, and players with data-driven insights into wage determination by focusing on on-field performance. The machine learning models used include Random Forest, Gradient Boosting (GBM), Bayesian Additive Regression Trees (BART), and Quantile Regression.

Objective of the Study

The primary aim is to identify the most important performance metrics for wage determination across different positions (goalkeepers, defenders, midfielders, forwards). Many past studies have explored popularity and off-field factors, but this dissertation focuses specifically on performance metrics that directly impact a team’s success.

Assumptions and Limitations

This study assumes that on-field performance metrics are the primary drivers of wages, with additional factors like age, league, and nationality providing context. However, it excludes factors such as player popularity and financial health of the club. A key limitation is that the study considers all five leagues together, without distinguishing between them in terms of playing styles or team priorities. Thus, differences between leagues—like fast-paced vs. possession-based play—are not explicitly analyzed, which may reduce the precision of the conclusions.

Methodology

Advanced machine learning models, including Random Forest, GBM, and BART, are employed to develop predictive models for wage determination. Stepwise regression is used to systematically identify the most relevant predictors for each player position. Quantile Regression plays a vital role in examining wage determination across different wage levels, offering more detailed insights into how metrics affect players in different salary brackets.

Data Sources

    •    Player Performance Data: FBRef (advanced football statistics)
    •    Wage Data: Capology
    •    Injury Data: Transfermarkt

Data was collected, pre-processed, and analyzed to ensure consistency. Initial data exploration provided a strong foundation for the predictive models.

Results

The models were applied to different player positions, yielding valuable insights into the key performance indicators for each position. The predictive power varied across positions, with midfielders generally showing lower predictive accuracy due to their diverse roles. The evolution of the sport over the past 20 years has greatly effected the roles of each position, and therefore, the predictability of wages. 

Dissertation Structure

The dissertation includes:

    •    Literature Review: A comparison of prior studies on football wage determination and their methodologies.
    •    Data and Methodology: Introduction to the data and the machine learning models employed.
    •    Results & Analyses: Detailed findings for each player position.
    •    Conclusion: Summary of key results, implications for wage negotiations, and suggestions for future research.
