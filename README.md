# AI_RLBasedSystemforCabDriver

**Project Objective:-**
The goal of our project is to build an RL-based algorithm which can help cab drivers maximize their profits by improving their decision-making process on the field.

In this highly competitive industry, retention of good cab drivers is crucial in business. Cab drivers, like most people are incentivized by a healthy growth in income.  The Need for Choosing the 'Right' Requests Most drivers get a healthy number of ride requests from customers throughout the day. But with the recent hikes in electricity prices (all cabs are electric), many drivers complain that although their revenues are gradually increasing, their profits are almost flat. Thus, it is important that drivers choose the 'right' rides, i.e., choose the rides which are likely to maximize the total profit earned by the driver that day.  The Need for Choosing the 'Right' Requests Most drivers get a healthy number of ride requests from customers throughout the day. But with the recent hikes in electricity prices (all cabs are electric), many drivers complain that although their revenues are gradually increasing, their profits are almost flat. Thus, it is important that drivers choose the 'right' rides, i.e., choose the rides which are likely to maximize the total profit earned by the driver that day.
For example, say a driver gets three ride requests at 10 PM. The first one is a long-distance ride guaranteeing high fare, but it will take him to a location which is unlikely to get him another ride for the next few hours. The second one ends in a better location, but it requires him to take a slight detour to pick the customer up, adding to fuel costs. Perhaps the best choice is to choose the third one, which although is medium distance, it will likely get him another ride subsequently and avoid most of the traffic.


**APPROACH: -**
In this project, we need to create the environment and an RL agent that learns to choose the best request. We need to train our agent using Deep Q-learning (DQN).
Goals: -
Create the environment: 
The ‘Env.py’ file is the "environment class" - each method (function) of the class has a specific purpose.
Build an Agent:
Build an agent that learns to pick the best request using DQN. We can choose the hyperparameters (epsilon (decay rate), learning-rate, discount factor etc.) of our choice.
Training depends purely on the epsilon-function we choose. If it decays fast, it won’t let our model explore much and the Q-values will converge early but to suboptimal values. If it decays slowly, our model will converge slowly.

For more detials go through the attached Project documentation.
