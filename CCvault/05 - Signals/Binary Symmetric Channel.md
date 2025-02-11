---
tags:
  - probability
  - signals
use:
---
The Binary Symmetric Channel (BSC) is a way to model the probability of bit errors (flips) in a binary transmission. We start on the transmission side (X) and cross to the receiver side (Y). X has two options 0,1. Y has the same. 

![[The-binary-symmetric-channel-with-cross-over-probability-p.png]]

You start with a transmitted bit. The probability of a correct transmission is $1-p$. Correct being $X=0$ and $Y=0$ or $X=1$ and $Y=1$. The probability for a flipped bit is $p$.

$p$ is the crossover probability.

p can be limited to 0.5. Because above 0.5 the interpretation of 0 and 1 can be swapped. 