---
title: "Neural Network-based Information Set Weighting for Playing Reconnaissance Blind Chess"
date: 2024-08-07
---
In imperfect information games, the game state is generally not fully observable to players. Therefore, good gameplay requires policies that deal with the different information that is hidden from each player. To combat this, effective algorithms often reason about information sets; the sets of all possible game states that are consistent with a player's observations. While there is no way to distinguish between the states within an information set, this property does not imply that all states are equally likely to occur in play. We extend previous research on assigning weights to the states in an information set in order to facilitate better gameplay in the imperfect information game of Reconnaissance Blind Chess. For this, we train two different neural networks which estimate the likelihood of each state in an information set from historical game data. Experimentally, we find that a Siamese neural network is able to achieve higher accuracy and is more efficient than a classical convolutional neural network for the given domain. Finally, we evaluate an RBC-playing agent that is based on the generated weightings and compare different parameter settings that influence how strongly it should rely on them. The resulting best player is ranked 5 th on the public leaderboard.


[Link to PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10592629)
