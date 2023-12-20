# Artificial Intelligence

## Topics to be covered:
- [x] Reinforcement Learning
- [ ] The Bellman Equation
- [ ] The Plan
- [ ] Markov Decision Process(MDP)
- [ ] Policy vs Plan
- [ ] Adding a living penalty
- [ ] Q-Learning Intuition
- [ ] Temporal Difference
- [ ] Q-Learning Visualization

### Reinforcement Learning
1) Environment in AI is the surroundings or circumstances in which the AI system functions.
2) Agent: It is the AI/mind that navigates the environment and learns from the feedback given by the environment while it performs certain actions.
3) The agent does actions on the environment which changes the state and gets a reward. By repeating this process the agent will keep on learning and exploring the environment about which action results in a good reward and a favorable state.

### Bellman Equation
1) The long-term reward for a given action is equal to the reward from the current action combined with the excepted reward of the future action to be performed at the moment.
2) V(s)=maxa(R(s,a)+ γV(s’))
      -  V is value
      -  s is the current state
      -  a is action
      -  V(s) is the value at the current state s
      -  V(s') is the value at the next/future state s'
      -  R(s,a) is Reward for being in state s and performing action a
      -  γ(Gamma) is the discount factor
3) Discount Factor(γ):
   -  represents how much the agent cares for the rewards in the distant future to those in the immediate future.
   -  It is between 0 to 1.
   -  Larger discount factor means the client is looking for a reward in the long term.

 ### Plan
 

