# FIFA 21 STATISTICAL

If you are a huge fan of FIFA - Soccer Video Game, you might want to know every player featuring in the game, some basic information about each player, etc.

In this Data Analysis, I will be analyzing basic statistics and playing attributes of all the players in FIFA 21. Then, I will be identifying a trend in the data and combine the data analysis with domain research to identify likely factors influencing how good a player is or which position a player is good at.

Therefore, we can make our dream team, and have several insights and correlations between player value, wage, age, and performance can be derived from the dataset.

## Data Description

The data was scraped from https://sofifa.com/ using BeautifulSoup package. This data set is provided by EA Sports game FIFA and developed to give gamers an extensive and coherent scout of players worldwide.

For each skill, we have an integer from 0 to 100 that measures how good a player is at that skill. For examples of skills are: Dribbling, Aggression, Finishing, Vision, and Ball Control. By observation, it seems to be unfeasible to accurately characterize players in these attributes automatically. Thus, all of those are gathered and curated by the company whose job is to bring the gameplay closer to reality as possible, hence preserving coherence and representativeness across the dataset.

The FIFA 21 dataset that has been used for this analysis provides statistics of about 360 players on different skills. These skills are optimal indicators to determine the performance of a player at a particular playing position.

## Exploratory Data Analysis Achieved Using This Dataset

- Top countries with number of players

- Top countries with good players

- Best players in different skills

- Best player per position

- Correlation Heatmap - find out interesting correlations between different skills

- Histogram - number of players in different age groups

- How to train a player in order to be good at a particular position

- Comparison of top five skills for each position

- How a player performs his role throughout the entire game

- Relationship between Overall & Potential vs Age

## Create Plotly Polar Charts

In this section, we will compare the characteristics of the players by using polar diagrams in Plotly in order to see which skills one player is better than another in the same skill sets.

Moreover, polar diagram also explains why a player performs well at his position. Thus, we are able to use the diagrams to pick our best player at a particular position.

## Genetic Algorithm

It is hard for a gamer to select his best team when playing FIFA. We will use Genetic Algorithm to select our best team by using some features such as total amount of value and average age of players.
