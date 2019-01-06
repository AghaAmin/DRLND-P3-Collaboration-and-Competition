# Collaboration and Competition Project Report

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
