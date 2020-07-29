Agent is being in an Environment . 
perform certain Action  - change the state s to St+1 
Get Reward 
goal -  is to maximize the reward   | reward is scaler 

keywords -  Agent, Environment , Action(A), reward(R) , states(S), policy , Value(V), Action Value(Q)
Agent is Algorithm
value -  long term retun with discount 
gamma value -   [0, 1]  -  discounting of value based on Gamma. 
State-value function associated with discounted reward .

policy(pie)  -  agent's action is modeled via policy 
policy gradient 
sparce reward setting -  Not every moment we assign the reward.
Reward is assigned after few action when we get result.
reward shaping ...

Exploration and Exploitation :- 
controlling the amount of exploration vs. exploitation  via epsilon . Probability is calculated 
0<epsilon<1   

Markov decision process:
Mapping a solution in RL to markov decision process
The below parameters are used to attain a solution 
1.set of actions
2.set of states
3.reward
4.policy
5.Value 

Q- learning :
Build a Q matrix  -   Represents the memory the agent has learned from experience 

row represents current states of the Agent 
Column represent  possible actions  leading to next states.
Q(state, Action ) = R(state,actions) + Gamma*max [ next state, all actions ]

if gamm is close to 0  ->> agent will tend to consider immediate reward 
if gamm close to 1 --> agent will consider future reward with greater weights.

dynamic programming

Policy iteration consists of two steps: policy evaluation and policy improvement.
we can use Monte carlo method for Policy iteration. 
Monte carlo -  Repeated random sampling to obtain numerical result .
Use randomness to solve problem that might be determinstic .

Function aproximation :

Various RL Algorithm:
1.Monte Carlo
2.Q -learning  : State–action–reward–state
3. SARSA : State–action–reward–state–action
4.Q-learning - Lambda
5.Deep Q n/w

all are model free  - Model free means trial and error  algorithm 
