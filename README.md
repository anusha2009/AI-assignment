Assignment 1 : 

1. Implement an agent module/class Agent that uses Heuristic Search for choosing an action to take given a state. The agent uses an independent module/class Game for functions defining state transitions and states neighborhood and a module/class Heuristics for definitions of heuristic functions.

2. Choose two different problems/games/puzzles and provide a statistical experimentation on several problem instances for comparatively evaluating the agent performance using different search algorithms and different heuristics

Assignment 2:

1. Augment your implementation of alhabetaMinMax by making it explore only most promising states according to their H0 “static” evaluation for computing their HL value.

- Experiment and report results observed when compared to the original alhabetaMinMax

2. Generalize a bit by making it compute HL according by exploring only most promising states according to their Hl evaluation, 0<l<L

-Experiment and report results observed for different choiches of l. Try to look for an optimal l whe L=10 (or maybe more …)

3. Define your H0 as a function f(h1,…,hn) where hi are “observations ”on the state.

Import a regressor R and train it for predicting HL (s) given static h1(s),…,hn (s) by making the agent play…

Modify your previous implemenation by making it use the R predictions instead of static evaluations.

- Experiment and report comparative results with respect to previous alhabetaMinMax versions.

Assignment 3: 

Cooking Chef Problem - Reinforcement Learning
