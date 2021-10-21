# MDP
""""In these code you will able to understand how the MDP works, Beofre that for your informaton you can take a look at
https://www.csie.ntu.edu.tw/~b91046/meeting/m2/mdp.pdf for your concern about the Bellman equation 

What is q-learning?
Q-learning is an off policy reinforcement learning algorithm that seeks to find the best action to take given the current state

It’s considered off-policy because the q-learning function learns from actions that are outside the current policy,
like taking random actions, and therefore a policy isn’t needed. More specifically, q-learning seeks to learn a policy that 
maximizes the total reward.

The ‘q’ in q-learning stands for quality. Quality in this case represents how useful a given action is in gaining some future reward.

So then here we will see q learing  reinforcement learning with reward function

in these code we will import numpy library as ql

ql is an nxp matrix from A for QL decomposition

A is list of two matrices Q and L so that A = QL

Q - nxp matrix with orthonormal columns with the same span as A

L - is a lower triangular pxp matrix with nonnegative diagonal entries
________________________________________________________________________________________________________________________________________________________________________________
For MDP we will use two variable R as reward and Q as learininf Matrix

R - is reward matrix for each state

Q - is the Learning Matrix in which rewards will be learned/stored
