# Ensemble-model-Reinformance-learning
The objective of the first question is to use the ensemble learning functionality to identify the 
extent to which classification performance can be improved through the combination of 
multiple models. Experiments will be run on a dataset extracted from US Census data. The 
data contains 14 attributes including age, race, sex, marital status etc, and the goal is to 
predict whether the individual earns over $50k per year. 

The objective of the second question is to explore the usage of reinforcement learning to 
learn strategies for combinatorial tasks. You are given a set of 10 balls and 10 bins (numbered 0 to 9). Initially, all the balls are in the 
bin number 5 and your goal is to ensure that the balls are well distributed across the bins 
eventually. Ideally, all balls should be in different bins. Train a reinforcement learning (RL) 
agent that should consider all balls in turn and for each ball b, decide whether to keep the 
ball in the current bin Bb or move it to the bin Bb - 1  or move it to the bin Bb + 1. Note that the 
action to move to bin Bb - 1 is only permissible if Bb – 1 >= 0 and the action to move it to the 
bin Bb + 1 is only permissible if Bb + 1 <= 9. 
