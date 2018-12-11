EEC731-Homework 7
Major Leagues - NBA Visualization 

Great stories and great visual effects
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download any of the data sets from previous projects
3. Load the data set into panda data frames
4. Formulate one or two ideas on how storytelling and visualization would help describe the data set and establish additional value
5. Build three or more compelling visualizations
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

The dataset I chose was the NBA predictions dataset.

This dataset contains information from the data behind The Complete History Of The NBA and our NBA Predictions.

nba_elo.csv contains game-by-game Elo ratings and forecasts back to 1946.

About the dataset
How do you rate an NBA team across decades of play? One method is Elo, a simple measure of strength based on game-by-game results. We calculated Elo ratings for every NBA (and ABA) franchise after every game in history — over 60,000 ratings in total.

Elo ratings have a simple formula; the only inputs are the final score of each game, and where and when it was played. Teams always gain Elo points for winning. But they get more credit for upset victories and for winning by larger margins. Elo ratings are zero-sum, however. When the Houston Rockets gained 49 Elo points by winning the final three games of their Western Conference semifinal during the 2014-15 playoffs, that meant the Los Angeles Clippers lost 49 Elo points.

A rating of 1500 is approximately average, although the league average can be slightly higher or lower depending on how recently the league has expanded. (Expansion teams begin with a 1300 rating.) Select a team above, and zoom in to explore its history.

Reference: https://projects.fivethirtyeight.com/complete-history-of-the-nba/#warriors

Code for the project:
The notebook for this project can be found in the notebook folder - notebook/1.0-EECS731-HW7.ipynb Jupyter notebook.

Data:
Dataset is contained in a csv file in the data folder : data/nba_elo.csv

