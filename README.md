This Project is all about basic <b>implementation and exploration of Reinforcement Learning in field of Quantitative Trading.</b>

I have explored Deep Learning + Reinforcement Learning coalition based algorithm -  Deep Q-Learning Neural Network.

the reward model that the neural network is based on is

![image](https://github.com/BD1634/Trading_Strategies_Using_RL/assets/97423675/a1c46455-8550-40e2-b4b0-88f7e7d5b037)

here,

<b>Q</b> is the Q-Value which is the actual reward.<br>
<b>R</b> is the immediate reward <br>
<b>alpha</b> is the learning rate<br>
<b>(s,a)</b>  is the state, action pair <br>
<b>gamma</b> is the discount factor to decrease the reward in latter phases of training.<br>

The Neural Network learns to approximate this Q-value function inturn helps the agent learn what to do.

The key components of the RL based framework are :

Agent: Trading agent.

Action: Buy, sell or hold.

Reward function: Realized profit and loss (PnL) is used as the reward function for this case study. The reward depends upon the action:

Sell: Realized profit and loss (sell price - bought price)

Buy: No reward

Hold: No Reward

State: Differences of past stock prices for a given time window is used as the state.

I have also modified and developed certain aiding functions that would help with formatting and plotting of the visualisations.

