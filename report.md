# Collaboration and Competition Project Report

## Deep Deterministic Policy Gradient (DDPG)
[DDPG](https://arxiv.org/pdf/1509.02971.pdf) implemeted as part of this project, is an offline policy method in which two architectures are combined: 1) Actor which is utilized to determine the current policy in continuous space and 2) Critic which is used to learn the Q-values in a given (state, action) pair. For more details, please take a look at [2](https://arxiv.org/pdf/1509.02971.pdf). 

## Multi-Agent Deep Deterministic Policy Gradient (MADDPG)
[MADDPG] (https://papers.nips.cc/paper/7217-multi-agent-actor-critic-for-mixed-cooperative-competitive-environments.pdf) was utilized to train two agents to play tennis.

## The Training Parameters and Result:
The parameters for this project are:

| Parameter     | Value     | Description |
| ------------- | --------- | ------------- |
| BUFFER_SIZE  | 1e5  |  replay buffer size |
| BATCH_SIZE  | 256  | replay buffer minibatch size|
| GAMMA  | 0.998  | discount factor |
| TAU  | 1e-3  | for soft update of target parameters |
| LR_ACTOR  | 1e-4  | learning rate of the actor used in the Adam optimizer |
| LR_CRITIC  | 1e-3  | learning rate of the critic used in the Adam optimizer |


## Result

The average score of 0.6 was reached at 758 episodes:

![alt text](https://github.com/AghaAmin/DRLND-P3-Collaboration-and-Competition/blob/master/result.png)

## Ideas for Future Work
Implementing PPO and comparing the results with MADDPG
