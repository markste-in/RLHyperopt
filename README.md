# RLHyperopt
A simple example of Q-Learning with automatic hyperparameter search using hyperopt and gym

Gym environment: FrozenLake4x4 and FrozenLake8x8

Hyperopt is used to search the whole space of alpha, gamma, epsilon and num_episodes (up to 10000).
The results will be displayed at the end of the notebook. 

![Result of the search](pictures/hyperopt1.png?raw=true "Result of the search")

There is also a full pairplot

![Pairplot result](pictures/hyperopt2.png?raw=true "Pairplot result")
