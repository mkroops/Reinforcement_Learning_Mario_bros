# Reinforcement_Learning_Mario_bros

To play
super mario bros version 2 Deep Reinforcement Learning (DRL) has
been used to train agents to play. The agents are trained using
different state representations and learning algorithms and their
performances are evaluated using metrics such as Avg. Reward,
Avg. Q-Value, Avg. Game Score, Avg. Steps Per Episode, and
Training and Test Times. The main goal of solving reinforcement
learning problems is to choose the best course of action to take
in each situation in order to maximise the reward. However,
unlike other forms of machine learning, the learning system
is not given instructions on what to do.

Reinforcement learning method was used to solve task 2.
This algorithm will train agents to make decisions in an
environment by learning through feedback mechanisms in the
form of rewards or punishments. The agent take action in the
environment and gets feedback in the form of a rewards which
indicates how well it is performing. Learning a policy that
maximises the expected cumulative reward over time is what
the agent aims to do.
A. Proximal Policy Optimization (PPO)
PPO algorithm uses objective function and an advantage
function to identify how good an action in a given state.
Ratio of the probabilities of selecting an action under the
new and old policies is determined by objective function
whereas advantage function measures how much better an
action compared to average action in a given state.
It helps in preventing policy collapse and improve stability
by limiting the changes in policy during optimization using
clipping mechanism.
B. Deep Q-Network (DQN)
Based on maximum Q-value DQN agent selects actions ob-
tained from a neural network with weights θ, where Q-values
represent the expected future rewards. By minimising the loss
function while using the replay memory buffer, the agent
learns the ideal Q-values, where θ - i denotes the target weights
and θi is the online weights. The loss function is the mean
squared error between the predicted Q-value and the target Q-
value. DQN agents use exploration/exploitation policies such
as e-greedy, Softmax, Boltzmann and hyperparameters such
as learning rate, discount factor, batch size, and network
architecture which significantly impact the performance of
DQN.
C. Advantage Actor-Critic (A2C)
The Actor-Critic (A2C) algorithm is a reinforcement learn-
ing algorithm which uses two neural networks such as the
Actor and the Critic, It is used to learn an optimal policy for
a given environment. The Actor and Critic networks are trained
simultaneously to maximize the expected total reward. Based
on the current policy Actor is responsible for selecting actions
by generating a probability distribution over actions in each
state and updates Advantage function whereas the Critic is
responsible for estimating the value of each state updates Tem-
poral difference error. The A2C method outperforms previous
reinforcement learning algorithms in terms of performance and
convergence speed by combining the benefits of the Actor and
Critic techniques.
