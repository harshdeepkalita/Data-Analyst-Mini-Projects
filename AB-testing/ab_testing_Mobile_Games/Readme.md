## Introduction
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. It also features singing cats. We're not kidding!
<br><br>
<center><img src="https://i.pinimg.com/originals/eb/3c/4b/eb3c4b5be29530a68c32434297d6f8b5.png" width=200/></center>
As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention.

<center>

|Data columns|Purpose|Valid values|
| ------------- |:-------------| -----:|
|userid| A unique number that identifies each player.|Category values|
|version| Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).|category|
|sum_gamerounds|The number of game rounds played by the player during the first 14 days after install.`|int64|
|retention_1|Did the player come back and play 1 day after installing?|Boolean|
|retention_7|Did the player come back and play 7 days after installing?|Boolean|
</center>

### Q) Should the first gate in Cookie Cats be moved from level 30 to level 40?
**The answer is divided into 2 parts:**
1) Probability, AB Testing, Z-Score Hypothesis Testing for Day 1 Retention.<br>
2) Probability, AB Testing, Z-Score Hypothesis Testing for Day 7 Retention.

## Conclusion
-  50% of the Players are quiting the game after reaching the 16th round and  75 % of the Players are quitting the game after reaching the 51th round. The reasons for quitting the game could be:- 
    - Levels after this round are really tough to crack
    - The players are getting bored after this level
    - and many more.
- The company should send a feedback form/survey to each customer/player and analysis the root cause of this problem.
- We have strong statistical evidence to proof that, the day 1 and day 7 Retention Rate of players when they encounter the gate_30 level is higher than when they are gate_40 level.

    - The "Day 1 retention rate" for the players when they encounter the gate level 30 is <b>0.0059%</b> greater than The "Day 1 retention rate" of players when they encounter the gate level 40.
    - The "Day 7 retention rate" for the players when they encounter the gate level 30 is <b>0.0082%</b> greater than The "Day 7 retention rate" of players when they encounter the gate level 40 .
### It is recommended that they do not move the gate level from 30 to 40.
