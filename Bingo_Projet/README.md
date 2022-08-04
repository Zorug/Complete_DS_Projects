# Analysis of Some Online Bingo Game

## About this Project
FABAMAQ produces games for several international markets, so their analysis is essential for the production of games aimed at each target audience/market.
One category of these games are bingo games, from which this project was created. They can be found [here](https://fbm.digital/1#bingo "FBMDS - Video Bingo").

Typically, 30 starting balls are randomly drawn in the game. Under certain conditions, the player has the opportunity to buy up to a certain number of extra balls (variable depending on the game), in order to fill in the numbers on their game cards, winning prizes according to predefined patterns. The biggest prize is bingo (filling in all the cells on a card). Each extra ball has a variable price, depending on factors related to the total possible winnings.

## Objectives of the Project
Based on this, this project has the following objectives:
- To make a exploratory analysis of the variables, comparing different games;
- Analysis the correlations in the dataset;
- Research and create predictive models of buying or not an extra ball that fit in each specific game.

## Dataset Information
This dataset compiles information from 3 different markets and 3 different games. Market M has a sample of two games (game_1 and game_2). Market E and I have samples from a similar game, game_03.

- game_id           - code for a game round where a played were offered the possibility of buying extra balls;
- bet               - the amount of credits (cr) per card;
- denomination      - value (in local currency) of each credit;
- ballIdx           - index of a given extraball;
- nr_cards          - number of open cards for a given game round;
- ball_price        - price (cr) of a given extra ball;
- won               - cumulative winnings (cr) of a game round;
- highest_oneaway   - highest prize (prize id for a specific prize table**) that the player is able to win at a specific point in the game. Higher ids translate to better prizes;
- total_oenaway     - sum of all the prizes that the player is able to win;
- bought            - decision of the player. Buy or not to buy an extra ball;
- highest_prize_won - the highest prize won on a specific extra ball and game round (prize id for a specific prize table**). Higher ids translate to better prizes;
- bonus_prize       - in case of entering a bonus, the amount (cr) won by the player;
- market            - code for a specific market;
- game              - code for a specific game.

** Prize table refers to a group of patterns of which the player gets prizes. The less probability of getting a pattern, the higher is the prize.

![Prize table](https://github.com/Zorug/Projetos_Completos/blob/master/Bingo_Projet/prize_table.png?raw=true)

## Developer
| [<img src="https://avatars.githubusercontent.com/u/54179576?v=4" width=115><br><sub>Cassiano Gross Schuler</sub>](https://github.com/Zorug) | 
| :---: |
