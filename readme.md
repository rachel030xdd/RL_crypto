# Portfolio Management of Cryptocurrencies using Reinforcement Learning

In the complex landscape of financial markets, the ratio of noise to signal is often low, making it challenging for traders and investors to discern the best strategies for optimizing their portfolios. With the ever-changing dynamics of market conditions, even the advantage of hindsight does not always reveal the most effective trading policies. In this context, Reinforcement Learning emerges as a powerful tool to learn optimal trading policies without requiring an explicit model to predict price movements.

In this project, we explore the use of Reinforcement Learning to discover hidden patterns for trading cryptocurrencies and devise trading policies. We designed customized state space to allow the agent to consider different aspect of the market and stock before trading; different action space to let agent only consider long or both long and short. By refining the state and action space, the goal is to enhance the agent's ability to adjust to the market fluctuation, not only to mitigate the effects of overfitting, but also to increase the generalizability of the RL model to different market scenarios. Then the agent is trained using A2C, PPO, and DDPG algorithms after parameter tuning. The performance is measured by portfolio return, and is compare against two baselines strategies based on mean reversion and momentum. 

You can read the final report in <Project_report.pdf>.