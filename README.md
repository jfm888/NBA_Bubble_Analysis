John Mahoney\
Data 512\
Project Proposal

# Analysis of 2019-20 NBA Season

### Motivation
People chose to become a fan of a particular sports team for a varity of reasons, many of them are enduring such as: family tradition, home town, or treasured childhood memory. The connection between a fan and their team is enduring and the team’s performance and the fan’s self-esteem are strongly linked([Abrams & Hogg](https://psycnet.apa.org/record/1989-22355-001)[1], [Wann et al](https://www.emerald.com/insight/content/doi/10.1108/JCM-02-2014-0856/full/html)[2]). This impiles sports may be a source of strenght for some fans during difficult times such as the Covid-19 pandemic. However altering the sports schedule or format can lead to questions of legitimacy and then sports may become a source of uncertianty in a fans life.

The 2019-20 NBA season was the longest in history at 377 days. Due to the Covid-19 pandemic, on March 11 the 2019-20 NBA regular season was suspended(later ruled concluded) with most teams having completed only about 80% of their scheduled regular season games (82 games is standard). Almost five months later the leading 22 teams met to play a further 8 games to determine which 16 teams would continue to the playoffs and what the playoff seeding would be. These eight games as well as the playoffs and the championship games were played in the NBA Bubble( also called the Disney Bubble), an isolated part of Walt Disney World in Orlando Florida. This season is incredibly interesting in many ways as it begins to answer real questions about factors involved in competitive sports. These questions including:

* Was the shortened season long enough to determine the proper playoff teams?
* Was play during the playoffs different than in previous years?

There has never been an NBA season like the 2019-20 season, and by studying it we can begin to answer some of the most difficult questions in sports. The goal of this project is to use the 2019-20 NBA season to try to better understand what influences basketball team performance.

### Data
Data was from [Basketball-Reference](https://www.basketball-reference.com/leagues/NBA_2020_games.html) with an MIT License.

[Basketball-Reference](https://www.basketball-reference.com/leagues/NBA_2020_games.html) is an excellent source for data, and the data is freely available for download and use as long as Basketball-Reference is mentioned as the source. I have collected the following datasets from [Basketball-Reference](https://www.basketball-reference.com/leagues/NBA_2020_games.html) and provided them in the Github Repo with an MIT License:

* 2009-20 NBA Regular Season Schedule
* 2009-20 NBA Playoff Schedule

The above datasets are Excel files of tables downloaded from Basketball-Reference. The Schedule datasets contain a schedule of games and final scores for the last 11 seasons. Each tuple contains: Date, Start Time - Eastern, Visiting Team, Points Scored, Home Team, Points Scored. These datasets will be used to draw comparisons between regular season performance and playoff performance. Lastly, there are no ethical considerations to using this data, as no part of the data contains sensitive information, or anything that is not a matter of public record. All of this data is freely available and based solely on the public performance of professional basketball teams. 

### Research Questions and Hypotheses
Question 1.a : Is stopping play at March 11th of a season enough to determine the best teams to send to the playoffs?\
Null Hypothesis 1.a : The remaining games after March 11th of regular season play have had no impact on playoff team selection over the last previous ten years if using the NBA Bubble selection method.\
Question 1.b : Is stopping play at 75% of a season enough to determine the best teams to send to the playoffs?\
Null Hypothesis 1.b : The last 25% of regular season play have had no impact on playoff team selection over the previous ten years if using the NBA Bubble selection method.\
Question 1.a/1.b Rationale: The NBA regular season is 82 games long, the 2019-20 season was stopped at March 11th(about 75% of regular season games) for the Covid-19 pandemic. I trust the NBA and believe that the reduced season is enough to determine the best playoff teams, providing the NBA bubble selection method is used(top eight teams in both conferences as well as the next six best teams overall, 22 teams total) as this picks an extra six teams.\
Question 2: Was play in the NBA Bubble significantly  different than in previous playoffs?\
Null Hypothesis 2: The difference between team scoring during the regular season and during playoffs in the NBA Bubble is not significantly different than the mean regular season / playoff scoring differential over the last ten years\
Question 2 Rationale: There was a five month break between regular season and playoff season play. This should be enough time for players to recover from injuries sustained during the regular season. Additionally this is enough time for teams to make adjustments on offense and defense in order to be more competitive. During the playoffs the teams lived in a quaranteened environment making it difficult for them to interact with friends, family and fans. My belief is that these many factors will affect teams equally and playoff play will not be significantly different compared to previous years.


