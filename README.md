# Unguided Project 001
# Investigating Netflix Movies and Guest Stars in The Office
# Datacamp projects x Joseph Abang

## Dataset
In this project, I applied the skills learned in Python to investigate a netflix series - The office. In this notebook, I took a look at a dataset of The Office episodes, and tried to understand how the popularity and quality of the series varied over time. 

The dataset used contains information on a variety of characteristics of each episode. It contained 188 entries and 14 columns as shown below.

### Variables
* episode_number: Canonical episode number.
* season: Season in which the episode appeared.
* episode_title: Title of the episode.
* description: Description of the episode.
* ratings: Average IMDB rating.
* votes: Number of votes.
* viewership_mil: Number of US viewers in millions.
* duration: Duration in number of minutes.
* release_date: Airdate.
* guest_stars: Guest stars in the episode (if any).
* director: Director of the episode.
* writers: Writers of the episode.
* has_guests: True/False column for whether the episode contained guest stars.
* scaled_ratings: The ratings scaled from 0 (worst-reviewed) to 1 (best-reviewed).

# Summary of findings 
* Episodes with guest stars generally have higher viewership.
* Guest stars seldom affected ratings of viewers. There is a fairly even distribution of ratings across episodes with guests and without.
* Guests stars appear more in the first 25 episodes and last 50 episodes.
* Episode 77 had the highest viewership (22.91M) and featured 3 guest stars (Cloris Leachman, Jack Black, Jessica Alba).