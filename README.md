# **Soccer Forecasting Model**

## **Overview**

This project builds an end-to-end algorithmic pipeline to identify mispriced odds in high-liquidity football betting markets. Rather than relying on intuition or subjective analysis, the goal was to develop a repeatable, data-driven edge by generating calibrated "fair lines" and comparing them against bookmaker pricing across 1X2, Over/Under 2.5, Asian Handicap, and other markets.

## **Key Findings**

* The model's pre-match xG projections achieve an MAE of  **0.847**, landing within **0.061 goals** of post-match xG accuracy — despite having no access to actual shot data.
* Probability estimates are **better calibrated** than market odds in both 1X2 (ECE 0.029 vs 0.039) and Over/Under 2.5 (ECE 0.035 vs 0.039).
* A 6-month backtest on 5,000+ bets yielded  **8.76% ROI** , **$129K profit** from a $10K starting bankroll, and a portfolio Sharpe ratio of  **3.48** .
* Asian Handicap and Over/Under 2.5 were the most profitable markets, generating  **$115K+ combined** . Correct Score produced negative returns despite high volume.
* A simulation study (10,000 randomized runs) confirms the results are non-random, with a  **p-value of 0.0013** .

For the complete story, visuals, business methodology, and full performance breakdown → check out the **[GitHub Project Page](https://www.notion.so/Advanced-Soccer-Forecasting-Model-322b7682d7a780b7a49ac85b794058a8)**.
