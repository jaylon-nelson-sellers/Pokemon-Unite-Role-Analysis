# Pokemon Unite Role Analysis
This analysis focuses on player roles and their impacts within the game of Pokemon Unite.
# Introduction
Pokemon Unite is a multiplayer online battle arena (MOBA) where two teams of five players aim to score the most points. This is accomplished through farming nonplayer characters, defeating opposing players, and scoring on enemy goals. While the genre has existed since the 2000s, Pokemon Unite players are often new to genre and make unusual decision. One common issue that veteran MOBA players have with Unite players is the playerbases unwillingness to "fill" roles. MOBA's traditionally have five main roles. 
- **DPS & Mages (Attackers)**: Deals the most damage at range, while having low health. These are Carries: characters which "carries" most of the team's attack damage.
- **Assassins (Speedsters)**: Deals bursts of damage, but is very easy to take down. Also Carries.
- **Bruisers (All-Arounders)**: Weak early into the game. If played well, can deal both high damage and has high health. These are also carries.
- **Tanks (Defenders)**: Verg high health and has the ability to stun enemies. This can be grouped into the broad "support role".
- **Support**: Often pose healing or methods to enhance teammate or hinder enemy ability. "This can also be grouped in the overall "support" role.
The issue is that the majority of unite players find little need in filling less attractive support roles, and would prefer to play carry roles. Often players defend this action, claiming that carry roles alloow them to win games more directly. Thus the purpose of this analysis is to examine various player games and to determine if having the support role on a team lead to more wins.

## Hypothesis
Teams with supports have a significant higher win rate than teams without a healer.
## Null Hypothesis
There is no significant difference in win rates between teams with a support and teams without one.

## Variables
- **Independent Variable**: Presence of a Support Role (Defender/Support) (Yes/No).
- **Dependent Variable (DV)**: Match outcome (Win/Loss).
- **Control Variables**: 
    - Players Recorded
    - Player's Skill (Games Played, Winrate, et)
    - Number of Games Recorded 
    - Player's Average Queue Size (How many friends are playing in a lobby together)
## Sample Information
- 362 Games Recorded
- 15 Players Recorded
    - 6 Professional Players
    - 6 Streamers: 
    - 6 Casuals
###  Role Conditional Probability Analysis 
#### Player Stats
1. Player's Team With vs. Without Support
With Support: 156 wins out of 240 games (Win Rate: 65.00%)
Without Support: 72 wins out of 122 games (Win Rate: 59.02%)
2. Player's Team With vs. Without Defender
With Defender: 191 wins out of 303 games (Win Rate: 63.04%)
Without Defender: 37 wins out of 59 games (Win Rate: 62.71%)
3. Player's Team With Support OR Defender vs. Without Support OR Defender
With Support OR Defender: 221 wins out of 351 games (Win Rate: 62.96%)
Without Support OR Defender: 7 wins out of 11 games (Win Rate: 63.64%)
4. Player's Team With Support AND Defender vs. Without Support AND Defender
With Support AND Defender: 126 wins out of 192 games (Win Rate: 65.63%)
Without Support AND Defender: 102 wins out of 170 games (Win Rate: 60.00%)
#### Enemy Stats
1. Enemy Team With vs. Without Support
With Support: 74 wins out of 211 games (Win Rate: 35.07%)
Without Support: 60 wins out of 151 games (Win Rate: 39.74%)
2. Enemy Team With vs. Without Defender
With Defender: 108 wins out of 303 games (Win Rate: 35.64%)
Without Defender: 26 wins out of 59 games (Win Rate: 44.07%)
3. Enemy Team With Support OR Defender vs. Without Support OR Defender
With Support OR Defender: 126 wins out of 339 games (Win Rate: 37.17%)
Without Support OR Defender: 8 wins out of 23 games (Win Rate: 34.78%)
4. Enemy Team With Support AND Defender vs. Without Support AND Defender
With Support AND Defender: 56 wins out of 175 games (Win Rate: 32.00%)
Without Support AND Defender: 78 wins out of 187 games (Win Rate: 41.71%)
#### With vs Without
Player's Team Results
Support
Both Teams Have Support: 102 wins out of 155 games (Win Rate: 65.81%)
Only Player Team Has Support: 54 wins out of 85 games (Win Rate: 63.53%)

Defender
Both Teams Have Defender: 162 wins out of 253 games (Win Rate: 64.03%)
Only Player Team Has Defender: 29 wins out of 50 games (Win Rate: 58.00%)

Support OR Defender
Both Teams Have Support OR Defender: 207 wins out of 329 games (Win Rate: 62.92%)
Only Player Team Has Support OR Defender: 14 wins out of 22 games (Win Rate: 63.64%)

Support AND Defender
Both Teams Have Support AND Defender: 77 wins out of 109 games (Win Rate: 70.64%)
Only Player Team Has Support AND Defender: 49 wins out of 83 games (Win Rate: 59.04%)

Enemy's Team Results
Support
Both Teams Have Support: 53 wins out of 155 games (Win Rate: 34.19%)
Only Enemy Team Has Support: 21 wins out of 56 games (Win Rate: 37.50%)

Defender
Both Teams Have Defender: 91 wins out of 253 games (Win Rate: 35.97%)
Only Enemy Team Has Defender: 17 wins out of 50 games (Win Rate: 34.00%)

Support OR Defender
Both Teams Have Support OR Defender: 122 wins out of 329 games (Win Rate: 37.08%)
Only Enemy Team Has Support OR Defender: 4 wins out of 10 games (Win Rate: 40.00%)

Support AND Defender
Both Teams Have Support AND Defender: 32 wins out of 109 games (Win Rate: 29.36%)
Only Enemy Team Has Support AND Defender: 24 wins out of 66 games (Win Rate: 36.36%)

# Chisquare tests
- Support vs No Support
