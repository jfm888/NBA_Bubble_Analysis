John Mahoney\
Data 512\
Autumn 2020

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

Question 2 Rationale: There was a five month break between regular season and playoff season play. This should be enough time for players to recover from injuries sustained during the regular season. Additionally this is enough time for teams to make adjustments on offense and defense in order to be more competitive. During the playoffs the teams lived in a quaranteened environment making it difficult for them to interact with friends, family and fans. My belief is that these many factors will affect teams equally and playoff play will not be significantly different compared to previous years.\

### Background and Related Work

The 2019-20 season has been unique and has rightly been the subject of a lot of analysis and reporting. For a description of the lives of players inside the Bubble [Sam Anderson](https://www.nytimes.com/2020/09/30/magazine/nba-bubble.html) [3] wrote a great article for the New York times. This article is a fascinating account of the stress players feel of being in the Bubble, and is some of the motivation for my second question as well as possible follow up questions. The work by [Simon Spichak](https://towardsdatascience.com/the-basketball-in-the-bubble-cfec7976574b)[4] dispels the idea that travel has an effect on team performance however, Spichak wrote this article before the start of the 2019-20 playoffs. Living and playing in the Bubble is unlike traditional away games in that players are so much more isolated (from friends, family and even fans at games) it is possible this does have an affect on team performance. My interest in the length of the regular season stems from the fact that the NBA left the remaining games of the 2019-20 season unplayed. If these games were consequential they should have been played, but these games obviously were not played. The site FiveThirtyEight published a series of articles on  where teams which participated in the NBA playoff Bubble rank in regards to their likelihood of winning the championship. A particular article of this series discusses teams with a low probability of winning it all, "Teams Just Along for the Ride" by [Jared Dubin](https://fivethirtyeight.com/features/whos-who-in-the-nba-bubble-the-teams-just-along-for-the-ride/)[5]. The idea that teams who barely qualify for the playoffs may have a reduced chance of winning the championship could imply that the remaining 25% of games unplayed in the 2019-20 season may not be important.  Jared Dubin's articles suggest the teams with the highest percentage of regular season wins to losses also have the best chance of winning the championship, and these top teams have no need of additional regular season games. It's the teams that just barely didn't qualify that may want additional regular season games, and even if they were to qualify with the extra games, these teams would have only a small chance of beating the other teams. Sports analytics and the NBA Bubble in particular is a well-trod area of research, but despite much previous work I have not found satisfying answers to the questions I am interested in.\

References:
1. Abrams, D., & Hogg, M. A. (1988). Comments on the motivational status of self-esteem in social identity and intergroup discrimination. European Journal of Social Psychology, 18(4), 317–334. https://doi.org/10.1002/ejsp.2420180403


2. Norris, J.I., Wann, D.L. and Zapalac, R.K. (2015), "Sport fan maximizing: following the best team or being the best fan?", Journal of Consumer Marketing, Vol. 32 No. 3, pp. 157-166. https://doi.org/10.1108/JCM-02-2014-0856


3. Anderson, Sam. “What I Learned Inside the N.B.A. Bubble.” The New York Times, The New York Times, 30 Sept. 2020, www.nytimes.com/2020/09/30/magazine/nba-bubble.html.


4. Spichak, Simon. “The Basketball in the Bubble.” Medium, Towards Data Science, 29 July 2020, towardsdatascience.com/the-basketball-in-the-bubble-cfec7976574b.


5. Dubin, Jared. “Who's Who In The NBA Bubble: The Teams Just Along For The Ride.” FiveThirtyEight, FiveThirtyEight, 20 July 2020, fivethirtyeight.com/features/whos-who-in-the-nba-bubble-the-teams-just-along-for-the-ride/.

### Methodology

For Question 1.a we will look at the previous ten years of regular season data and select only games played before March 11th(this is the date play was stopped due to Covid-19). We will then use the NBA Bubble select method(top eight teams in both conferences as well as the next six best teams overall, 22 teams total) to choose hypothetical playoff teams. We will then compare the hypothetical teams to the historical playoff teams and use a Welch t-test to asses significance. Welch t-test will be used as it does not assume equal variance.

For Question 1.b we will use the same method as question 1.a, but instead of using the March 11th date as the cut off we will use percentage of games played. During the 2019-20 season only 75% of scheduled games were played so we will look at the first 75% of games played for each of the ten seasons prior to the most recent season. We will then use the NBA Bubble selection method to determine playoff teams and compare this result with historical playoff teams, using a Welch t-test to asses significance.

For Question 2 we will calculate the mean difference in mean scoring between the regular season and the playoffs per year. We will then compare the mean difference in mean scoring between the most recent 2019-20 season and the ten seasons previous, using a Welch t-test to asses significance.

### Findings

We rejected the null hypotheses in all cases and determined that within the bounds of our investigation there is no siginficant difference between this most recent season and the ten seasons prior. This does not imply there is no difference in areas which were not tested. Within the scope of this project it seems the NBA Bubble selection method was appropriate and play in the NBA Bubble is not significantly affected compared to the previous ten years.

### Conclusion

2019-20 season play was not significantly different than the ten previous years.

Results of the 2019-20 season seem as legitimate as previous ten seasons based on game score.

Further research could take a look at individual player performance between the regular season and the NBA Bubble playoffs, or aspects of team performance other than game score.

Possible Takeaway: The NBA outcomes seem reasonably robust to schedule and format change, and may continue to be trusted during tumultuous times.



