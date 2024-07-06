This Project is all about basic implementation and exploration of Reinforcement Learning in field of Quantitative Trading.

I have explored Deep Learning + Reinforcement Learning coalition based algorithm -  Deep Q-Learning Neural Network.


The key components of the RL based framework are :

Agent: Trading agent.

Action: Buy, sell or hold.

Reward function: Realized profit and loss (PnL) is used as the reward function for this case study. The reward depends upon the action:

Sell: Realized profit and loss (sell price - bought price)

Buy: No reward

Hold: No Reward

State: Differences of past stock prices for a given time window is used as the state.
