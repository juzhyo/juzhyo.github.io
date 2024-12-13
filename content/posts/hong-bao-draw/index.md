---
title: Hong Bao Draw
date: "2024-12-09"
draft: true
math: true
plotly: true
---
Around the time of Lunar New Year, Singapore Pools will organise a special lottery event called the Toto Hong Bao Draw, which features a significantly larger jackpot prize compared to the regular draws. The Hong Bao Draws, with their larger prize money, attracted people to participate, suggesting that it may be worth placing a bet.

The Kelly criterion is used to evaluate if this is the case. It is a formula for sizing a sequence of bets by maximising the geometric growth rate of wealth. For a system where the bettor wins or loses a fixed percentage of his bet, the Kelly criterion reads: 

$$\begin{aligned}
f & = p - \frac{q}{b} \\
& = p - \frac{1-p}{b}
\end{aligned}$$

where \(f\) is the fraction of one's capital, \(p\) the probability of winning, \(q\) the probability of losing, and \(b\) the odds of the bet.

The values for \(p\) are as shown below

| Prize Group    | Matched Numbers | Odds of Winning |
| :--------: | :-------: | :--------: |
| 1 (Jackpot)  | 6 Winning Numbers    | 1 in 13,983,816 |
| 2 | 5 Winning Numbers + Additional Number     | 1 in 2,330,636 |
| 3    | 5 Winning Numbers    | 1 in 55,491 |
| 4    | 4 Winning Numbers + Additional Number   | 1 in 22,197 |
| 5    | 4 Winning Numbers    | 1 in 1,083 |
| 6    | 3 Winning Numbers + Additional Number    | 1 in 812 |
| 7    | 3 Winning Numbers    | 1 in 61 |

[Source: Singapore Pools](https://online.singaporepools.com/en/lottery/toto-statistics-history)

Considering only the jackpot, where the prize money had been around $12 million historically, \(b = 12\times 10^6\) for a $1 minimum bet.

{{<plotly json="/plotly/hong-bao-draw.json" height="400px">}}

