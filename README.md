This Project is all about basic implementation and exploration of Reinforcement Learning in field of Quantitative Trading.

I have explored Deep Learning + Reinforcement Learning coalition based algorithm -  Deep Q-Learning Neural Network.

the formula that model is based on is

![image](https://github.com/BD1634/Trading_Strategies_Using_RL/assets/97423675/a1c46455-8550-40e2-b4b0-88f7e7d5b037)


The key components of the RL based framework are :

Agent: Trading agent.

Action: Buy, sell or hold.

Reward function: Realized profit and loss (PnL) is used as the reward function for this case study. The reward depends upon the action:

Sell: Realized profit and loss (sell price - bought price)

Buy: No reward

Hold: No Reward

State: Differences of past stock prices for a given time window is used as the state.

I have also modified and developed certain aiding functions that would help with formatting and plotting of the visualisations

