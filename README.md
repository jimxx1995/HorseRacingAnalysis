# HorseRacingAnalysis
The project analyzed the 2014-2016 Hong Kong racing season data from Hong Kong Jockey Club using Python and extracted features from the data. The purpose of this project is to examine the possibility of yielding positive return on Hong Kong horse racing by statistical and machine learning approaches.

## Required Installations
The only installation needed to run this repo is Python. Click here to learn about how to install [Python](https://www.python.org/getit/). Once installed, you should be good to go!

## Data Source
I used the horse racing dataset that provided by [Kaggle Dataset-Can You Predict The Result?](https://www.kaggle.com/lantanacamara/hong-kong-horse-racing). The dataset contains the race result of 1561 local races throughout Hong Kong racing seasons 2014-16. Please download both race-result-horse.csv and race-result-race.csv files.

## Data Wrangling 
Please see the [Data Wrangling notebook](Data_Wrangling.ipynb) for more details.
## Analysis
Please see the [Analysis report](report/Analysis_of_Horse_Racing.pdf) for more details.

## Model
The details of the model and winner prediction cannot be shared publicly, but I am happy to share or provide a printout for any interested individuals.

- Logistic Regression Model for winning probability prediction 
- Lasso and Random Forest for features selection

## Predictor Variables
- Finishing_position
- Actual Weight 
- Declared Horse Weight
- Draw
- Finish Time 
- Win Odds 
- Race Class 
- RaceDistance
- Performance of Jockey
- Performance of Trainer
- Daysince

## File Structure
```
project/
     README.md
     Analysis_of_Horse_Racing.ipynb
     Data_Wrangling.ipynb
     LICENSE
     report/
          Analysis_of_Horse_Racing.pdf    
     data/
          db.bak
          db.dat
          db.dir
          horsedb.csv
          raceresult.csv
     images/
          Draw-vs-Finishing-Position.jpg
          Draw-vs-Win.jpg
          Draw-vs-Winner.jpg
          Jockey-vs-Finishing-Position.jpg
          Jockey-vs-Win.jpg
          Jockey-vs-Winner.jpg
          Pairwise-Relationships.jpg
          Speed-vs-Finishing-Position.jpg
          Speed-vs-Win.jpg
          Win-Odds-vs-Finishing-Position.jpg
          Win-Odds-vs-Win.jpg
          heatmap.jpg
```

# LICENSE
In an effort to enable reproducible, collaborative research this project is subject to the GNU Lesser General Public License v3.0.
